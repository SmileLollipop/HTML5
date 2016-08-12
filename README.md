# HTML5
HTML5学习记录


HTML5的目标是为了能够创建更简单的Web程序，书写出更简单的HTML代码。为了使Web应用程序的开发变得更容易，提供了许多API;为了使HTML变得更简洁，
开发出了新属性，新元素。不但如此，HTML5使页面结构也变得清楚明了，提供更加语义化的结构标签来代替div。HTML5要解决的三个问题：1.Web浏览器之间兼容性低的问题，2.文档结构不明了的问题，3.Web应用程序功能受限的问题。

HTML5与HTML4在基本语法上的区别（基本语法包括：DOCTYPE声明，内容类型，字符编码的指定方式，元素标记的省略，具有布尔值的属性，引号的省略等几个方面）  
1.内容类型（ContentType）仍为“text/html”  
2.DOCTYPE声明  
  <! DOCTYPE html>
  HTML5中不使用版本声明  
3.指定字符编码  
<meta charset="utf-8">,也可以使用之前的方式，但是不能同时混用。  
4.HTML5为了确保兼容性，从元素标记的省略，具有boolean值的属性，引号的省略来实现兼容

HTML5新增元素
新增结构元素：
section,article,aside,header,footer,nav,
figure(使用figcaption元素为figure元素组添加标题)相当于dl，dt，dd
```html
  <figure>
    <figcaption>PRC</figcaption>
    <p>The People's Republic of China was born in 1949...</p>
  </figure>
```


