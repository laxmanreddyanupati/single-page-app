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

\\ interpolation//
sing System;
					
public class Program
{
	public static void Main()
	{
		string name="laxman";
		int age=23;
		Console.WriteLine($"my name is {name} and i am {age} years old");
	}
}
		/// arthemetic operators///
        using System;
					
public class Program
{
	public static void Main()
	{ 
		int a =10;
		int b=4;
		Console.WriteLine(a+b);
		Console.WriteLine(a-b);
		Console.WriteLine(a*b);
		Console.WriteLine(a%b);
		Console.WriteLine(a/b);
	}
}

/// compression operators which says true or faalse ///
using System;
					
public class Program
{
	public static void Main()
	{ 
		int age =23;
		Console.WriteLine(age ==23);
		Console.WriteLine(age!=23);
		Console.WriteLine(age >23);
		Console.WriteLine(age<23);
		Console.WriteLine(age>=23);
	}

  ///  logical operators////
  and//
  using System;
					
public class Program
{
	public static void Main()
	{
		int age = 23;
         bool hasId = true;

        if (age >= 18 && hasId)
{
         Console.WriteLine("Allowed");
}

	}
}

\\or condition which helep to find either one value is true//
using System;
					
public class Program
{
	public static void Main()
	{
		int age = 23;
         bool hasId = true;

        if (age >= 18 || hasId)
{
         Console.WriteLine("Allowed");
}

	}
}

/// multiple conditions///in if else
using System;
					
public class Program
{
	public static void Main()
	{
		int marks =50;
		if(marks>=90)
		{
		Console.WriteLine("A");
		}
		else if(marks>=75)
		{
			Console.WriteLine("B");
		}
		else if(marks>=65)
		{
			Console.WriteLine("c");
		}
		else

		\\\while loop//

		using System;
					
public class Program
{
	public static void Main()
	{
		int i=5;
		while(i<=15)
		{ 
		Console.WriteLine(i);
			i++;
		}
	}
}
		{
			Console.WriteLine("fail");



			\\\\\student grade calculator\\\\\
			Console.WriteLine("=====student grade calculator======");
Console.WriteLine("Enter student name:");
string name =Console.ReadLine();
Console.WriteLine("Enter math marks:");
int math=Convert.ToInt32(Console.ReadLine());
Console.WriteLine("Enter phys marks:");
int phys=Convert.ToInt32(Console.ReadLine());
Console.WriteLine("Enter chem marks:");
int chem=Convert.ToInt32(Console.ReadLine());
int total=math+phys+chem;
double average=total/3.0;
string grade;
if(average>=90)
{
    grade="A";
}
else if(average>=80)
{
    grade="B";
}
else if(average>=70)
{
    grade="c";
}
else if(average>=60)
{
    grade="d";
}
else
{
    grade="e";
}
bool passed=math>=40&&phys>=40&&chem>=40;
Console.WriteLine("======student result======");
Console.WriteLine("name:" +name);
Console.WriteLine("math:"+math);
Console.WriteLine("phys:"+phys);
Console.WriteLine("chem:"+chem);
Console.WriteLine("total:"+ total);
Console.WriteLine("grade:"+grade);
Console.WriteLine("average:"+average);
Console.WriteLine("result:?");
		}
	}
}
