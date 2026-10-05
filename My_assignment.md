# Section A — Concepts and Understanding

# ASSIGNMENT

1. In your own words, explain each of the following:

a. Variable
b. Expression
c. Assignment
d. Statement
e. Data type

#Answer

1a. A variable is a labeled storage box in the computer's memory.
1b. An expression is any piece of code that calculates a final value.
1c. 
1d. A statement is a complete instruction that tells the computer to perform an action
1e. A data type is the category or kind of value you are working with.

2. We compared an expression and a statement in programming with a phrase and a clause/sentence in English grammar.

Explain this comparison.

Then consider:

int total = price * quantity;
Identify:

a. The variable being declared
b. The expression used to calculate a value
c. The assignment taking place
d. The complete statement
Explain the difference between a primitive data type and a reference data type in Java.

3. Explain the difference between a primitive data type and a reference data type in Java.

Then classify each of the following as either primitive or reference:

int
String
double
boolean
char
Student
long
Integer
Assume Student is a class created by a programmer.

#Answer

Primitive

Reference

int-Primitive.
String-Reference.
double
boolean.
char-Primitive.
Student-Primitive.

4. Suppose a programmer creates the following class:

class BankAccount {
}
Then writes:

BankAccount account;
Answer the following:

a. What is the data type of account?

b. Is BankAccount a primitive type or a reference type?

c. Why is BankAccount described as a user-defined type?

d. Does the variable account itself contain an entire BankAccount object? Explain briefly.

#Answer

a. The data type is BankAccount.

b. It is a reference type.

c. Java comes out of the box with built-in tools like numbers (int) and letters (char). And Java has no idea what a "Bank Account" or a "Video Game Character".


## Section B-Variables and Naming

5. For each name below, state whether it is a valid Java variable name.

If it is invalid, explain why.

studentName
2ndStudent
_total
class
account_balance
first-name
age2
student name
$salary
totalAmount
true
Score
For valid names that are legal Java but do not follow normal Java naming conventions, mention that as well.

6.int studentAge = 25;
double monthlySalary = 45000.50;
boolean isAccountActive = true;
String customerFullName = "Ada Lovelace";
int classStudentCount = 120;

## Section C — Declarations, Assignment and Expressions


8a. x + y=11 addition.
b. x - y=5 subtraction.
c. x * y=24	multiplication.
d. x / y	2 Division 
e. x + z=10.5	double 
f. (x + y) * 2=22

9a. 15.


## Section D — Data Types

a. A person’s age=int 
b. A person’s full name=string 
c. Whether a student has paid school fees
d. The price of a product such as 3500.75=float
e. The number of people in Nigeria=int
f. A student’s grade represented by one character, such as A=char(character)
g. The distance between two cities measured in kilometres and containing decimal values=float
h. Whether an application is currently running
i. The number of books in a library=int
j. A very large whole number that might exceed the normal range of int=long

## Section E — Overflow and Reasoning

Answer the following in your own words:

a. What is integer overflow?

b. Why can overflow occur even though a computer can perform calculations very quickly?

c. Does Java automatically make an int larger when its maximum value is exceeded?

d. Why can overflow be dangerous in real software?

#Answer
integer overflow occurs when integer generates a numeric value that is outside the maximum range.



c. no

d. like in a bank\organisation in which the bank holds peoples money; if one is add to the maximum value or the maximum number exceeds it's value it will turn to minus the minimum value which means dept.it will over flow.

## Section F — Programming Exercises

~~~ java

16.int pricePerBook = 3500;
int numberOfBooks = 4;
int totalPrice = pricePerBook * numberOfBooks;
System.out.println("Price of one book: ₦" + pricePerBook);
System.out.println("Number of books bought: " + numberOfBooks);
System.out.println("Total price: ₦" + totalPrice);
~~~    

## Section G — Read, Think and Debug

