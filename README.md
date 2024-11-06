# PY-Practical-4
character = input("Enter a character: ")

# Check if the character is a letter
if character.isalpha():
    if character.isupper():
        print("The character is an uppercase letter.")
    else:
        print("The character is a lowercase letter.")
# Check if the character is a numeric digit
elif character.isdigit():
    print("The character is a numeric digit.")
    digit_to_text = {
        0: 'zero', 1: 'one', 2: 'two', 3: 'three', 4: 'four', 
        5: 'five', 6: 'six', 7: 'seven', 8: 'eight', 9: 'nine'
    }
    n = int(character)
    print("The numeric digit is:", digit_to_text[n])
# If the character is neither a letter nor a digit, it is a special character
else:
    print("The character is a special character.")




'''output
Enter a character: 6
The character is a numeric digit.
The numeric digit is: six

Enter a character: A
The character is an uppercase letter.

Enter a character: g
The character is a lowercase letter.

Enter a character: @
The character is a special character.
'''
