### 動機
身為外地來的大學生，在吃膩了學校餐廳及清夜後，常常不知道要吃甚麼，為了解決這個困擾，決定寫一款尋找餐廳的 bot，名稱為「EatWhat-Bot」，讓使用者能透過最簡單方便的方法來找到想吃的食物。

### 系統摘要
利用 Bottender 這個 Chatbot 的 framework，來開發 Telegram bot。藉由 bot 問特定問題，而使用者回答問題就能夠得到想要的資訊。

### bot 系統開發環境
- framework : Bottender
- 使用的程式語言 : Node.js
- 使用的 API : Telegram API、Google Maps API 
- 從 Google Maps API 抓取資料 : Axios 
- 讓內網的 localhost 讓外網的人看見 : ngrok 
- IDE : Visual Studio Code
- 使用的程式語言 : html、css、js
- IDE : Visual Studio Code
- 參考網站 : http://botender.mynmi.net/ 從參考網站下去改程式碼

### bot 功能說明
EatWhat-Bot 有三項功能。

#### 進入 bot 起始畫面
￼￼￼![](https://i.imgur.com/x2SwHHa.jpg)

#### 功能一、不知道要吃什麼:
這個功能的前提預設是給完全不知道要吃甚麼東西的人使用。 輸入位置以及最遠可接受的距離，bot 在接收這些資料後，會列出 Google Maps API 上的所有店家。選擇該店家後，即得到資訊。得到資訊後，選擇你 有興趣的店家，之後針對該店家會有兩個選項可以選擇:(1)查詢店家資訊、(2) 查詢店家位置。 點擊「查詢店家資訊」，會得到評等、地址、電話、營業時間、粉專或是網站網 址。點擊「查詢店家位置」，會送出該店家在 Google Map 上的位置。

- 回答現在所在位置以及可接受的店家距離 
![](https://i.imgur.com/XOTP6Yb.png)

- 選定店家後，點擊查詢店家資訊 
![](https://i.imgur.com/xY2D8Em.jpg)

- 選定店家後，點擊查詢店家位置 
![](https://i.imgur.com/e8VZs4V.png)

#### 功能二、想找特定店家資訊: 
這個功能的前提預設是給已經要吃哪家但不清楚店家資訊的人使用。 輸入你現在的位置，再輸入要找的店家名稱，bot 找到該店家資訊後，會出現 兩個選項 : (1)查詢店家資訊、(2)查詢店家位置。 點擊「查詢店家資訊」，會出現評等、地址、電話、時間、網站或是粉專網址。 點擊「查詢店家位置」會送出該店家在 Google Map 上的位置。

- 回答現在所在位置以及欲找的店家名稱  點擊查詢店家資訊- - 點擊查詢店家位置 
![](https://i.imgur.com/RD3F6we.jpg)

#### 功能三、查詢店家評價:
輸入想要評價的店家名稱，就會出現店家名稱、評等以及前4個最近評論。

- 輸入想知道的店家名稱 
![](https://i.imgur.com/tlMVRpt.png)

#### start 快捷鍵 
- 點按此按鈕即可重新開始
![](https://i.imgur.com/jRWcAmA.jpg)
![](https://i.imgur.com/Vn2Ieg4.png)


