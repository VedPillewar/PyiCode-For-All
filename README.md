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


[5]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Replace substring using replace().

CODE NO :- 5

    s=""
    s1=s.replace("difficult ","easy ")
    print(s1)
    
    s="ababababababab"
    s1=s.replace("a","b")
    print(s1)



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



[8]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Find maximum and minimum among three numbers using nested if-else.

CODE NO :- 8

    n1 = int(input('Enter the value of paper1:'))
    n2 = int(input('Enter the value of paper2:'))
    n3 = int(input('Enter the value of paper3:'))
    
    if n1 > n2:
    if n1 > n3:
    print("n1 is greater")
    else:
    print("n3 is greater")
    else:
    if n2 > n3:
    print("n2 is greater")
    else:
    print("n3 is greater")
    
    if n1 < n2:
    if n1 < n3:
    print("n1 is smaller")
    else:
    print("n3 is smaller")
    else:
    if n2 < n3:
    print("n2 is smaller")
    else:
    print("n3 is smaller")

[9]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Check grade based on percentage using if-elif ladder.

CODE NO :- 9
    
    per = int(input('Enter your percentage:'))
    
    if per >= 90:
    print("A")
    elif per >= 80 and per < 90:
    print("B")
    elif per >= 60 and per < 80:
    print("C")
    else:
    print("FAIL")

[10]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Perform dictionary operations and string methods.

CODE NO :- 10

    mydict = {
    "name": "prashant",
    "professional": "developer",
    "enpid":1001
    }
    print(mydict)
    
    mydict[102] = "peter"
    print(mydict)
    
    for x in mydict:
    print(x)
    
    for x in mydict.values():
    print(x)
    
    for x,y in mydict.items():
    print(x,y)
    
    name = "prashantjha"
    print(name[0:5])
    print(name[::-1])

[11]|[A] LANGUAGE:- "Python"

PROBLEM STATEMENT:- Find maximum among five numbers.

CODE NO :- 11

    v1 = float(input("Enter value 1: "))
    v2 = float(input("Enter value 2: "))
    v3 = float(input("Enter value 3: "))
    v4 = float(input("Enter value 4: "))
    v5 = float(input("Enter value 5: "))
    
    max_val = v1
    
    if v2 > max_val:
    max_val = v2
    if v3 > max_val:
    max_val = v3
    if v4 > max_val:
    max_val = v4
    if v5 > max_val:
    max_val = v5
    
    print("Maximum value is:", max_val)



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


