
<div dir = rtl > 

## Keyword `in`
 
تستخدم لتحديد مكان معين بالذاكرة ليتم وضع القيمة فيه مباشرة وتمرر لامر او للدالة ولكن الفرق ان المتغير بعدها لن يتم تغيير قيمته.

**مثال :**

<div dir = ltr > 

{

var Numbers = new List<int> { 0, 1, 1, 2, 3, 5, 8, 13 }; انشاء قائمة
int count = 0;
foreach (int element in Numbers) نستدعي عناصر القائمة , ونلاحظ استخدام الامر ما يعني ان عناصر القائمة يجب ان لا يعدل عليها بعنوانها
{
    count++ زيادة العداد
}
Console.WriteLine($"Number of elements: {count}"); طباعة عدد الارقام بالقائمة

}


</dir>
</dir>
