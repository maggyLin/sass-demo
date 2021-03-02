## SASS 安裝
* 使用 Node.js 安裝 $ npm install -g sass
* 確認版本  $ sass --version

## 編譯
* sass css/xxx.scss:css/xxx.css
* sass test.scss test.css (注意路徑指向)

## 監聽 scss，檔案有修改，css 變會即時的進行編譯 (多增加watch)
* sass --watch css/xxx.scss:css/xxx.css
* sass --watch . (目前指向目錄底下全部逕行監聽,不指定檔案)
* sass --watch sass:css (目錄下全部監聽：監聽 sass 目錄下的 sass/scss 檔案到指定的 css 目錄下)

<hr>

### 參考資料
> https://frankknow.com/sass-tutorial/
