<div dir = rtl > 

## Keyword `private`
  هي إحدى كلمات تحديد الوصول  وهي تجعل الوصول لبيانات النوع  حكرا على النوع فقط .


**مثال :**

 في المثال ادناه نلاحظ ان الكلمه "private "  تجعل جميع بيانات النوع "people " قابلة للوصول من دوال "people " فقط لا غير .
<div dir = ltr > 

{


    private class People  
     { 
    private string name ; 
    private int age ;
    private people() {
        this.name = "name";
        this.age = 20 ;
    }
   
}


</dir>
</dir>