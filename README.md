## **IWNO2: Первый контейнер** 
*Цель работы: Данная лабораторная работа знакомит с основами контейнеризации и подготавливает рабочее место для выполнения следующих лабораторных работ.*
*Задание: Установить Docker Desktop и проверить его работоспособность.*
* Подготовка
Скачайте и установите Docker Desktop.

Выполнение
Создайте репозиторий containers02 и склонируйте его себе на компьютер.

Создайте в папке containers02 файл Dockerfile со следующим содержимым:

*FROM debian:latest
COPY ./site/ /var/www/html/
CMD ["sh", "-c", "echo hello from $HOSTNAME"]*
В той же папке проекта создайте папку site. В новой папке создайте файл index.html с произвольным содержимым.*
