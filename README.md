# Домашнее задание к занятию "`8_01_Git_HW`" - `Makarov-Denis`


### Инструкция по выполнению домашнего задания

   1. Сделайте `fork` данного репозитория к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/git-hw или  https://github.com/имя-вашего-репозитория/7-1-ansible-hw).
   2. Выполните клонирование данного репозитория к себе на ПК с помощью команды `git clone`.
   3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
      - впишите вверху название занятия и вашу фамилию и имя
      - в каждом задании добавьте решение в требуемом виде (текст/код/скриншоты/ссылка)
      - для корректного добавления скриншотов воспользуйтесь [инструкцией "Как вставить скриншот в шаблон с решением](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md)
      - при оформлении используйте возможности языка разметки md (коротко об этом можно посмотреть в [инструкции  по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md))
   4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`);
   5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
   6. Любые вопросы по выполнению заданий спрашивайте в чате учебной группы и/или в разделе “Вопросы по заданию” в личном кабинете.
   
Желаем успехов в выполнении домашнего задания!
   
### Дополнительные материалы, которые могут быть полезны для выполнения задания

1. [Руководство по оформлению Markdown файлов](https://gist.github.com/Jekins/2bf2d0638163f1294637#Code)

### Задание 1

**Что нужно сделать:**

1. Зарегистрируйте аккаунт на [GitHub](https://github.com/).
1. Создайте публичный репозиторий. Обязательно поставьте галочку в поле «Initialize this repository with a README».
2. Склонируйте репозиторий, используя https протокол `git clone ...`.
3. Перейдите в каталог с клоном репозитория.
1. Произведите первоначальную настройку Git, указав своё настоящее имя и email: `git config --global user.name` и `git config --global user.email johndoe@example.com`.
1. Выполните команду `git status` и запомните результат.
1. Отредактируйте файл README.md любым удобным способом, переведя файл в состояние Modified.
1. Ещё раз выполните `git status` и продолжайте проверять вывод этой команды после каждого следующего шага.
1. Посмотрите изменения в файле README.md, выполнив команды `git diff` и `git diff --staged`.
1. Переведите файл в состояние staged или, как говорят, добавьте файл в коммит, командой `git add README.md`.
1. Ещё раз выполните команды `git diff` и `git diff --staged`.
1. Теперь можно сделать коммит `git commit -m 'First commit'`.
1. Сделайте `git push origin master`.

В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.

Ответ:
https://github.com/Makarov-Denis/my-first-github/commit/bc73d71530cc7ceeb2f4afdf8ac76c3b764bff6c

### Задание 2

**Что нужно сделать:**

1. Создайте файл .gitignore (обратите внимание на точку в начале файла) и проверьте его статус сразу после создания.
1. Добавьте файл .gitignore в следующий коммит `git add...`.
1. Напишите правила в этом файле, чтобы игнорировать любые файлы `.pyc`, а также все файлы в директории `cache`.
1. Сделайте коммит и пуш.

В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.
Ответ:
https://github.com/Makarov-Denis/my-first-github/commit/76d5f986d429af81aced2a5162d4244422e1422e

### Задание 3

**Что нужно сделать:**

1. Создайте новую ветку dev и переключитесь на неё.
1. Создайте файл test.sh с произвольным содержимым.
1. Сделайте несколько коммитов и пушей, имитируя активную работу над этим файлом.
1. Сделайте мердж этой ветки в основную. Сначала нужно переключиться на неё, а потом вызывать `git merge`.
1. Сделайте коммит и пуш.

В качестве ответа прикрепите ссылку на граф коммитов https://github.com/ваш-логин/ваш-репозиторий/network в ваш md-файл с решением.

Ответ:
https://github.com/Makarov-Denis/my-first-github/network


---

## Дополнительные задания* (со звёздочкой)

Их выполнение необязательное и не влияет на получение зачёта по домашнему заданию. Можете их решить, если хотите лучше разобраться в материале.

---
### Задание 4*

Сэмулируем конфликт. Перед выполнением изучите с [документацию](https://git-scm.com/book/ru/v2/%D0%98%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D1%8B-Git-%D0%9F%D1%80%D0%BE%D0%B4%D0%B2%D0%B8%D0%BD%D1%83%D1%82%D0%BE%D0%B5-%D1%81%D0%BB%D0%B8%D1%8F%D0%BD%D0%B8%D0%B5).

**Что нужно сделать:**

1. Создайте ветку conflict и переключитесь на неё.
2. Внесите изменения в файл test.sh. 
3. Сделайте коммит и пуш.
4. Переключитесь на основную ветку.
5. Измените ту же самую строчку в файле test.sh.
6. Сделайте коммит и пуш.
7. Сделайте мердж ветки conflict в основную ветку и решите конфликт так, чтобы в результате в файле оказался код из ветки conflict.

В качестве ответа на задание прикрепите ссылку на граф коммитов https://github.com/ваш-логин/ваш-репозиторий/network в ваш md-файл с решением.

