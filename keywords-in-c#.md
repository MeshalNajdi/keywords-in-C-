
<div dir = ltr > 

## Keyword `Base`
Base keyword is used from a  derived class to access elements of the base class : it could be used to call a method or select a certain constructor from the base class.

**Example :**

{


    public class People { 
    string name ; 
    int age ;
    public people() {
        this.name = "name";
        this.age = 20 ;
    }
    }
    public class students : people {

        public student () : Base () {
            Console.WriteLine("this is a student")
        }
    }
}


</dir>


<div dir = ltr > 

## Keyword `as`
Used to explicitly converts the result of an expression to a given reference or nullable value type . If it isn't possible to convert the value < as operator return Null .



**Example :**

{


    IEnumerable<int> numbers = new[] { 10, 20, 30 };
    IList<int> indexable = numbers as IList<int>;
}

## Keyword `Abstract`
Abstract classes are classes that are used to inherit fields and functions from, but it can not be instantiated to an object.



**Example :**

    public abstract class shape
    {

        public abstract void draw();
    }
    public class Rectangel : shape
    {

        public override void draw()
        {
            Console.WriteLine("Rectangel");
        }
    }
    

## Keyword `Class`
a class contains objects that has similar features and methods . Classes can also inherit from other classes .



**Example :**

     public class People { 
     string name ; 
     int age ;
     
    }

## Keyword `goto`
Goto statement transfers the program control directly to a labeled statement.



**Example :**

    static void Main(string[] args)
        {
        print:
        Console.WriteLine("write a string that  contains 7");
            string s = Console.ReadLine();

            if (!s.Contains("7"))
                goto print;
        }


## Keyword `Delegate`
delegate is a method pointer that save the references of the methods assigned to it.



**Example :**

    public delegate int del(int a, int b);
        static void Main(string[] args)
        {
            del del = sum;
            Console.WriteLine(del(1, 2));
            
        }
        static int sum(int a, int b)
        {
            return a + b;
        }

</dir>