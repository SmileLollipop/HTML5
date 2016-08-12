# HTML5
HTML5学习记录


HTML5的目标是为了能够创建更简单的Web程序，书写出更简单的HTML代码。为了使Web应用程序的开发变得更容易，提供了许多API;为了使HTML变得更简洁，
开发出了新属性，新元素。不但如此，HTML5使页面结构也变得清楚明了，提供更加语义化的结构标签来代替div。HTML5要解决的三个问题：1.Web浏览器之间兼容性低的问题，2.文档结构不明了的问题，3.Web应用程序功能受限的问题。

HTML5与HTML4在基本语法上的区别（基本语法包括：DOCTYPE声明，内容类型，字符编码的指定方式，元素标记的省略，具有布尔值的属性，引号的省略等几个方面）  
1.内容类型（ContentType）仍为“text/html”  
2.DOCTYPE声明  
  `<!DOCTYPE html>`  
  HTML5中不使用版本声明  
3.指定字符编码  
 `<meta charset="utf-8">`,也可以使用之前的方式，但是不能同时混用。  
4.HTML5为了确保兼容性，从元素标记的省略，具有boolean值的属性，引号的省略来实现兼容

HTML5新增元素
1.新增结构元素：
`section`,`article`,`aside`,`header`,`footer`,`nav`,`main`
`figure`(使用`figcaptio`n元素为`figure`元素组添加标题)相当于`dl`，`dt`，`dd`
```html
  <figure>
    <figcaption>PRC</figcaption>
    <p>The People's Republic of China was born in 1949...</p>
  </figure>
```

2.新增其他元素
`video` 定义视频,`audio`定义音频，`embed` 用来插入各种多媒体  
`mark`高亮显示文字  
`progress`表示运行中的进程，可以用来显示js中耗费时间的函数  
`meter`表示度量衡  
`time`,  
`ruby`,`rt`,`rp`  
`wbr` 表示软换行，`wbr`元素与`br`元素的区别是：`br`元素是此处必须换行，而`wbr`元素意思就是浏览器窗口或父级元素的宽度  
足够宽时（没必要换行时），不进行换行，而当宽度不够时，主动在此处进行换行。`wbr`元素对字符型语言用处比较大，但对中文貌似没多大用处  
`canvas`元素表示图形，比如图表和其他图像。这个元素本身没有行为，仅提供一块画布，但把一个绘图API展现给客户端JavaScript，以使脚本能够将想绘制的东西绘制到这块画布上。  
`command`元素表示命令按钮，比如单选按钮，复选框或按钮
·details` 与`summary`元素配合使用,`summary`提供标题或图例，用户点击标题，会显示细节信息
```html
<details>
  <summary>HTML5</summary>
  there is html5 document
</details>
```
`datalist` 表示可选数据的列表，与input元素配合使用。    
`datagrid`表示可选数据的列表，它以树形列表的形式显示。   
`keygen`表示生成密钥     
`output`表示不同类型的输出，比如脚本的输出    
`source`为媒介元素（`<video>`,`<audio>`...）定义媒介资源  
`menu`表示菜单列表。当希望列出表单控件时使用该标签  
`dialog`表示对话框  

3.新增的input元素的类型
`email`,`url`,`number`,`range`,`Date Pickers`






