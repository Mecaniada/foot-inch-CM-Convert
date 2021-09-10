#Write a Python program to
#convert height (in feet and inches) to centimeters.

req = input('What do you want to convert into centimeters? [INCH/FEET]\n')
def INCH(n):
    if n > 0:
        conv = n * 2.54
        return conv
    else:
        return False

def FEET(n):
    if n > 0:
        conv1 = n * 30.48
        return conv1
    else:
        return False

if req == 'INCH':
    try:
        n = int(input('Enter the value you want to convert: '))
        print(INCH(n), 'cm')
    except:
        print('You have to enter a value and not a string!')

elif req == 'FEET':
    try:
        n = int(input('Enter the value you want to convert: '))
        print(FEET(n), 'cm')
    except:
        print('You have to enter a value and not a string!')
else:
    print("There's no other function! :(")
    quit()
