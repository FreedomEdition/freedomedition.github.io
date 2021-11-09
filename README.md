# freedomedition.github.io
host testing description

<html>
<head>
<title>css styling</title>
<style>
	
	 p{font-family: sans-serif, arial; font-size:16pt}
	.p{font-family: sans-serif, arial; font-size:16pt}
	.editText{height:30; font-size:18pt; width:200; border: 5px solid red; padding:20px; text-align:center}
	.btn{padding: 16px 60px; background-color: gray; border:none; font-size: 16pt; color:#ffff}
	.dropdown{background-color: green; font-size:16pt; color:white; padding:16px 50px;  border-radius: 20px}
	
</style>
</head>


<body>
	
	<div>
		<p style= "color:blue">This first "input" tag is being used as an editText</p>
		<input class="editText"	maxlength="5" type="text"/>
	</div>
	
	
	<div>
		<p style="color:blue"> This "input" tag is being used to input number and increment and decrementation
		feature is already integrated</p>
		<input class="editText"	maxlength="5" type="number"/>
	</div>
	
	
	<div>
		<p style="color:blue"> The "input" tag is now being transformed into a button</p>
		<input class="btn" type="button" name="id_btn1" value="Click here" />
	</div>
	
	<div style="margin-top:50px">
		
		<p style="color:blue">This widget is a dropdown menu and it uses 2 tags</p>
		<ul class="p" style="color:blue">
			<li>select</li>
			<li>option</li>
		</ul> 
		<p style="color:blue">The "select" tag is used to create the features of a dropdown menu and the "option" tag is used for the inside element that are being selected.</p>
		
		<select class="dropdown">
			<option>Annas</option>
			<option> Ajmal</option>
			<option>Taslima</option>
		</select>
	</div>
	

</body>
</html>