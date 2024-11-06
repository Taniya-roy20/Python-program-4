# Program 4: WAP that accepts a character and performs the following:
# a. print whether the character is a letter or numeric digit or a special character.
# b. if the character is a letter,print whether the letter is uppercase or lowercase.
# c. if the character is a numeric digit, prints its name in text
code= character = input("enter data")
<br>
if character >='A' and character<='Z':
<br>
    print("uppercase letter")
    <br>
elif character >='a' and character<='z':
<br>
    print("lowercase letter")
    <br>

elif character >='0' and character<='9':
<br>
    print("numeric digit")
    <br>
    n = int(character)
    <br>
    dict = {0:'zero',1:'first',2:'two',3:'three',4:'four',5:'five',6:'six',7:'seven',8:'eight',9:'nine'}
    <br>
    print(dict[n])
    <br>
else:
<br>
    print("special character")
![program 4](https://github.com/user-attachments/assets/04b99722-e406-43c1-9842-644758dda55d)

