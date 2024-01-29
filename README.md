9. Which of the following is NOT describe about a structure?
   A. We can have pointers of type structures.
   B. Defining a structure is like defining a new data type.
   C. A structure may contain members of many data types.
 = D. A structure may contain function as members of its elements.

Structure can have a member and a class*


10. Which of the following is a properly defined struct?
    A. struct { int x; }
    B. struct my_struct int x;
    C. struct my_struct{ int x; }
 = D. struct my_struct{ int x; };

Must have a semicolon ";" and curly braces "{ }"


11. Which symbol is used to define the member of a class externally?
    A. :
    B. #
    C. ::
 = D. };


12. Which of the following is declare just like a regular member function, but with a name that matches the class name and without any return type?
    A. Cass
    B. Object
  = C. Constructor
    D. User-defined

Constructor is named the same as the class and don't have a data type*


14. When constructor is invoked automatically?
    A. A class is defined.
    B. A class is referenced.
  = C. An object is instantiated.
    D. An object is called by a function.


15. What will be the output if the string syafiqah is entered in code Figure 1?

    Char name[20];
    cout << “Enter your name : ” ;
    cin.width(5);
    cin >> name;
    cout << name << endl;

    Figure 1

    A. syaf
  = B. syafi
    C. syafiq
    D. syafiqah


16. Which stream manipulator forces a floating point number to display a specific number of digits to the right of the decimal point?
  = A. fixed
    B. setw()
    C. width()
    D. scientific


17. Which stream manipulator is used to reset function showpos back to default display mode?
  = A. noshowpos
    B. stopshowpos
    C. cancelshowpos
    D. removeshowpoint


18. Which stream manipulator forces a floating point number to be output with its decimal point and trailing zeros?
    A. showcase
  = B. showpoint
    C. showarray
    D. noshowpoint


19. Which class file handle both file input and output?
    A. infile
    B. outfile
  = C. fstream
    D. ofstream


20. What does it mean by ofstream in C++?
    A. Delete the file.
  = B. Writes to a file.
    C. Reads from a file.
    D. Writes to a file & Reads from a file.


12. Which the following is used to call function within a class?
    A. Member
    B. Operator
    C. Class
  = D. Method


14. All of the following is a valid access specifier in a class EXCEPT:
    A. private
    B. public
    C. protected
  = D. encapsulated


15. How many times a derived class can inherit from a base class?
    A. One
    B. Maximum three
    C. Maximum five
  = D. More than one













(a)
(i) Account
(ii) Public and it can be accessed by all.
(iii) MyBal
(iv) To call the function displayTotalBalance.
(v) You may click here for total balance









Volume of Box1 : 210.0
Volume of Box2 : 240.0

210.0 * 12



Question 7

struct committee {

   string fullname;
   int year;
   float cgpa;
   string designation;
};


Struct committee  com1;
cout << com1.fullname;
cout << com1.year;
cout << com1.cgpa;
cout << com1.designation;















# include < iostream>
# include <fstream>
using namespace std;


Int main ( )
{
   int odd=0, oddTotal=0, sum=0;
   Instream infile;
   Infile.open("integer.txt")






while(infile>n)
{
   if(n/2!=0)
   {
      odd++;
      oddTotal=oddTotal+n;
   }
   sum=sum+n;
}
ofstream outfile;
outfile.open("odd.txt");





outfile << "Total of odd number : " << odd << endl;
outfile << "Summation of odd number : " << oddTotal << endl;


cout << "The total of all numbers : " << sum;












#include <iostream>
using namespace std;

class Movie {
   private
      string title;
      int year;
      float income.profit;
      string BoxOfficeStandard;

public:
Movie ( ) {
    cout << "Enter the Title Movie : ";
   getline (Cin,title);
    cout << "Enter the Year of Movie Lanveh : ";
   cin >> year;
   cout << "Enter the profit of the movie (USD) : ";
   cin >> income_profit;
}

void report ( ) {
   cout << "Movie title" << title << "produce in
   the year" << year << " is a " << BoxOfficeStatus;




void get BoxOfficeStatus ( )
{ 
   if (income_profit > 50,000 oou)
      return " Box Office";
   else 
      return "flop";
}
},




int main ( )
{
   Movie m1;
   m1.report;
}
