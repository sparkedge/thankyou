<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Thank You</title>
</head>
<style>

	body{
		background: #d7aded;
	}

	.popup{
		width:400px;
		background: #fff;
		border-radius: 30px;
		position: absolute;
		top: 50%;
		left: 50%;
		transform: translate(-50%,-50%);
		text-align: center;
		padding: 0 30px 30px;
		color:#333;
	}

	.popup img{
		width: 100px;
		position: absolute;
		
		transform: translate(-50%,-80%);
		border-radius: 50%;
		box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
	}

	.popup h2{
		font-size: 38px;
		font-family: arial;
		font-weight: 500px;
		margin: 40px 0 10px;
		color: indigo;
	}

	.popup p{
		font-size: 25px;
		font-family: arial;
		font-weight: bold;
	}

	.popup button{
		width: 100%;
		height: 50px;
		margin-top: 20px;
		padding: 10px 0;
		background: indigo;
		color: #fff;
		border: 0;
		outline: none;
		font-size: 18px;
		font-weight: bolder;
		border-radius: 100px;
		cursor: pointer;
		box-shadow: 0 5px 5px rgba(0, 0, 0, 0.2);
	}

</style>
<body>
<div class="popup">
	<img src="images/tick.jpg">
	<h2>Thank You!</h2>
	<p>Your details has been successfully submitted. Thanks!</p>
	<button type="button" onclick="window.location.href='index.html'" >OK</button>
</div>
</body>
</html>
