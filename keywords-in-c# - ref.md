
<div dir = rtl > 

## Keyword `ref`
 
تستخدم لتحديد مكان معين بالذاكرة ليتم وضع القيمة فيه مباشرة وليس نسخ القيمة في مكان اخر ولكن يجب ان تحدد قيمة مسبقة للمتغير .

**مثال :**

<div dir = ltr > 

{


   public void sum(ref int x) يتم تمرير عنوان المتغير لدالة جمع 
{
    x = 5 +16 امر جمع العددين ووضعهم في عنوان المتغير
}

int number = 1;
sum(ref number); إستدعاء دالة الجمع
Console.WriteLine(number); سنلاحظ ان قيمة المتغير الاساسية تم تغييرها

}


</dir>
</dir>
