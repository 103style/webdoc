### 结构
```
<!DOCTYEP HTML>
<html>
 <head>
  <title></title>
 </head>
 
 <body>
 </body>
</html>
```

---

### 标题
一共 h1 - h6 六种
```
<h1>一级标题</h1>
<h2>二级标题</h2>
<h3>三级标题</h3>
<h4>四级标题</h4>
<h5>五级标题</h5>
<h6>六级标题</h6>
```
---

### 分块
利用 `div` 标签分块
```
<div>
  <h2>热门课程排行榜</h2>
</div>
<div>
  <h2>最新课程排行</h2>
</div>
```

---

### 头部 底部 正文 侧边
```
  <body>
    <header>头部</header>
    <aside>侧边</aside>
    <section>正文区段</section>
    <footer>底部</footer>
  </body>
```

---

### 换行 空格  分割线
`<br />` 换行

`&nbsp;` 代表空格

`<hr />` 代表分割线

---

### 列表
```
<!-- 无序列表 -->
<ul>
  <li>item</li>
  <li>item</li>
  <li>item</li>
</ul>

<!-- 有序列表 -->
<ol>
  <li>item</li>
  <li>item</li>
  <li>item</li>
</ol>
```

---

### 图片 链接 
```
<!-- 图片 -->
<img src="https://www.xxx.png" alt="图片加载失败的提示" title="鼠标移动到图片上的提示文字"/>

<!-- 链接 -->
<!-- target 默认为 `_self`是直接在当前窗口打开链接    '_blank'则是新开一个窗口 -->
<a href="https://www.baidu.com" title="鼠标移动到链接上的提示文字" target="_self">链接文字： www.baidu.com   </a>

<a href="https://www.baidu.com" title="鼠标移动到链接上的提示文字" target="_blank">链接文字： www.baidu.com   </a>

```


---

### table
```
// 1、<table>…</table>：整个表格以<table>标记开始、</table>标记结束。
// 2、<tr>…</tr>：表格的一行，所以有几对tr 表格就有几行。
// 3、<td>…</td>：表格的一个单元格，一行中包含几对<td>...</td>，说明一行中就有几列。
// 4、<th>…</th>：表格的头部的一个单元格，表格表头。
// 5、表格中列的个数，取决于一行中数据单元格的个数。
// 6、border属性可以为表格添加边框，属性值为数字。

// 7、<thead> 标签定义表格的表头。该标签用于组合 HTML 表格的表头内容。
// 8、<tbody>…</tbody>：如果不加<thead><tbody><tfooter> , table表格加载完后才显示。
//    加上这些表格结构， tbody包含行的内容下载完优先显示，不必等待表格结束后在显示，同时如果表格很长，用tbody分段，可以一部分一部分地显示。
//    （通俗理解table 可以按结构一块块的显示，不在等整个表格加载完后显示。）
// 9、<tfoot> 元素用于对 HTML 表格中的表注（页脚）内容进行分组。

<table>
  <caption>表格标题</caption>
  <thead>
    <tr>
      <th>科目</th>
      <th>分数</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>语文</td>
      <td>90</td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td>数学</td>
      <td>80</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td>总分</td>
      <td>170</td>
    </tr>   
  </tfoot>
</table>
```

---


### 表单
```
```


---
