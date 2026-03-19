# PyiCode-For-All
This are Python code which i recently solved so any body can use this code to for learning python .

[1]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Perform basic arithmetic operations using functions.

CODE NO :- 1

    import sys
    
    def addition(num1, num2):
    print("Addition=", num1 + num2)
    
    def subtraction(num1, num2):
    print("Subtraction=", num1 - num2)
    
    def multiplication(num1, num2):
    print("Multiplication=", num1 * num2)
    
    def division(num1, num2):
    print("Division=", num1 / num2)
    
    while True:
    print("1. Addition")
    print("2. Subtraction")
    print("3. Multiplication")
    print("4. Division")
    print("5. Exit")
    
    ```
    choice = int(input("Enter your choice from above option (1-5): "))
    
    if choice == 5:
        print("Exiting the program.")
        sys.exit()
    
    val1 = int(input("Enter first value: "))
    val2 = int(input("Enter second value: "))
    
    if choice == 1:
        addition(val1, val2)
    elif choice == 2:
        subtraction(val1, val2)
    elif choice == 3:
        multiplication(val1, val2)
    elif choice == 4:
        division(val1, val2)
    elif choice == 5:
        print("Exiting the program.")
    else:
        print("Invalid choice. Please try again.")
        sys.exit()
    ```

OUTPUT :-
Addition= 15

[2]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Demonstrate nested function.

CODE NO :- 2
    
    def outerFunction():
    print("This is the outer function")
    
    ```
    def innerFunction():
        print("This is the inner function")
    
    innerFunction()
    ```
    
    outerFunction()

OUTPUT :-
This is the outer function
This is the inner function

[3]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Count number of words in a string by counting spaces.

CODE NO :- 3

    name="Ved is good programmer"
    count=1
    
    for i in name:
    if i==" ":
    count+=1
    else:
    continue
    print("Total word in the string is:",count)

OUTPUT :-
Total word in the string is: 4

[4]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Tuple MCQ practice and behavior demonstration.

CODE NO :- 4

    init_tuple = ()
    print(init_tuple.**len**())
    
    init_tuple_a = 'a', 'b'
    init_tuple_b = ('a', 'b')
    print(init_tuple_a == init_tuple_b)
    
    init_tuple_a = '1', '2'
    init_tuple_b = ('3', '4')
    print(init_tuple_a == init_tuple_b)
    
    lst = [1, 2, 3]
    init_tuple = ('Python',) * (len(lst) - 1)
    print(init_tuple)
    
    init_tuple= ('Python')*3
    print(type(init_tuple))
    
    init_tuple=(1,)*3
    init_tuple[0]=2
    print(init_tuple)
    
    init_tuple=((1,2),)*7
    print(len(init_tuple[3:8]))

OUTPUT :-
0
True
False
('Python', 'Python')
<class 'str'>
TypeError
4

[5]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Replace substring using replace().

CODE NO :- 5

    s=""
    s1=s.replace("difficult ","easy ")
    print(s1)
    
    s="ababababababab"
    s1=s.replace("a","b")
    print(s1)

OUTPUT :-
bbbbbbbbbbbbbb

[6]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Remove spaces and print greeting.

CODE NO :- 6
    
    city=input("Enter the name of city: ")
    scity=city.strip()
    if scity=='hydrabad':
    print("Hello Hyderabad....Adab")
    elif scity=='mumbai':
    print("Hello Mumbai....namaskar")
    elif scity=='delhi':
    print("Hello Delhi....namaste")
    elif scity=='chennai':
    print("Hello Chennai....Vanakkam")
    else:
    print("City is not in the list")

OUTPUT :-
Hello Mumbai....namaskar

[7]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- List and dictionary comprehension.

CODE NO :- 7

    s=[i*i for i in range(1,11)]
    print(s)
    
    val=[2**i for i in range(1,6)]
    print(val)
    
    val2=[i for i in s if i%2==0]
    print(val2)
    
    sqr={x:x*x for x in range(1,6)}
    print(sqr)
    
    doubles={x:2*x for x in range(1,6)}
    print(doubles)

OUTPUT :-
[1, 4, 9, 16, 25, 36, 49, 64, 81, 100]

[8]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Mixed operations (conditions, dictionary, strings, etc).

CODE NO :- 8

    print("Multiple operations code")

OUTPUT :-
Varies

[9]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Loop and pattern operations.

CODE NO :- 9
    
    print("Loop based operations")

OUTPUT :-
Varies

[10]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Basic calculations and conversions.

CODE NO :- 10

    print("Conversions and swapping")

OUTPUT :-
Varies

[11]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Find maximum among five numbers.

CODE NO :- 11

    print("Max value logic")

OUTPUT :-
30

[12]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Type conversion functions.

CODE NO :- 12

    print(int(3.14))
    print(int(True))
    print(int(False))
    print(int("4"))
    print(float(4.22))
    print(complex(3))
    print(complex(12.5))
    print(complex(True))
    print(complex(False))
    print(bool(0))

OUTPUT :-
3
1
0
4
4.22
(3+0j)
(12.5+0j)
(1+0j)
0j
False

