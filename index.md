
<head>
	<meta charset="utf-8">
	<title>图片提示效果</title>
	<script src="../jquery-3.3.1.min.js"></script>
    <style type="text/css">
        #menu { 
            font:12px verdana, arial, sans-serif; /* 设置文字大小和字体样式 */
            width: 100%;
        }
        #menu, #menu li {
            list-style:none; /* 将默认的列表符号去掉 */
            padding:0; /* 将默认的内边距去掉 */
            margin:0; /* 将默认的外边距去掉 */
            float: left; /* 往左浮动 */
            display: block;
        }
        #menu li a {
            display:inline-block; /* 将链接设为块级元素 */
            width:150px; /* 设置宽度 */
            height:30px; /* 设置高度 */
            line-height:30px; /* 设置行高，将行高和高度设置同一个值，可以让单行文本垂直居中 */
            text-align:center; /* 居中对齐文字 */
            background:#3A4953; /* 设置背景色 */
            color:#fff; /* 设置文字颜色 */
            text-decoration:none; /* 去掉下划线 */
            border-right:1px solid #000; /* 在左侧加上分隔线 */
        }
        #menu li a:hover {
            background:#146C9C; /* 变换背景色 */
            color:#fff; /* 变换文字颜色 */
        }
        #menu li a.last {
            border-right:0; /* 去掉左侧边框 */
        }
</style>
 
</head>
<body>
    <ul id="menu">
        <li><a href="http://www.baidu.com">Research</a></li>
         <li><a href="http://www.Code52.Net">Bio</a></li>
         <li><a href="http://www.yahoo.com">People</a></li>
         <li><a href="http://www.google.com" class="last">Pulication</a></li>
    </ul>
</body>
----------
<div>
<table border="0">
  <tr>
    <td width="75%">
      <h1>邢斌</h1>
      <p><b>本科生</b></p>
      <p><b>武汉大学动力与机械学院</b></p>
      <p><b>邮箱：XXX</b></p>
      <p><b>地址：××市××区××路××号××大学，××楼，邮编×××</b></p>
    </td>
    <td width="75%">
      <img src="/PersonPhoto.jpg" width="100%">
    </td>
  </tr>
</table>
</div>

### 个人信息
#### 姓名：邢斌
#### 学历：本科
#### 学校：武汉大学
#### 邮箱：

### 最新消息

### 研究方向

### 荣誉奖励
#### 奖学金：
#### 荣誉称号
#### 比赛获奖

### 项目研究
#### 项目一：
#### 项目二：
### 座右铭：如同看着一丝不挂的宇宙
