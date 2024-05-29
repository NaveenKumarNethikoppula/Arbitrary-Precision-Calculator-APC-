# Arbitrary-Precision-Calculator-APC-
Introduction:-
Arbitrary-precision arithmetic, also called big-num arithmetic, multiple precision arithmetic, or sometimes infinite-precision arithmetic, indicates that calculations are performed on numbers whose digits of precision are limited only by the available memory of the host system. This contrasts with the faster fixed-precision arithmetic found in most arithmetic logic unit (ALU) hardware, which typically offers between 8 and 64 bits of precision. Explore the world of arbitrary-precision arithmetic with our calculator project in C

 

Some example applications include:-

A common application is public-key cryptography, whose algorithms commonly employ arithmetic with integers having hundreds of digits.
Arbitrary precision arithmetic is also used to compute fundamental mathematical constants such as π to millions or more digits.
The goal of this project is to implement various mathematical operations of given two big numbers by storing in an Abstract Data Type (ADT) like linked list.

 

Data Structres Projects Explore the intersection of data structures and arithmetic with our projects and extend your skills through our calculator project in C. For our implementation following mathematical operations are considered: 

Addition (+)
Subtraction (-)
Multiplication (*)
Division (/)
Modulus (%)
Power (^)
Given the two big numbers it has to be sliced and stored across different nodes of the linked list. Depending on the type of operation performed it should create a result linked list and stored the output. It should also take care of printing the given output from the newly crated output list. Appropriate handling of specific things (ex: carry forward) need to be taken care during implementation. All operations should work for integer numbers and also for numbers with decimal point. Slice the numbers according to sizeof(int), should be portable across different machines.

During the implementation special care need to be taken for handling zero inputs by reducing the work and optimizing the program. Similar to zero input, there can be multiple corner cases / optimization opportunities, which need to be taken care appropriately. If any one of the given input number is zero, the following Algorithm can be applied. 

If Num1 = 0 and Num2 = x, then directly print Num2 as output.
If Num1 = x and Num2 = 0, then directly print Num1 as output.
If Num1 = 0 and Num2 = 0, then directly print 0 as output
Requirement Details:
1. User will enter two big numbers along with the operator in the terminal, say x+y, where x and y are very large numbers and + is the operation that need to be performed.

2. Application will perform the operation based on the user input and display the result.

 

User Interface requirements:-

 

1. Run the application
    ./apc

 

2. Enter the input    1234567890121234518775261672673+718625634152778367635544816
Note: Application has to figure out the operator present in the input and perform the operation.

 

3. Result will be displayed
 1235286515755387297142897217489

 

4. Make the program user-friendly as given below
Want to continue? Press [yY | nN]
Note: If the user selects the option, n | N, the application will be terminated or else will run if the user selects the      option y | Y.

Skeleton Code:
The skeleton code in a very interesting concept used in Emertxe. By looking into the skeleton code, you will get a clear picture into converting the given requirement into a working solution. This will also take care of important aspects like modularity, clean coding practices, re-usability etc.
