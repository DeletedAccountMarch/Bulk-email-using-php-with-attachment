# Bulk-email-using-php-with-attachment
A simple php script that will help you to send bulk email with being able to attach file.

To run this script, You need to follow these steps -

1) At first install xampp server on your windows.

2) After installation is completed you have to open your sendmail folder which can be in this location = “C:\xampp\sendmail\ “ here edit the file sendmail.ini with your details like smtp link, your email your password and smtp port. the smpt link of google is [smtp.google.com](http://smtp.google.com) and port no. is 587
![image](https://user-images.githubusercontent.com/82378187/163569180-3c414a74-2d8e-4d44-9df0-af67b9dabada.png)

3) Now go to php folder inside “C:\xampp\php\php.ini” now here in this folder edit the php.ini folder with these values = 

at first search for smtp, on the search result comment
![image](https://user-images.githubusercontent.com/82378187/163569210-90441f35-9a32-4fdb-892f-59ed4930b917.png)

now uncomment the openssl extension from php.ini

![image](https://user-images.githubusercontent.com/82378187/163569228-ce27ac47-4385-4357-91bc-5f38b4cb2355.png)


Once its done, upload index.php file on your root folder and it will start sending email to the array list of emails.
![image](https://user-images.githubusercontent.com/82378187/163569338-9564300b-0b40-4837-83ec-ba7416d1a03b.png)

