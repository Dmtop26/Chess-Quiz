# Chess-Quiz
This is a basic chess quiz about general knowledge, this project is mostly a Kickstarter to my coding career.

score = 0

question_1 = input("\nQuestion 1:\nWhat piece moves in an L shape?\n").lower()

if question_1 == "knight" or question_1 == "a knight":
    score = score + 1

question_2 = input("\nQuestion 2:\nWhich piece has move value, a rook or a bishop?\n").lower()

if question_2 == "a rook" or question_2 == "rook":
    score = score + 1

print("\nYour total score is: ", score)
