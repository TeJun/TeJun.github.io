TeJun.github. o
==============

大標題
===================================
  大標題一般顯示工程名,類似html的\<h1\><br />
  你只要在標題下面跟上=====即可

中標題
-----------------------------------
  中標題一般顯示重點項,類似html的\<h2\><br />
  你只要在標題下面輸入------即可

### 小標題
  小標題類似html的\<h3\><br />
  小標題的格式如下 ### 小標題<br />
  注意#和標題字符中間要有空格

### 注意!!!下面所有語法的提示我都先用小標題提醒了!!!

### 單行文本框
    這是一個單行的文本框,只要兩個Tab再輸入文字即可

### 多行文本框
    這是一個有多行的文本框
    你可以寫入代碼等,每行文字只要輸入兩個Tab再輸入文字即可
    這裡你可以輸入一段代碼

### 比如我們可以在多行文本框裡輸入一段代碼,來一個Java版本的HelloWorld吧
	public class HelloWorld {

    /**
      * @param args
      */
    	public static void main(String[] args) {
        	System.out.println("HelloWorld!");
    	}
	}

### 鏈接
1.[點擊這裡你可以鏈接到www.google.com](http://www.google.com)<br />
2.[點擊這裡我你可以鏈接到我的博客](http://guoyunsky.iteye.com)<br />

###只是顯示圖片
![github](http://github.com/unicorn.png "github")

###想點擊某個圖片進入一個網頁,比如我想點擊github的icorn然後再進入www.github.com
[![image]](http://www.github.com/)
[image]: http://github.com/github.png "github"

### 文字被些字符包圍
> 文字被些字符包圍
>
> 只要再文字前面加上>空格即可
>
> 如果你要換行的話,新起一行,輸入>空格即可,後面不接文字
> 但> 只能放在行首才有效

### 文字被些字符包圍,多重包圍
> 文字被些字符包圍開始
>
> > 只要再文字前面加上>空格即可
>
>  > > 如果你要換行的話,新起一行,輸入>空格即可,後面不接文字
>
> > > > 但> 只能放在行首才有效

### 特殊字符處理
有一些特殊字符如<,#等,只要在特殊字符前面加上轉義字符\即可<br />
你想換行的話其實可以直接用html標籤\<br /\>
