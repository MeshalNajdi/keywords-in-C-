<div dir = rtl > 

## Keyword `protected`
  هي إحدى كلمات تحديد الوصول  وهي تجعل الوصول لبيانات النوع  حكرا على النوع ومن يرث منه.


**مثال :**

 في المثال ادناه نلاحظ ان الكلمه "protected "  تجعل جميع بيانات النوع "people " قابلة للوصول من دوال "people "و الانواع المشتقة منه . 

<div dir = ltr > 

{


    protected class People  
     { 
    protected string name ; 
    protected int age ;
    protected people() {
        this.name = "name";
        this.age = 20 ;
    }
   
}


</dir>
</dir>