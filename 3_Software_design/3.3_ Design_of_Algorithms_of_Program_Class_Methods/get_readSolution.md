# Get Read Solution
***
@startuml  
start  
title Get_readSolution()  
 :Вывод решений к заданию;  
   note right  
   FR2.2  
   end note  
 :Запрос к БД на вывод решений по заданию;  
   note right  
   solution.find({task: req.body.task}, => (err, result){})  
   end note  
 :Отображение заданий;  
stop  
@enduml  
***
![3.3.3](https://github.com/Sergeev1ch/webproject/blob/main/jpg/3.3.3.png)
