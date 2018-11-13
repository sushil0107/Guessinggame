from random import randint
num = randint(0,100)
guesses = [0]
while True:
    guess = int(input("Enter a number 1 and 100 "))
    if(guess < 0  or guess >100):
        print('OUT OF BOUNDS')
        continue
    if(num == guess):
        print(f'Voila you guess the correct number in {len(guesses)}')
        print(guesses)
        break
    guesses.append(guess)
    if guesses[-2]:
        if abs(num - guess) < abs(num - guesses[-2]) :
            print('warmer')
        else:
            print('colder')
    else:
        if guess - 10 < num < guess +10:
            print('warm')
        else:
            print('cold')
