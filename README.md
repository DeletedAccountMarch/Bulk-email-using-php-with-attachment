# Bulk-email-using-php-with-attachment
A simple php script that will help you to send bulk email with being able to attach file.

To run this script, You need to follow these steps -

1) At first install xampp server on your windows.

2) After installation is completed you have to open your sendmail folder which can be in this location = “C:\xampp\sendmail\ “ here edit the file sendmail.ini with your details like smtp link, your email your password and smtp port. the smpt link of google is [smtp.google.com](http://smtp.google.com) and port no. is 587

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b0b36f28-a80e-4f2e-90ce-774d7b4a0aab/Untitled.png)

3) Now go to php folder inside “C:\xampp\php\php.ini” now here in this folder edit the php.ini folder with these values = 

at first search for smtp, on the search result comment

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/fbaaf905-8d25-4b34-91d9-30048f389cb3/Untitled.png)

now uncomment the openssl setting

Once its done, upload index.php file on your root folder and it will start sending email to the array list.
