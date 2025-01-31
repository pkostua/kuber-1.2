# Решение домашнего задания к занятию «Базовые объекты K8S»
https://github.com/netology-code/kuber-homeworks/blob/main/1.2/1.2.md
## Задание 1. Создать Pod с именем hello-world
Манифест https://github.com/pkostua/kuber-1.2/blob/master/helow-world.yml  
Команда get pods и проброс портов  
![image](https://github.com/user-attachments/assets/e7c4d71d-c5f5-43fb-8303-2a970f4e4ed8)  
Http Ответ сервера  
![image](https://github.com/user-attachments/assets/3d6b6889-7bb7-43ec-b879-48cb8b10a3ba)  

## Задание 2. Создать Service и подключить его к Pod
Применение манифеста, поды и сервисы
![image](https://github.com/user-attachments/assets/0d4cef89-0049-4562-a5e8-0701f000d412)
Проброс порта на сервис  
```
kubectl port-forward service/netology-svc 8080:80
```
Ответ сервера  
![image](https://github.com/user-attachments/assets/e9462926-d172-44b2-bb48-1fe21ecb0775)  





