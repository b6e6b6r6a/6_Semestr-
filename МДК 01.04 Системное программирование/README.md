# ЛК1 15.01.24.

Git Bash - команды для работы с Git из терминала 

[Установка Git Bash](https://git-scm.com/downloads)

Прокси сервер git config --global http.proxy 10.0.50.52:3128

[Практические работы](https://smartiqa.ru/courses/git/answer-key)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/44710bc2-9235-413e-94f3-8fda8c24a6bf)

Создание репозитория на компьютере: Инициализация Git Init

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/25d26c97-b57a-4a52-99a4-cad392da6bd7)

cmd //c tree .git - показывает структуру папки git

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/819f0ec2-b451-4ec9-acde-366de8262709)

git status - Показывает статус репозитория On branch master - Указывает имя версии

No commits yet - Нет сохраненных версий

Untracked files: - Неотслеживаемые файлы

(use "git add ..." to include in what will be committed) - Нужна команда добавить, чтобы зафиксировать версию для сохранения

    index.html
    pictures 
список файлов для сохранения

nothing added to commit but untracked files present (use "git add" to track) - Найдены файлы для добавления


**Задаем имя и email пользователя для текущего репозитория 23-12 303-15**
 
$ git config  --global user.name PK303-12 

$ git config  --global user.email PK303-12@gmail.com


**Отменяют прокси**

$ git config --global –unset http.proxy

$ git config --global --unset https.proxy

$ git config --global --unset core.gitproxy

Добавление файлов - git add * 

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/5e2aa216-dead-45b3-8ce1-0203cde9ff14)

**Для фиксации версии нужно указаь ее название, для этого создается сообщение** 
$ git commit -m "G-02: Initial"

**Выводим информацию о фиксации** 
$ git logl"

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/f1146ee2-bd13-49f3-ad2a-697ec8363ded)

**Подтверждение git**

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/9284ce83-fff5-4fd3-902e-6b0a049d0db8)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/5516acef-cf5d-44c7-9649-2f3000b79913)




![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/a891cce3-5cc1-4eb7-ac85-4ab5fa9ccb41)

Основные ошибки :

1. Remote - подключение к удаленному репозиторию (показывает на какой репозиторий мы хотим сохранить данные), может быть ошибка что неправильно укзали ссылку. Что бы изменить -> добавить сейт-URL
2. Авторизация - гитхабу нужно передать данные пользователя (логин, пароль или токен)
3. Прокси сервер - проверять включен или нет


# ЛК2 22.01.24.

1. Если есть папка _.git_, то команду _git init_ выполнять не нужно
2. Команды _config_ настраиваются на ПК 1 раз
3. _git remote_ указывается 1 раз

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/1190e164-00df-44c4-976b-c1d93667afb3)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/5f3e4844-f4eb-4e1f-8f66-c927c8870f2a)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/0869ec52-ce89-458f-9c6b-3bc948ccfa35)


![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/3e2326b1-3229-4dad-ad5f-e35ca17dea4d)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/0c84387a-5eac-45e1-87ef-9a8c873504ae)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/95a62750-7bc7-4acf-9e4b-bad7852b03c5)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/75649a9e-e5ca-4c98-a3a1-51971ca9af3c)



# ЛК 05.02.24 Работа с файлами

1. Создание
2. Перенесение
3. Редактирование
4. Удаление

**Обычный или regular файл**

1)touch kstr.txt

2)nano kstr.txt/home/stud/'Рабочий стол'

3)mv  kstr.txt/home/stud/'Рабочий стол'

4)rm /home/stud/'Рабочий стол'/kstr.txt

5)cat /home/stud/'Рабочий стол'/kstr.txt

mv - перемешение

rm - удалить(каталог можно удалить только с -r, тк там внутри файлы)

ls - просмотреть

-r - рекурсия

cat - чтение

mkdir - создает директорию

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/32f62c50-9ae3-49f3-a5da-902b903286d3)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/3633b550-9b0c-406e-a67c-e97038c350c8)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/d8c9f8c8-9e8c-40de-9d21-26a449eea8c4)


![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/09fb680c-fbee-43cc-91d6-f0d999fcb950)

**Папка (directory)**

1)mkdir /home/stud/ kss

2)mkdir /home/stud/kss  home/stud/ksss

3)touch home/stud/ksss/mayy

4)touch home/stud/ksss

5)rm -r home/stud/ksss



![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/e2cfc2a9-22ac-4713-86a1-82495556fb3a)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/11db9fb9-6543-46fe-8cae-0e326efc143b)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/8cb1a16b-d7da-4337-bef4-3926148c068f)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/b8aeb9e3-cd79-4a7d-907b-079dc7470915)




**Устройства:**

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/95c89a47-8905-4f0e-a0d5-81b9623ce820)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/c9963467-c973-4846-adef-61923c1c1541)

c - cимвольные

блочные (флешки)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/4e7e40a9-a0d6-40d4-b54b-e1b20af511b3)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/170975f4-2881-495b-81b4-03baacb94913)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/e02e582d-1780-4660-8f70-861824570a24)

b - блок

Пытались создать флешку


Файлам присваиваются уникальные номера - inod, посмотреть команды - ls-i1

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/d0d920a0-1b77-42a9-a0df-6c928dba226a)

Жесткие ссылки имеют тот же номер что и файл и это можно использовать, чтобы найти все жесткие ссылки

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/e19ef99e-e730-41f0-b905-2a582fd11189)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/de71be1d-d2e4-4ae2-a15e-cd430431df02)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/a0da9c60-d9ba-4e4b-b146-4d325b48d8ee)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/4e1af64a-ac5b-4f08-b386-ec6d417ea1b2)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/94900693-12da-4265-bad9-ab2f9c2fc5c1)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/a1087f1e-8835-4a0d-ad9c-90edef1f8ea7)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/4bd85d49-9a2e-4c92-92ab-d0adf70e7807)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/216aa7d5-e409-4fe6-a0f1-a1b7a83ac36f)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/dd73b383-4177-47da-aafa-b5e8c8a42dc3)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/80499013-1a20-42f1-8b1e-f2d23764d498)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/d21b5656-6b88-4277-804e-688f1a708f72)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/54c60c21-bcf3-4bb3-9060-b80bd7ed6881)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/49fbf817-cfb0-428d-8c50-6b47a0b97008)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/97699767-6c2f-455d-9209-bd43c98db249)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/e42f112e-44f6-4bb9-92bb-639080492be8)



# ЛК3 19.02.24 Скрипт на создание и удаление пользователя



Имя пользователя/Место под пароль/Номер пользователя/Номер группы пользователя/название группы/Домашняя директория пользователя/Терминал пользователя 

Создаем пользователя
![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/9509879a-508e-411b-a86b-6d45293c538d)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/88a2410c-eba2-4153-8db1-5c5859987748)

Переключаем ползователя

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/fe232fcf-6260-48d0-9df9-b99f86a70008)

Создаем пароль для нашего пользователя

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/7e16de77-8a0e-4455-b4da-c9da5218a35b)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/5eccff94-37df-4d46-93d5-85d0516f21db)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/0db71c7b-6898-436f-9e3b-e9a76b06de1e)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/c7baa1f1-c565-4a0c-8ebd-19c40dbbca18)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/b6414a5c-e5fc-4aeb-9ce6-3006eecf98c2)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/45714afb-bd26-43e9-8258-9353002b4fe9)


Создаем пользователя в нашем новом пользователе при помощи сркипта

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/c2aa04e9-8daa-475f-b426-de265914d520)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/8923ea80-fb63-4ae7-a238-a60bc7b28843)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/861e9a25-1bb5-4d5f-8625-e3f700e9649d)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/8b35d716-c84f-41fa-93f4-a6fb654df710)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/4a87bb05-ac7f-42af-9781-c9c960fd84df)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/9d795aa5-49a5-45ac-8e41-93934fe7d832)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/e9e07fee-bfcf-4ef0-876a-a43798d016c2)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/f6e092f9-0c95-4150-9977-665963df7337)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/b163db35-a0e5-4634-af8d-038872ef5e4d)



# ЛК4 04.03.24 Структура памяти процесса 

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/aec0d04a-b2b9-427e-9c95-3aaa6b4e44b3)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/96e1a93f-619a-4cbe-9165-1b536f677ac6)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/3d72fb07-40fe-4e8c-9a1a-dc6941bdc39f)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/83fa1a6e-158b-4b61-99b6-a40c601a9361)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/8195be3b-28b1-40e5-82d6-74b5cab05dcc)

PID - номера поцесса (на винде в диспетчере задач смотрим)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/a98b6c71-f6e3-49a9-a88f-eff1070a8ab1)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/31f6269f-0329-4084-af26-75ad2d1f2919)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/de6ff1c7-40f9-44b6-8501-7daace1c8be8)

Память запоняется в определенные ячейки(разные)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/77589065-f271-45c2-80c9-b8910c4c9bdb)

Библиотеки:

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/d7c43635-31bb-42a3-ad8f-5b207be28f54)

Область данных и текст(код):

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/671f9271-4922-4e5b-bf3b-8dc128da2fb1)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/e306985d-2954-4fdf-b994-f1946d369af3)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/11877113-51d8-42d3-9d61-af83a04bb345)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/3a0573ff-f1df-473f-b76d-3c9910715277)


![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/5dfad536-aac3-48f9-83d8-7ec9cd48b3cb)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/bb3ce670-1313-4614-9a99-fd8fda8a88bd)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/8ea8d718-5952-484d-9ccd-63b8be08fdc8)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/28587c19-1c89-468b-bcac-743190dad1f6)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/048b9bfa-6c7b-4ddd-ac0a-0ff3129a0a6f)

# ЛК5 11.03.24. Потоки в БД

**Атрибуты процесса:**

1. PID - уникальный идентификатор 
2. Адресация областей памяти процесса
3. fd - открытые файловые дескрипторы (терминал или файлы которые используют процессы)
4. Обработчики сигналов процесса (введение запроса пользователя)
5. Код выхода (Ctr+C, Ctr+Z, exit, Программа все выполнила)
6. Рабочий каталог (Папка рабочего процесса - proc)
7. Переменные окружения (Комментарии)
8. Состояние процесса
9. Аппаратный контекст (То что определяься компьютером)

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/e815d141-22b8-4194-8846-42907d916483)
 
**Состяние процесса**

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/cd5cfc1d-92a2-4d4c-adda-6682f0b6ca21)

Первый процесс init

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/b4c88025-e5b0-40ad-a4b1-5cb31145a0e2)

Сотояние процессса: Ready

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/a6bc2b96-59c6-4d75-9f24-6de5f4d4096c)

Сотояние процессса: Running

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/1b1ec900-73c3-4f8d-bd09-b78aafa0e492)

Сотояние процессса: Sleeping

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/4a0d4a9b-e92e-4ab4-ae4c-96ed0ee0206e)

Сотояние процессса: Zombie

![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/bad08e57-3053-4899-9b6d-647ba97e5947)

**Смерть процесса**
   
   - exit() или kill() - останавливает поцесс
  
   - После завершения род.процессса, дочерний переходит либо в состояние зомби, либо к другому род.процссу
  



![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/7bae567d-c610-4bb2-a5aa-5cfecf5dd6e0)

**Сигналы**
   
![image](https://github.com/b6e6b6r6a/6_Semestr-/assets/113089548/642f829f-25bc-4247-b937-39563f9f4031)

Прерывание: 

- Аппаратные - все проблемы с устройством
  
- Программные - все что с программмами

Планировщик процессов:

- Вытесняющая(планировщик сам)
  
- Кооперативная(пк сам выбирает) многозадачность







https://docs.google.com/document/d/1z27O5xLblWKjIxcXRZnbd1smm-oYa8bt/edit








