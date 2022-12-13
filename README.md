# GITHomework6
## git add -p
В созданыый файл doc.html вносим некоторые изменения

![image](https://user-images.githubusercontent.com/118339667/207326156-cf03bc9f-9af8-4a14-bc66-b7514c0adc79.png)

Вводим команду git add -p и видим все изменения, которые непроиндексированы. 

![image](https://user-images.githubusercontent.com/118339667/207328231-19a157c7-4c39-4d4d-b65a-b2a82e51437d.png)

Чтобы разделить изменения, вводим s и видим, что теперь для каждого изменения требуется отдельное действие

![image](https://user-images.githubusercontent.com/118339667/207332206-6c88731c-ee9f-4352-b2cf-7bdeb75c892e.png)

Для индексации одного изменения выбираем y, а чтобы не индексировать второе изменение, выбираем n. Выполняем git status т видим, что файл doc.html находится одновременно в двух состояниях. То есть, команда git add -p позволяет индексировать изменения частично 

![image](https://user-images.githubusercontent.com/118339667/207338238-8bb672b3-719c-4d9a-8570-e8fe72b26724.png)

## Работа в SmartGit

### Подключение локального репозитория

Чтобы подключить локальный репозиторий, нажимаем на кнопку Add or Create. В поле появившегося окна вводим адрес локального репозитория

![image](https://user-images.githubusercontent.com/118339667/207349853-404e947e-5f5a-429e-8cf8-9e0236b7685e.png)
![image](https://user-images.githubusercontent.com/118339667/207350547-e4d24095-7db0-4593-8646-0c7bfe56106e.png)

### Добавление изменений в индекс

Чтобы добавить изменения файла doc.html в индекс - нажимаем на кнопку Stage 

![image](https://user-images.githubusercontent.com/118339667/207355286-8895f717-c711-42c9-aac1-9108f628865c.png)

Изменения проиндексированы и можем наглядно видеть, где какие изменения были внесены

![image](https://user-images.githubusercontent.com/118339667/207355915-cead9352-15c3-4b23-b6e6-ee383a8514b5.png)

### Коммит изменений

Чтобы закоммитить изменения, мы в окошке для коммитов пишем комментарий и нажимаем на кнопку Commit

![image](https://user-images.githubusercontent.com/118339667/207357052-4c797df3-2c54-452d-9816-50f89944d603.png)

После этого происходит автоматический переход на вкладку History, где мы видим ветку со всеми коммитами
![image](https://user-images.githubusercontent.com/118339667/207359472-c264c868-411a-4f34-83f8-6db995e07f6b.png)

### Изменение последнего коммита

1. Мы создали и закоммитили file1.txt. 
2. Затем мы создали и отправили в индекс file2.txt.
3. Для того, чтобы внести изменения в последний коммит и закоммитить вместе с file1.txt file2.txt мы выбираем Amend last commit. автоматически появляется комментарий к предыдущему коммиту, который мы можем изменить

![image](https://user-images.githubusercontent.com/118339667/207367011-67b9d692-50a3-4224-b953-724ded584322.png)

Вводим изменения в комментарий и нажимаем коммит. Измененный комментарий появился вместо предыдущего, оба файла закоммичены

![image](https://user-images.githubusercontent.com/118339667/207368019-ca09766e-8a17-4266-a0ff-416f0358681e.png)


### Создание веток

Для создания новой ветки нажимаем на кнопку Branch и выбираем Add Branch

![image](https://user-images.githubusercontent.com/118339667/207369259-124d1995-76cd-46a1-95a7-03282dfc56bf.png)

В открывшемся поле вводим название новой ветки, например, Feature_1 и нажимаем Add Branch (если не собираемся сразу переключаться на новую ветку)

![image](https://user-images.githubusercontent.com/118339667/207370267-784a450a-dacc-468d-bdfa-f681229c3ba6.png)

Создалась ветка, идентичная ветке main

![image](https://user-images.githubusercontent.com/118339667/207371274-6c447077-85a0-499f-be63-2ccae3173ad7.png)


В новой ветке Feature_1 создаем и коммитим новый файл file3.txt

![image](https://user-images.githubusercontent.com/118339667/207375930-d8c7de99-2aa9-407c-a9aa-5e407a3d6bf9.png)

при переходе в ветку main мы видим, что файла file3.txt в ней отсустствует

![image](https://user-images.githubusercontent.com/118339667/207376551-55939f9d-ca81-4ddc-9ff5-d66fde4fdfcb.png)
















