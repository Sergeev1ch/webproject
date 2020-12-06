# Get Read Obj
***
@startuml  
start  
title Get_readObj()  
 :Запрос к БД на вывод геометрического объекта;  
   note right  
   object.find({theme: req.body.theme}, => (err, result){})  
   object.find({task: req.body.task}, => (err, result){})  
   object.find({solution: req.body.solution}, => (err, result){})  
   end note  
 :Отображение геометрического объекта;  
   note right  
   FR3.2  
   end note  
 stop  
@enduml  
***
![3.3.4](https://github.com/Sergeev1ch/webproject/blob/main/jpg/3.3.4.png)
