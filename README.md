# Unique-Password-Generator
Unique Password Generator is a Python program which generates a unique password evverytime it runs.
The user is asked for the type of password he/she wants like a password with only digits, only alphabets or both or both with special chracters.
At first it will ask the user to enter desired password length.
The while loop will be repeated till the user enters a number.
If the user has entered a number then the while loop will be broken and it will come out of the loop.
If the user enters something else than number(integer) like string or character, it will be identified as an exception as ‘ValueError’.
If the user entered input is not number(integer), it will print the except statement i.e. “Please enter a number”
Now the second part of code also contains a while loop and try, except statements.
Inside the while loop is the try statements.
The try statement consists of an input variable ‘yourchoice’ and if ..elif..else conditions.
First the user is asked the type of password they want. For every choice there is a number assigned. For text only password - 1, for digits only password - 2, for alphanumeric password – 3 and password for alphanumeric with special characters - 4.
