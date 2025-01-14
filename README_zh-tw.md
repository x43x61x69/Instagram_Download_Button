# Instagram Download Button
[Github](https://github.com/y252328/Instagram_Download_Button), [Greasy Fork](https://greasyfork.org/zh-TW/scripts/406535-instagram-download-button) ~~, [OpenUserJS](https://openuserjs.org/scripts/y252328/Instagram_Download_Button)~~

此腳本會在Instagram頁面上新增下載按鈕與開啟按鈕，透過這些按鈕可以下載或開啟大頭貼與貼文、限時動態、Highlight中的照片或影片

新版的程式只在Chrome上做了簡單的測試，所以如果有任何問題，歡迎與我聯繫並附上執行環境!

> Note: 目前此腳本只在Windows 10 1903 64-bit上的Chrome ~~、Edge與Firefox~~ 搭配Tampermonkey測試過

## 選項
透過修改腳本開頭中的常數變數可以設定此腳本。
* `attachLink` : boolean, 設為true時，將連結加入按鈕元素中
* `postFilenameTemplate` : string，貼文檔案的命名規則
* `storyFilenameTemplate` : string，現實動態的檔案命名規則

## Naming Template
* `%id%` : 貼文者的ID
* `%datetime%` : 貼文時間
* `%medianame%` : 原始的檔案名稱
* `%postId%` : 貼文ID
* `%mediaIndex%` : 檔案的序號
* ~~`%ext%` : 副檔名~~

## 快捷鍵 (在新版本中可能無法使用)
* `Alt` + `i` : 在新視窗開啟圖片/影片
* `Alt` + `k` : 下載圖片/影片
* `Alt` + `j` : 向前一個圖片/影片 (多圖貼文中)
* `Alt` + `l` : 向後一個圖片/影片 (多圖貼文中)

> 目前快捷鍵無法在Instagram主頁上使用

## Contributors
* [孙年忠](https://greasyfork.org/users/829246-%E5%AD%99%E5%B9%B4%E5%BF%A0)
* [FlowerForWar](https://github.com/FlowerForWar)
* [xxalexx](https://greasyfork.org/en/users/170052-xxalexx)

## 預覽
<img src="img/profile.png" alt="drawing" width="436" height="134"/>
<br/>
<img src="img/post.png" alt="drawing" width="467" height="294"/>
<br/>
<img src="img/story&highlight.png" alt="drawing" width="216" height="376"/>

## License
[MIT](https://github.com/y252328/Instagram_Download_Button/blob/master/LICENSE)