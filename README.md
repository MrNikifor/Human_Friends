# Итоговая контрольная работа

## Задания

1. Используя команду cat в терминале операционной системы Linux, создать
   два файла Домашние животные (заполнив файл собаками, кошками,
   хомяками) и Вьючные животными заполнив файл Лошадьми, верблюдами и
   ослы), а затем объединить их. Просмотреть содержимое созданного файла.
   Переименовать файл, дав ему новое имя (Друзья человека).
2. Создать директорию, переместить файл туда.
3. Подключить дополнительный репозиторий MySQL. Установить любой пакет
   из этого репозитория.
4. Установить и удалить deb-пакет с помощью dpkg.
5. Выложить историю команд в терминале ubuntu
6. Нарисовать диаграмму, в которой есть класс родительский класс, домашние
   животные и вьючные животные, в составы которых в случае домашних
   животных войдут классы: собаки, кошки, хомяки, а в класс вьючные животные
   войдут: Лошади, верблюды и ослы).
7. В подключенном MySQL репозитории создать базу данных “Друзья
   человека”
8. Создать таблицы с иерархией из диаграммы в БД
9. Заполнить низкоуровневые таблицы именами(животных), командами
   которые они выполняют и датами рождения
10. Удалив из таблицы верблюдов, т.к. верблюдов решили перевезти в другой
    питомник на зимовку. Объединить таблицы лошади, и ослы в одну таблицу.
    11.Создать новую таблицу “молодые животные” в которую попадут все
    животные старше 1 года, но младше 3 лет и в отдельном столбце с точностью
    до месяца подсчитать возраст животных в новой таблице
12. Объединить все таблицы в одну, при этом сохраняя поля, указывающие на
    прошлую принадлежность к старым таблицам.
    13.Создать класс с Инкапсуляцией методов и наследованием по диаграмме.
14. Написать программу, имитирующую работу реестра домашних животных.
    В программе должен быть реализован следующий функционал:
    14.1 Завести новое животное
    14.2 определять животное в правильный класс
    14.3 увидеть список команд, которое выполняет животное
    14.4 обучить животное новым командам
    14.5 Реализовать навигацию по меню
    15.Создайте класс Счетчик, у которого есть метод add(), увеличивающий̆
    значение внутренней̆int переменной̆на 1 при нажатие “Завести новое
    животное” Сделайте так, чтобы с объектом такого типа можно было работать в
    блоке try-with-resources. Нужно бросить исключение, если работа с объектом
    типа счетчик была не в ресурсном try и/или ресурс остался открыт. Значение
    считать в ресурсе try, если при заведения животного заполнены все поля.

## Выполнение

### Решение 1

cat > "Pets animals" <<EOF
Dogs
Cats
Hamsters
EOF

cat > "Pack animals" <<EOF
Horses
Camels
Donkeys
EOF

cat "Pets animals" "Pack animals" > "Animals"

cat "Animals"

mv "Animals" "Human Friends"

cat "Human Friends"

![Задание 1.jpg](Imges/Задание%201.png)

### Решение 2

mkdir Animals

mv 'Human Friends' Animals/

cd 'Human Friends'

cat 'Human Friends'

cd Animals

cat 'Human Friends'

![Задание 2.png](Imges/Задание%202.png)

### Решение 3

sudo wget https://dev.mysql.com/get/mysql-apt-config_0.8.23-1_all.deb

sudo dpkg -i mysql-apt-config_0.8.23-1_all.deb

sudo apt-get update

sudo apt-get install mysql-server

![Задание 3.png](Imges/Задание%203.png)
![Задание 3.1.png](Imges/Задание%203.1.png)
![Задание 3.2.png](Imges/Задание%203.2.png)
![Задание 3.3.png](Imges/Задание%203.3.png)

### Решение 4

sudo apt update

sudo install nginx

sudo stop nginx

sudo apt remove --purge nginx

![Задание 4.png](Imges/Задание%204.png)

### Решение 5

* *Все команды ubuntu выложены выше*.

### Решение 6

![Diogram_Human_Friands.png](Imges%2FDiogram_Human_Friands.png)

### Решение 7

*Бузу данных создал под названием animals_db, так как “Друзья человека”(Human Friends) уже ранее был создан в репозиторий в линуксе и будет называться так основной класс в написанной програме как указано на диаграме, чтобы в будущем не вызывать ошибку!*

![Задание 7 БД.png](Imges/Задание%207%20БД.png)

### Решение 8

![Задание 8](Imges/Задание%208.1%20бд.png)
![Задание 8](Imges/Задание%208.2%20бд.png)
![Задание 8](Imges/Задание%208.3%20бд.png)
![Задание 8](Imges/Задание%208.4%20бд.png)
![Задание 8](Imges/Задание%208.5%20бд.png)

### Решение 9

![Задание 9.1.png](Imges/Задание%209.1.png)
![Задание 9.2.png](Imges/Задание%209.2.png)
![Задание 9.3.png](Imges/Задание%209.3.png)
![Задание 9.4.png](Imges/Задание%209.4.png)

### Решение 10 & 11

![Задание 10.png](Imges/Задание%2010.png)
![Задание 11.png](Imges/Задание%2011.png)

### Решение 12

![Задание 12.2.png](Imges/Задание%2012.1.png)
![Задание 12.2.png](Imges/Задание%2012.2.png)

### Решение 13-15 

* *Выполнено в коде, пака-src*
