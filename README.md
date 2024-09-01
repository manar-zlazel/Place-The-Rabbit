# Place-The-Rabbit
print('Welcome to place the rabbit: ')

field = [['🌿', '🌿', '🌿'] , ['🌿', '🌿', '🌿'] , [ '🌿', '🌿', '🌿']]
print(f'{field[0]} \n{field[1]} \n{field[2]}')
print('\nWhere should the rabbit go? 🐇 ')

position = input('Please choose a row and a column: ')
row = int(position[0])
colomn = int(position[1])

field[row-1][colomn-1] = '🐇'
print('\nSuccess....\n')
print(f'{field[0]} \n{field[1]} \n{field[2]}')
