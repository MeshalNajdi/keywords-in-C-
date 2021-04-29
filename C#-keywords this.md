<div dir = rtl > 

## Keyword `this`
  إستخدام هذا الامر يشير إلى عنصر من المجموعة ,  فهذا الامر يكتب احيانا بشكل مخفي من البرنامج  للتعبير عن العنصر بشكل ضمني .


**مثال :**

 في المثال ادناه نلاحظ ان الكلمه "this " عبرت عن العنصر المنشأ من نوع المجموعة واخذت نفس خصائص العنصر .
<div dir = ltr > 

{


    public class People  
     { 
    public string name ; 
    public int age ;
    public virtual info() 
        {
        this.name = "name";
        this.age = 20 ;
         Console.WriteLine($"this is a {name}")
        }
   
    }
   
}


</dir>
</dir>