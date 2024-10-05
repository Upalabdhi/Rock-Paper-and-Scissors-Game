import random
user1=input('enter user 1 choice(rock, paper, scissor):')
user2=random.choice(['rock','paper','scissor'])

if user1== user2:
    print('User 1 chose:', user1)
    print('Computer chose:', user2)
    print('it is a tie, Retry!!')
elif user1=='rock' and user2=='paper':
    print('User 1 chose:',user1)
    print('computer chose:', user2)
    print('paper wins hence computer wins!!')
elif user1=='paper' and user2=='rock':
    print('User 1 chose:',user1)
    print('computer chose:', user2)
    print('paper wins hence user1 wins!!')
elif user1=='rock' and user2=='scissor':
    print('User 1 chose:',user1)
    print('computer chose:', user2)
    print('rock wins hence user1 wins!!')
elif user1=='scissor' and user2=='rock':
    print('User 1 chose:',user1)
    print('computer chose:', user2)
    print('rock wins hence computer wins!!')
elif user1=='scissor' and user2=='paper':
    print('User 1 chose:',user1)
    print('computer chose:', user2)
    print('scissor wins hence user1 wins!!')
elif user1=='paper' and user2=='scissor':
    print('User 1 chose:',user1)
    print('computer chose:', user2)
    print('scissor wins hence computer wins!!')
else:
    print('Invalid Number')
