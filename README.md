# ajax
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<meta http-equiv="X-UA-Compatible" content="ie=edge">
	<title>უკუკავშირი</title>
	<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
</head>
<body>
	<div class="container">
<h1>უკუკავშირი</h1>
<form id="mailForm">
	<input type="email" id="email" placeholder="Email" name="email" class="form-control"><br>
		<input type="text" id="name" placeholder="სახელი" name="name" class="form-control"><br>
		<input type="phone" id="phone" placeholder="ტელეფონი" id="subject" name="subject" class="form-control"><br>
		<textarea name="message" id="message" placeholder="შეიყვანეთ აქ თქვენი შეტყობინება" class="form-control"></textarea> <br>
		<button type="button" id="sendMail" class="btn btn-success">გაგზავნა</button>
	</div>
	<script src="C:\Users\STUDENT\Desktop\formMail.js"></script>
</form>
<div id="errorMess">
</body>
</html>
