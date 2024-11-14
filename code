#Quiz game

questions=["1.How many elements are there in the periodic table? ",
           "2.Which animal lays the largest eggs? ",
           "3.What is the most abundant gas in the Earth's atmosphere? ",
           "4.How many bones are there in human body? ",
           "Which planet in the solar system is the hottest?"
           ]

options=(('A.116','B.117','C.118','D.119'),
         ('A.Ostrich','B.Whale','3.Crocodile','4.Elephant'),
         ('A.Nitrogen','B.Oxygen','C.Carbon-dioxide','4.Hydrogen'),
         ('A,207','B.300','C.205','D.206'),
         ('A.Mercury','B.Venus','C.Earth','D.Mars')
         )
ques_num=0
guesses=[]
score=0
answers=("C","A","A","D","B")
for question in questions:
    print('-'*20)
    print(question)
    for option in options[ques_num]:
        print(option)
    guess=input("Enter your choice (A,B,C,D):").upper()
    guesses.append(guess)
    if guess == answers[ques_num]:
              score+=1
              print("Correct")
    else:
        print("Incorrect")
        print(f'Correct answer is {answers[ques_num]}')
    ques_num+=1
print('-'*20)
print('Answers are',end=" ")
for answer in  answers:
    print(answer,end=' ')
print('-'*20)
print('Guesses are',end=' ')
for guess in guesses:
    print(guess,end=' ')
print('-'*20)
print('-'*20)
print('Your Result is:')
score=int(score/len(questions)*100)
print(f'Your score is {score}%')
