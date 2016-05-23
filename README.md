<!DOCTYPE html>
<html lang="ru">
<head>
	<meta charset="UTF-8">
	<title>Aplle-Market</title>
	<link rel="stylesheet" href="style.css">
</head>
<body>
	<div class="menu">
		<ul>
			<li>Iphone</li>
			<li>Ipad</li>
			<li>О Компании</li>
		</ul>
	</div>
	<div class="header">
		<div class="logo">
		<p>Iphone and Ipad</p><br>
			<span>I-Market</span>
		</div>
		
	</div>
	
	<div class="content">
		<div class="registration">
			<form method="get">
				<label>Имя</label>&nbsp;&nbsp;
				<input type="text" name="log" required>
				<br>
				<label>Введите Пароль</label>
				<input type="password" name="pas" required>
				<br>
				<label>Введите номер телефона</label>
				<input type="tel" name="tel" pattern="[0-9]{4,12}" required>
				<input type="submit" name="btn" value="Зарегистрироваться">
			</form>
			<?
				if(isset($_GET['btn']))
				{
			?>
				<p><? echo $_GET['log']?>, вы успешно зарегистрировались!</p>
			<?
				}
			?>
		</div>
	</div>
	<div class="footer">
		
		<span class="contacts">г. Пермь, ул. Дедюкаина, 19 <br> 
				Торговая точка "у Алмаза" <br>
				тел.: (342)277-10-67 <br>
				моб.: 8-9O2-83-31-O67 <br>
				e-mail: almaz-s@yаndеx.ru <br> </span>
	</div>
</body>
</html>
