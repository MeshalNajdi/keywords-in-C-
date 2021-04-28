<div dir = rtl > 

## Keyword `override`
 يجب إستخدام هذا الامر كتابع لـ"virtual " في دوال وبيانات المجموعة الوارثة التي تريد التعديل على البيانات  او الدوال في المجموعة الموروث منها . 


**مثال :**

 في المثال ادناه نلاحظ ان الكلمه "virtual " جعلت الدالة التي تنتمي لمجموعة "people " قابلة للتعديل من مجموعة "student "التابعة لها . وتم استخدام الامر "override "في المجموعة الوارثة للتعديل على دالة في المجموعة الموروث منها .
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