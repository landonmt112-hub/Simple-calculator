# Simple-calculator
def calculator():
    print("== Addition, Subtraction, Multiplication, Division ==")
    num_one= int(input('Please tell us your first number: '))
    num_two = int(input('Please tell us your second number: '))
    # ask for numbers
    answer = input('What do you want to do with your numbers? ')
    if answer.lower() == 'addition':
        print(num_one + num_two)
    if answer.lower() == 'subtraction':
        print(num_one - num_two)
    if answer.lower() == 'multiplication':
        print(num_one * num_two)
    if answer.lower() == 'division':
        print(num_one / num_two)

calculator()
