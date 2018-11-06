# DOM
## 什么是DOM
> 文档对象模型（Document Object Model）
## DOM HTML
> HTML DOM 允许 JavaScript 改变 HTML 元素的内容
```
<p id="p1">Hello World!</p>

<script>
document.getElementById("p1").innerHTML="New text!";
</script>
```
> 绝不要使用在文档加载之后使用 document.write()。这会覆盖该文档
## DOM CSS
> JavaScript HTML DOM - 改变 CSS
```
<p id="p2">Hello World!</p>

<script>
document.getElementById("p2").style.color="blue";
</script>
```
## DOM 事件
> HTML DOM 使 JavaScript 有能力对 HTML 事件做出反应
```
<script>
function changetext(id)
{
id.innerHTML="谢谢!";
}
</script>
</head>
<body>
<h1 onclick="changetext(this)">请点击该文本</h1>
</body>
```
## DOM 节点
> 添加和删除节点（HTML 元素）
```
<div id="div1">
<p id="p1">这是一个段落</p>
<p id="p2">这是另一个段落</p>
</div>

<script>
var para=document.createElement("p");
var node=document.createTextNode("这是新段落。");
para.appendChild(node);

var element=document.getElementById("div1");
element.appendChild(para);
</script>
```