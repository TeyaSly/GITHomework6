# GITHomework6
## git add -p
В созданыый файл doc.html вносим некоторые изменения
![image](https://user-images.githubusercontent.com/118339667/207326156-cf03bc9f-9af8-4a14-bc66-b7514c0adc79.png)

Вводим команду git add -p и видим все изменения, которые непроиндексированы. 
![image](https://user-images.githubusercontent.com/118339667/207328231-19a157c7-4c39-4d4d-b65a-b2a82e51437d.png)

Чтобы разделить изменения, вводим s и видим, что теперь для каждого изменения требуется отдельное действие
![image](https://user-images.githubusercontent.com/118339667/207332206-6c88731c-ee9f-4352-b2cf-7bdeb75c892e.png)

Для индексации одного изменения выбираем y, а чтобы не индексировать второе изменение, выбираем n. Выполняем git status т видим, что файл doc.html находится одновременно в двух состояниях. То есть, команда git add -p позволяет индексировать изменения частично 
![image](https://user-images.githubusercontent.com/118339667/207337278-2fb575fb-3401-4c79-8393-69cab534d286.png)

