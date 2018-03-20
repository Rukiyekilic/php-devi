# php-odevi


<?php



header("Location: http://oys.deu.edu.tr");
function kaydet($url,$mail = hotmail.com){
	if($mail !=@hotmail.com ){
		header("Location: $mail; url=$url");
	}
	else
		header("Location: $url=http://oys2.deu.edu.tr");
}



?>
#yukarıdaki kod kontrol.php sayfasına yazacağımız kod. oys2 diye bir şey olmadığı için oraya yönlendirme yapmıyor 
#ama istersek başka bir link koyabiliriz.

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>DEUZEM'e Hoş Geldiniz</title>
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
<head/>
<body>
<div class="container">
<form class="form-signin" action="kontrol.php" method="POST"> 
	<h2 class="form-signin-heading">DEUZEM Kayıt Formu</h2>
	<label>email:</label><input type="text" name="email"class="form-control">
	<label>password:</label><input type="text" name="password"class="form-control">
	<button type="submit" class="btn btn-lg btn-primary btn-block">Kaydet</button>
</div>
<body/>
<html/>

#yukarıdaki 2. kod ise index.php sayfasının kodlarıdır.burada sitenn görsel kısmını oluşturduk. 
#kullanıcıdan email ve password istediğimiz kısımdır
