[category]: <> (About)
[date]: <> (2024/10/13)
[title]: <> (Как сделать такое же)

На самом деле сложного нет вообще ничего, если поискать в интернетах - я думаю можно найт и другие шаблоны. Мне понравился этот именно из-за его минималистичности. Хотя есть немного небольшая претензия - слишком мелкий шрифт в мобильной версии, надо будет покопаться - поискать где подкрутить эту настроечку...

## 1. GitHub

Регистрируемся и клонируем к себе в аккаунт репозиторий [отсюда](https://github.com/vbuterin/blogmaker)

## 2. Fleek.xyz

1. Создаем аккаунт

2. Идем в **Hosting -> Add New -> Deploy my site**<br>
На самом деле на fleek жеж я и нашла этот шаблон, но почему-то, когда я пыталась сразу построить из него сайт - скрипт ни в какую не хотел работать, возможно это чисто мой глюк и можно выбрать сразу вариант **use a template**

3. Слева выбираете GItHub, коннектите аккаунт. Дальше важное: надо выбрать в advansed options не корневой репозиторий, а папку **site** в нем. 

4. Все. Нажимаете **deploy** и ждете несколько минут. Сайт готов. У него будет рандомное имя, которое можно изменить в настройках.

## 3. GitHub desktop

Качаем, устанавливаем, коннектим

## 4. Visual Studio Code

Качаем, устанавливаем, клонируем репозиторий (весь, не только папку site) себе на компьютер.

Собственно описание как делать посты в файле README.md. Пишем текст в любом редакторе в формате markdown, закидываем в папку posts. Запускаем скрипт publish.py c параметром либо posts/* либо с posts/название-вашей-заметки.md

Через GitHub desktop закидываем изменения на сайт и через минуту любуемся готовым постом.

Медиа файлы я кладу на тот же fleek, в раздел storage, но наверное можно и на github, если там не гигабайты

***

Все, мои файлы, мои тексты теперь лежат у меня, не у LiveJournal, не у телеграмма или еще где-то. Даже если github когда-нибудь сломается - все это будет довольно легко за пару кликов перенести на любой другой хостинг.