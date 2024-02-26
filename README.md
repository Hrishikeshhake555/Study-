<!DOCTYPE html>
<html>
<head>
	<title>RSA Algorithm</title>
</head>
<body>
	<h1>RSA Algorithm</h1>
	<label for="publicKey">Public Key:</label>
	<input type="text" id="publicKey" readonly><br><br>
	<label for="privateKey">Private Key:</label>
	<input type="text" id="privateKey" readonly><br><br>
	<label for="message">Message:</label>
	<input type="text" id="message" value="Hello, World!"><br><br>
	<button onclick="encryptMessage()">Encrypt</button>
	<button onclick="decryptMessage()">Decrypt</button><br><br>
	<label for="encryptedMessage">Encrypted Message:</label>
	<input type="text" id="encryptedMessage" readonly><br><br>
	
