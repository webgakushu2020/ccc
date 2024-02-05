# **2日目**

## **いろいろなタグを書こう**
<br>

webサイトのパーツには「見出し」や「メインビジュアル」のように役割がありました  
HTMLにも役割に合わせたタグが

<br><br>

### **見出しをつけよう**  
追加されているコードを探して、書いてみよう  

```html
<!doctype html>
<body>
    <div class="header">
        <h1>[自分のなまえ]の自己紹介</h1>
    </div>
    <div class="profile">
        <h2>My Profile</h2>
        <div class="box1">
            <div class="section1">
                <h3>生年月日</h3>
                <p>[自分の生年月日]</p>
            </div>
            <div class="section2">
                <h3>出身</h3>
                <p>[自分の住んでいるところ]</p>
            </div>
            <div class="section3">
                <h3>好きなこと</h3>
            </div>
        </div>
    </div>
    <div class="favorite">
        <h2>My Favorite</h2>
        <div class="box2">
            
        </div>
    </div>        
</body>
```

<br>

### **VSCode（Visual Studio Code）**  

https://code.visualstudio.com/download

<br><br>

### **VSCodeの使い方**  

HTMLを書いてみよう

<br>

```html
<!doctype html>
<html>
    <head>
        <meta charset="UTF-8">
        <title>自己紹介</title>
    </head>
    <body>
        <h1>[自分のなまえ]の自己紹介</h1>
    </body>
</html>
```

<br><br>

### **webサイトの構成を考えよう** 

Webサイトの情報を整理してみよう

![info](img/01_info1-1.png)

<br>

- 見出し
- メインビジュアル
- 文章
- リスト
- 画像
- リンク

<br><br>

### **グループを考えよう** 

![info](img/01_info1-2.png)


```html
<!doctype html>
<html>
    <head>
        <meta charset="UTF-8">
        <title>自己紹介</title>
    </head>
    <body>
        <div class="header">
            
        </div>
        <div class="profile">
            <div class="box1">
                <div class="section1">
    
                </div>
                <div class="section2">
                    
                </div>
                <div class="section3">
                    
                </div>
            </div>
        </div>
        <div class="favorite">
            <div class="box2">
                
            </div>
        </div>        
    </body>
</html>
```