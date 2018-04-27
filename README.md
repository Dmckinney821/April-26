# April-26
loop review, lists, strings, more overthewire, mind bending/melting
count = 0
while count < 10:
    count = count + 1
    print(count)


break

start = int(input('start from:'))
end = int(input('end on:'))

count = start
while count <= end:
    print(count)
    count = count + 1

break

count = 0 
while count < 10
    if count % 2 !=0:
        print(count)
    count = count + 1

break


coins = 0
print("you have %d coins" % coins)

another = 'yes'
while another == 'yes':
   print('you have %d coins', % coins)
    another = input('Do you want another?')
    another = another.lower()
    coins = coins + 1
print('Bye')

    pass

break



size = 5
count_y = 0
while count_y < size:
    
    row = ''
    count_x = 0
    while count_x < size:
        #print('*', end='')
        row = row + '*'
        count_x = count_x + 1
    
    count_y = count_y + 1
    print(row)

size = 5

square = ''
count_y = 0
while count_y < size:
    
    row = ''
    count_x = 0
    while count_x < size:
        #print('*', end='')
        row = row + '*'
        count_x = count_x + 1
    
    count_y = count_y + 1
    #print(row)
    square = square + row + '\n'
print(square)

break

size = int(input('how big' ))
BRICK = '* '

count_y = 0
while count_y < size:
    
    
    count_x = 0
    while count_x < size:
        print(BRICK, end='')
        count_x = count_x + 1
    
    count_y = count_y + 1
    print()


break


var = str(input())
list = ['a', 'i', 'e', 'o', 'u']

for letter in var:
    if letter in list:
        print(var.replace(letter, letter*5))
        break
    x = 'lbh zhfg hayrnea jung lbh unir yrnearq'

alphabet = 'abcdefghijklmnopqrstuvwxyz'

for letter in x:
    if letter == ' ':
        print(' ')
        
    else:
        index_of_translation = (alphabet.index(letter) - 13) 
        if index_of_translation < 0:
            
            index_of_translation = index_of_translation + 26
            
        
        
    
        print(alphabet[index_of_translation])
    


