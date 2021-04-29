# ChromePasswordSaver
Problem with Google password manager is that it only saves passwords on pages with login input fields (and not all of them even work).
But what if you want to save password that does not have a web page?

This project creates a web server with login page on your local machine that you can use to store any password. 

You will need docker installed on your machine.

Run `docker-compose up`.
It will build and run image with page where you can save your passwords on address http://localhost:7000.

## Problems
Page that will be associated with your password is `http://localhost:7000` which tells you nothing about what is your password for.
You will need to remember it or prepend your username with text that will help you remember it.