<div dir = rtl > 

## Keyword `virtual`
  إستخدام هذا الامر يجعل البيانات والدوال قابلة للتعديل من انواع البيانات الوارثة من نفس مجموعتها 


**مثال :**

 في المثال ادناه نلاحظ ان الكلمه "virtual " جعلت الدالة التي تنتمي لمجموعة "people " قابلة للتعديل من مجموعة "student "التابعة لها .
<div dir = ltr > 

{


    public class People  
     { 
    public string name ; 
    public int age ;
    public virtual info() {
        this.name = "name";
        this.age = 20 ;
         Console.WriteLine($"this is a {name}")
    }
    public class students : people {

       public override info() {
            Console.WriteLine("this is a student")
        }
    }
   
}


</dir>
</dir>