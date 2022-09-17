<table border="1">
  <tbody>
    <tr>
      <th colspan="2">信 息 统 计 表</th>
    </tr>
 <tr>
      <td><label for=username>姓名:</label></td>
      <td><input name=username id=username type=text requierd /><br></td>
    </tr>
    <tr>
      <td><label for=age>年龄:</label></td>
      <td><input name=age id=age type=number min=0 max=100/><br/></td>
    </tr>
    <tr>
      <td><label for=sex>性别:</label></td>
      <td><input name=sex id=sex typer=raido <input type="radio" name="sex" value="1">男  &nbsp; &nbsp;
		<input type="radio" name="sex" value="0">女</td>
    </tr>
    <tr>
      <td><label for=hobby>爱好:</label></td>
      <td><input type="checkbox" name="hobby" value="1">旅游<br/>
	  <input type="checkbox" name="hobby" value="2">登山<br/>
	  <input type="checkbox" name="hobby" value="3">健身<br/>
	  <input type="checkbox" name="hobby" value="4">上网<br/>
	  <input type="checkbox" name="hobby" value="5">游泳<br/></td>
    </tr>
    <tr>
      <td><label for=education>学历:</label></td>
      <td><select name="degree">    <option value="">--请选择--</option>   
	   <option value="1">专科</option> 
		  <option value="2">本科</option>  
			<option value="3">硕士</option>  
			  <option value="4">博士及以上</option>
			  </select></td>
    </tr>
    <tr>
      <td><label for=Introduce>自我介绍</label></td>
      <td><textarea name="comment" rows="5" cols="40"></textarea>
    </tr>
	<tr>
		<td><label for=option>  </label></td>
		<td><input type="submit" value="提交">
		<input type="reset" value="重置">
		<input type="button" value="返回"></td>
	</tr>
  </tbody>
  <colgroup>
    <col>
    <col>
  </colgroup>
</table>

