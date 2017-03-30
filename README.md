# Project
Project Description
Here at Aperture Science Labs (ASL), we aim to use science (in this case computer science) in order to make life easier for all humankind.
For example: A normal human can easily remember at least one single password, but remembering hundreds for every little thing? Simply using the same password is not very secure from those humans or robots with nefarious intent.
Our latest project is to create a secure yet password free web-based "one stop shop" password storage website, accessible from anywhere in the world any from any device.
Our team is developing a process called EasyPass. Using customisable and editable questions and answers, EasyPass will encrypt your password list so you will never again have to worry about O's and 0's, 1's and l's or which special character went where. You will never need to worry about being hacked either. Trust us on that one!
As all these questions are provided by you, as such only you know the correct answer. With the exception of mind readers, (ASL does not speculate in science fiction) you will never be hacked by anyone else again.
Just another way that the team at Aperture Science Labs is using science to make life easier for you.

Demonstrable Outcomes
Minimum Viable Product
The application will provide an interface to the user to allow their passwords to be stored online.

Validation Test : Test case 1 will confirm that this outcome will be met through an exercise of the interface functions. Additionally, this will be demonstrated as part of the final presentation.


The security for this will be provided by the user setting three questions and the answers.

Validation Test : Test case 2 will confirm that this outcome will be met by ensuring the user can set three questions and then provide their answers. Additionally, this will be demonstrated as part of the final presentation.

The questions will be stored on the website encrypted and the user’s email address will be hashed and used as the password (a weak security feature).

Validation Test : Test case 3 will confirm that this outcome will be met through inspection of the text file containing the user's questions.

The password file will also be encrypted and the answers to the questions will be aggregated, hashed and this will be used to unlock the password file (a strong security feature).

Validation Test : Test case  will confirm that this outcome will be met through inspection of the text file containing the user's questions.

The application will use a clean, easy to navigate interface with minimal clutter and helpful prompts to the user. The application interface style will be constructed using CSS3.

Validation Test : The CSS file will be run through the W3C CSS validator.
Extended Features
A basic two factor authentication will be used where a second credential (like a random number) will be sent to the user mobile phone via SMS. This number will be used to encrypt the super-password a second time for transmission. At the far end the hashed password will be decrypted by the random number and then can unlock the password file. This is to further mitigate against potential phishing attacks (like from https://EasyPass.dodgy.ru) against unsophisticated users.

Validation Test : If implemented, the two-factor authentication will be demonstrated during the application presentation video.


The application will implement a basic anti-brute force protection by setting a limit on the number of authentication attempts.

Validation Test : A test harness will be created to trigger the anti-brute force protection and the results recorded.


The application will make use of modern anti-robot techniques like Captchas etc.


Validation Test : Demonstration of the Captcha technology during the assignment presentation.
