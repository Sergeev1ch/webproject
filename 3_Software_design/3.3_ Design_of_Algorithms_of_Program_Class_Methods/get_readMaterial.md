# Get Read Material
***
@startuml  
start  
title Get_readMaterial()  
 :Вывод меню для выбора темы;  
   note right  
   FR1.1  
   end note  
 :Запрос к БД на вывод материала по теме;  
   note right  
   material.find({theme: req.body.theme}, => (err, result){})  
   end note  
 :Отображение материалов;  
stop  
@enduml  
***
![3.3.1](https://github.com/Sergeev1ch/webproject/blob/main/jpg/3.3.1.png)
