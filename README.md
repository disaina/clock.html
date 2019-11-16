<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>表单</title>
</head>
<body>
<h3>表单</h3>
<hr/>
<!--
<button id="btn" onclick="alert('nihao')">
		开始记录
</button>
-->

<!--
<form action="14.html" method="get" name="你好">
姓名：<input type="text" name="username"/><br/>
密码：<input type="password" name="pwd"/><br/>
<input type="submit" value="提交"/>
</form>
-->

<fieldset>
	<legend>注册新用户</legend>
	<form  method="get" action="2.html" name="form1">
		<table align="center" border="1" cellpadding="2">
		<tr align="center">
			<td>姓名</td>
			<td><input type="text" name="name"/></td>
		</tr>
		<tr align="center">
			<td>密码</td>
			<td><input type="password" name="psw"/></td>
		</tr>
		<tr align="center">
			<td>性别</td>
			<td>
			<input type="radio" name="sex" value="male"/>男
			<input type="radio" name="sex" value="female"/>女
			</td>
		</tr>
		<tr align="center">
			<td>爱好</td>
			<td>
			<input type="checkbox" name="film" value="hobby"/>看电影
			<input type="checkbox" name="basketball" value="hobby"/>打篮球
			<input type="checkbox" name="code" value="hobby"/>敲代码
			</td>
		</tr>
		<tr align="center">
			<td>头像</td>
			<td><input type="file" name="photo"/></td>
		</tr>
		<tr>
		<td colspan="2">
		评论:<br/>
		<textarea rows="5" cols="50" name="comment">注意文明用语！</textarea>
		</td>
		</tr>
		<tr align="center">
			<td colspan="2">
			<input type="reset" value="重填"/>
			<input type="submit" value="注册"/>
			</td>
		</tr>
		</table>
	</form>
</fieldset>
<script>
/*
function aler(){
	var i=0,j;
	//j="Hello JavaScript!";
	for(;i<3;i++){
	alert(j); 
	}
	}
	*/
</script>	
</html>
