# web-meeting-java

## 環境建置
- 使用Intellij IDEA內建Smart Tomcat
- 重新build maven pom.xml
  
![image](https://github.com/SCYeh/Java_Web_Meeting_System/assets/88961674/bc26a6cb-cdae-438f-8b2e-db4b4fbd6680)
![image](https://github.com/SCYeh/Java_Web_Meeting_System/assets/88961674/ccb16f67-6f9f-47dc-a7d1-a4d040c2d17d)

## 錯誤紀錄
- 20240308
    - maven pom.xml spire.xls build failed，改為spire.xls.free後build success
    - jsp讀取script無法使用相對路徑，改為絕對路徑後才成功抓到檔案
    - 原先將upload Assessment ballot file轉換為html時，不知為何在讀取checkbox時奪讀取了一個特定的class，暫時刪除後恢復正常

## 環境設定
1. 到windows系統環境變數設定->進階->環境變數下方的系統變數點擊新增，
    變數名稱為JAVA_HOME，
    變數值選擇Meeting_system目錄下的jdk1.8.0_301目錄
2. 點擊連線的wifi內容，編輯IP設定，更正成手動，IPV4開啟，
    IP位址:192.168.0.124
    子網路首碼長度:24
    閘道:192.168.0.1
## 執行須知
1. 點擊Meeting_system目錄的.bat檔
2. 檔名不使用空白符號
