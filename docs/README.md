# LibreNMS 安裝與使用

## Lubuntu 22.04 安裝 

### 製作 lubuntu 安裝開機 usb
1. 下載 lubuntu 22.04 iso 檔，使用軟體製作 usb 開機檔

lubuntu 22.04 https://lubuntu.me/downloads/

rusuf https://rufus.ie/zh_TW/

### 安裝 lubuntu
1.使用 usb 開機，執行第一個選項，就會先以 live cd 的模式進入 lubuntu 作業系統的界面，點選桌面的 install Lubuntu 圖示，就會開始安裝 lubuntu 
![install_lubuntu](2023-12-12-08-49-03.png)

2.依照安裝指示一直按下一步即可，以下僅顯示需要做選擇或輸入的部份提示
![](2023-12-12-08-49-52.png)

![](2023-12-12-08-50-07.png)

安裝完成後，移除 usb 後重新開機

3.安裝中文輸入法，在終端機（命令列）視窗內，
![](2023-12-12-08-50-31.png)


執行以下指令安裝中文輸入法

`sudo apt install fcitx5-chewing`


備註1： sudo 允許一般用戶以 root 或其他特定帳號執行程式

備註2： 不使用命令列安裝軟體，從功能表執行「」
![](2023-12-12-08-51-47.png)

![](2023-12-12-08-51-58.png)

以下說明將都使用命令列方式安裝，已方便複製、貼上指令
