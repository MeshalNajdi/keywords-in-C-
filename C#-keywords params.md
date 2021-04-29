<div dir = rtl > 

## Keyword `params`
 عند تعيينك لهذا لاحد المدخلات من نوع "params" فهو يجب ان يكون مصفوفة , و الميزة في هذا التعريف ان المصفوفة المدخلة لها عدد غير محدد من العناصر . ولكن هذا المتغير يجب ان يكون اخر الانواع تعريفا في المدخلات .


**مثال :**

 في المثال ادناه نلاحظ ان الكلمه "params " تقبل مصفوفة مهما كان عدد عناصرها وتطبع عناصر المصفوفة .
<div dir = ltr > 

{


    public class paramsClass{
    
    public static void paramsArr(params int[] S)
    
    {
        for (int i = 0; i < S.Length; i++)
        {
            Console.Write(S[i] + " ");
        }
        Console.WriteLine();
    }
   
    
   
}


</dir>
</dir>