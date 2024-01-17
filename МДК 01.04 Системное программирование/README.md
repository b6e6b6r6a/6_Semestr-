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
