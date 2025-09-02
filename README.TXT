Project: naive-ticket-machine
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling
   Pearson Education

It is discussed in chapter 2.

Purpose of project: To illustrate the basics of fields, constructors, and methods.
How to start this project: Create one or more TicketMachine objects.

part ii
2. 0
3. if you put too much in, the machine keeps it, no refunds, the ticket machine also will print a ticket even if too little was inserted, it will also print a ticket for a negative balance
5. the price shown on the ticket is different
6. 
public class Student
{
    
}
and
public class LabClass
7. lots of errors, but the main one is 'class, interface, enum, or record expected', the error message doesnt really explain whats wrong
8. word 'public' can be left out without error
9. the word 'class' on the other hand cannot, i think this is because public defines a feature of the class (visibility) so its not entirely required, but class defines the code as a class and so cant be left out otherwise the computer doesnt know what it is

10. 
fields:
 price
 balance 
 total
constructors: 
 public TicketMachine(int cost), creates the machine
methods:
 getPrice(), finds a tickets price
 getBalance(), checks the balance in the machine
 insertMoney(int amount), adds money to the balance
 printTicket(), sets the balance to zero and prints a fake ticket in the terminal
11. no parentheses and the return type is 'class'
12. int, Student, Server
13. alive, tutor, game
14. Student, Server, Person, Game
15. yes, the computer cant understand it in any other order and so returns errors
16. yes, always
17. private int status;
18. Student
19. two, the first is a string and the second is a double
20. no, theyll be stored in the object when its created
