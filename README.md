# CIS567-integrated-lab-2
8.7 LAB: Count characters
input_string = input()

char, phrase = input_string.split(maxsplit=1)

count = phrase.count(char)

if count == 1:
    print(f'{count} {char}')
else:
    print(f'{count} {char}\'s')
