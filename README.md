# 測試用 selenium 製作迷因
測試網址：https://memes.tw/maker/painter/21673  

# 注意事項：
- 點擊 "上下留白" 按鈕，可能會報錯，原因尚不明 (概率約 5% 左右)，若碰上再執行一次即可
- 盡量不要用 By.XPATH 去找網頁元素，因為每次進入都可能會不同
- 每張梗圖 textarea 數量、位置可能不同，所以之後需要調整
- 無頭模式 (headless) 程式碼會失效

# 操作步驟
0. 將檔案下載，放在 VS Code 上執行

1. 在終端機輸入以下指令：

```
pip install selenium
```

2. 直接執行程式碼 **執行之後甚麼都不要碰**  

3. 網頁自動關閉後 "pictures" 資料夾會多出新圖片   
![image](https://github.com/raamiiChu/selenium_gen_meme_test/assets/87169493/68f8b7da-a07f-4a09-935c-c1c0b6ded13e)
![我的梗圖創作-1684045485](https://github.com/raamiiChu/selenium_gen_meme_test/assets/87169493/22b6917c-ab45-4c24-a002-8ceb10a56804)
