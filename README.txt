*** Config library ***
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

*** setting up your email account ***
1. Enable POP and IMAP 
  > Go to setting -> Forwarding and POP/IMAP ->choose Enable
2. Enable less security 
  > Go to my account -> Signin & Security -> Scroll to the bottom ->Allow less secure apps: ON

Note: Should create an test account, don't use your personal email becuase it will affect to securty 
