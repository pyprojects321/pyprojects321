# 1.Questions and answers:
Questions = [
    ['Question1', '1. What is the most famous programming language in the world?', 'Python', 'JS', 'C++', 'Java', 1],
    ['Question2', '2. What is the biggest country in the world?', 'America', 'China', 'Russia', 'Bangladesh', 3],
    ['Question3', '3. Which country won 5 world cups?', 'Argentina', 'Brazil', 'Portugal', 'Italy', 2],
    ['Question4', '4. Which country has the most trophies in the world?', 'Brazil', 'Germany', 'Italy', 'Argentina', 4],
    ['Question5', '5. Which sport is the most famous sport in the world?', 'Basketball', 'Cricket', 'Football', 'Rugby',3]
]
print('The game is starting now.\n')
score = 0
for K in range(5):
    print(f'Your {K + 1} no question is', Questions[K][1])
    print('1.', Questions[K][2], '2.', Questions[K][3])
    print('3.', Questions[K][4], '4.', Questions[K][5])
    Answer = input(f'Enter your answer of {K + 1} no question(1/2/3/4) = ')
    if int(Answer) == Questions[K][6]:
        print('Your answer is correct.\n')
        score += 1
    else:
        print('Your answer is wrong.\n')
print(f'You got {score} out of 5.')





