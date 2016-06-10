1. Copy the folder and myemail_helper.php to the helper folder 
2. confige 
....................................................
	$mail->Username = "Your gmail account";                 
	$mail->Password = "Your gmail password account"
	$mail->From = "Your gmail account";
	$mail->FromName = "Sender name"
.....................................................
3. Load helper "myemail"
4. use function  myEmail(someone_address,someone_name,email_title,email_content)
5. myEmail() function return true if it works and return false if it not work