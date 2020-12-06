# Get Read Task
***
@startuml  
start  
title Get_readTask()  
 :Вывод меню для выбора темы;  
   note right  
   FR1.1  
   end note  
 :Запрос к БД на вывод заданий по теме;  
   note right  
   task.find({theme: req.body.theme}, => (err, result){})  
   end note  
 :Отображение заданий;  
stop  
@enduml  
***
![3.3.2](https://github.com/Sergeev1ch/webproject/blob/main/jpg/3.3.2.png)
