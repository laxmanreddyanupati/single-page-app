# single-page-app
my info
this is my new project 
sing System;

    string name ="laxman";
int age =23;

Console.WriteLine("name");
Console.WriteLine("age");
Console.WriteLine($"my name is {name}");
Console.WriteLine($"i am {age} years old");
using System;
student info **********
    string name ="laxman";
    int age =23;
    string degree ="b.tech";
    string leasrning ="c#";
    string goal ="dotnet developer";
    Console.WriteLine("================");
    Console.WriteLine(" student info ");
    Console.WriteLine("===============");
    Console.WriteLine("$name:{name}");
    Console.WriteLine("$age:{age}");
    Console.WriteLine("$degree:{degree}");
    Console.WriteLine("$learning:{learning}");
    Console.WriteLine($"goal:{goal}");
    Console.WriteLine("================");
    using System;
//////correct one////
    string name ="laxman";
    int age =23;
    string degree ="b.tech";
    string leasrning ="c#";
    string goal ="dotnet developer";
    Console.WriteLine("================");
    Console.WriteLine(" student info ");
    Console.WriteLine("===============");
    Console.WriteLine($"name: {name}");
    Console.WriteLine($"age: {age}");
    Console.WriteLine($"degree: {degree}");
    Console.WriteLine($"leasrning: {leasrning}");
    Console.WriteLine($"goal: {goal}");
    Console.WriteLine("================");

practiced:variables
operators
if statements
switch statements
loops
parameters

using System;
//variables
int age =23;
double salary=35000.50;
string name="laxman";

var age =23;
var name ="laxman";

// operators
int a =10;
int b =20;
 Console.WriteLine(a +b);
 Console.WriteLine(a-b);
 Console.WriteLine(a*b);
 Console.WriteLine(a/b);
 Console.WriteLine(a%b);

 // if statements
 int age =23;
 if(age>=18)
{
    Console.WriteLine("adult");
}
    else
    {
        Console.WriteLine("minor");
        
    
}

//switch statements
int day = 2;
switch (day)
{
    case 1:
           Console.WriteLine("monday");
    break;
    case 2:
           Console.WriteLine("tuesday");
    default:
            Console.WriteLine("invalid day");
            break;

}

//loops
// in these we have for/foreach/while
for(int i=1; i<=5; i++)
{
    Console.WriteLine(i);
    }//output= 1,2,3,4,5

    // parameters
    static void greet(string name)
{
    Console.WriteLine($"hello {name}");} // we call the method as greet laxman \\ we will get output as hello laxman

     static void Addnumbers(int a,int b)
{
    Console.WriteLine("a+b");
}
Addnumbers(10,20);// we get output as 30

