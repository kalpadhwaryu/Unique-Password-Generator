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
For joining strings in Python join() method is used which is available in string library. It can join any two strings.
Python random module‘s random.choice() function returns a random element from the non-empty sequence. We can use the random.choice() function for selecting a random string.
In Python3, ascii_letters is a pre-initialized string used as string constant.ascii_letters is basically concatenation of ascii_lowercase and ascii_uppercase string constants. Also, the value generated is not locale-dependent, hence, doesn’t change.
To print both uppercase and lowercase letters, string.ascii_letters is used.
Similarly for printing digits, string.digits is used and for printing special characters, string.punctuation is used. This all is available in the string library.
Now according to the conditions, if..elif…else statements are executed.
If the user enters “1” as input then pw variable will be made by joining the randomly chosen letter from string.ascii_letters using random.choice() every time till the password length (inputted above) is reached in range of for loop and then the while loop breaks.
If the user enters “2” as input then pw variable will be made by joining the randomly chosen digit from string.digits using random.choice() everytime till the password length (inputted above) is reached in range of for loop and then the while loop breaks.
If the user enters “3” as input then pw variable will be made by joining the randomly chosen concatenation of letters and digits from string.ascii_letters & string.digits using random.choice() everytime till the password length (inputted above) is reached in range of for loop and then the while loop breaks.
If the user enters “4” as input then pw variable will be made by joining the randomly chosen concatenation from string.ascii_letters, string.digits & string.punctuation using random.choice() everytime till the password length (inputted above) is reached in range of for loop and then the while loop breaks.
