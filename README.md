# https-github.com-yabukilab-shimoda-c<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>実験用</title>
    <link rel="stylesheet" href="stylesheet.css">
    <link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css">
  </head>
  <body>
    <header>
      <div class="container">
        <div class="header-left">
          <img class="logo" src="サイトロゴ">
        </div>
        <div class="header-right">
          <a href="#" class="login">メニュー</a>
        </div>
      </div>
    </header>
    <div class="top-wrapper">
      <div class="container">
        <h1>なんか書くとこ</h1>
        <h1>なんか書くとこ２</h1>
        <p>このHPでは時間や経済に配慮した津田沼周辺のサービスやスポットを紹介しています。</p>
        <p>紹介したモノ以外にもより良いものがあれば情報提供をお願いします。</p>
        <div class="btn-wrapper">
          <a href="#" class="btn signup">新規登録はこちら</a>
          <p>or sign up with</p>
          <a href="#" class="btn facebook"><span class="fa fa-facebook"></span>Facebookで登録</a>
          <a href="#" class="btn twitter"><span class="fa fa-twitter"></span>Twitterで登録</a>
        </div>
      </div>
    </div>
    <div class="lesson-wrapper">
      <div class="container">
        <div class="heading">
          <h2>SHOP SERVICE SPOT</h2>
        </div>
        <div class="lessons">
          <div class="lesson">
            <div class="lesson-icon">
              <img src="https://prog-8.com/images/html/advanced/html.png">
              <p>名前</p>
            </div>
            <p class="txt-contents">店の説明</p>
          </div>
          <div class="lesson">
            <div class="lesson-icon">
              <img src="https://prog-8.com/images/html/advanced/jQuery.png">
              <p>名前</p>
            </div>
            <p class="txt-contents">店の説明２</p>
          </div>
          <div class="lesson">
            <div class="lesson-icon">
              <img src="https://prog-8.com/images/html/advanced/ruby.png">
              <p>名前</p>
            </div>
            <p class="txt-contents">店の説明３</p>
          </div>
          <div class="lesson">
            <div class="lesson-icon">
              <img src="https://prog-8.com/images/html/advanced/php.png">
              <p>名前</p>
            </div>
            <p class="txt-contents">店の説明４</p>
          </div>
        </div>
      </div>
    </div>
    <div class="message-wrapper">
      <div class="container">
        <div class="heading">
          <h2>このページでは皆さんからの情報提供をお願いしています。</h2>
          <h3>素敵なお店やサービス等あれば是非Facebook、Twitterでご連絡ください。</h3>
        </div>
        <span class="btn message">Facebook、Twitterに戻る</span>
      </div>
    </div>
    <footer>
      <div class="container">
        <img src="サイトロゴ">
        <p>お問い合わせはFacebook、Twitterから</p>
      </div>
    </footer>
  </body>
</html>

body {
  margin: 0;
  font-family: "Hiragino Kaku Gothic ProN";
}

a {
  text-decoration: none;
}

.container {
  width: 1170px;
  padding: 0 15px;
  margin: 0 auto;
}

.top-wrapper {
  padding: 180px 0 100px 0;
  background-image: url(http://sonouchi.jp/tph-maebara/wp-content/uploads/sites/163/2019/04/DSC00667.jpg);
  background-size: cover;
  color: white;
  text-align: center;
}

.top-wrapper h1 {
  opacity: 0.7;
  font-size: 45px;
  letter-spacing: 5px;
}

.top-wrapper p {
  opacity: 0.7;
}

.btn-wrapper {
  margin: 20px 0;
}

.btn-wrapper p {
  margin: 10px 0;
}

.signup {
  background-color: #239b76;
}

.facebook {
  background-color: #3b5998;
  margin-right: 10px;
}

.twitter {
  background-color: #55acee;
}

.btn {
  padding: 8px 24px;
  color: white;
  display: inline-block;
  opacity: 0.8;
  border-radius: 4px;
}

.btn:hover {
  opacity: 1;
}

.fa {
  margin-right: 5px;
}

header {
  height: 65px;
  width: 100%;
  background-color: rgba(34, 49, 52, 0.9);


}

.logo {
  width: 124px;
  margin-top: 20px;
}

.header-left {
  float: left;
}

.header-right {
  float: right;
  background-color: rgba(255, 255, 255, 0.3);
  transition: all 0.5s;
}

.header-right:hover {
  background-color: rgba(255, 255, 255, 0.5);
}

.header-right a {
  line-height: 65px;
  padding: 0 25px;
  color: white;
  display: block;
}

.lesson-wrapper {
  height: 500px;
  padding-bottom: 80px;
  background-color: #f7f7f7;
  text-align: center;
}

.heading {
  padding-top: 60px;
  padding-bottom: 30px;
  color: #5f5d60;
}

.heading h2 {
  font-weight: normal;
}

.lesson {
  float: left;
  width: 25%;
}

.lesson-icon {
  position: relative;
}

.lesson-icon p {
  position: absolute;
  top: 90px;
  width: 100%;
  color: white;
}

.txt-contents {
  width: 80%;
  display: inline-block;
  margin-top: 20px;
  font-size: 12px;
  color: #b3aeb5;
}

.heading h3 {
  font-weight: normal;
}

.message-wrapper {
  border-bottom: 1px solid #eee;
  padding-bottom: 80px;
  text-align: center;
}

.message {
  padding: 15px 40px;
  background-color: #5dca88;
  cursor: pointer;
  box-shadow: 0 7px #1a7940;
}

.message:active {
  position: relative;
  top: 7px;
  box-shadow: none;
}

footer img {
  width: 125px;
}

footer p {
  color: #b3aeb5;
  font-size: 12px;
}

footer {
  padding-top: 30px;
}
