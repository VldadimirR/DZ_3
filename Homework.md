# Знакомство с Git

>Git Это Распределённая система управления версиями. Проект был создан Линусом Торвальдсом для управления разработкой ядра Linux, первая версия выпущена 7 апреля 2005 года. На сегодняшний день его поддерживает Джунио Хамано.

Git прост в освоении и занимает совсем немного места при молниеносной производительности. Он превосходит инструменты SCM, такие как Subversion, CVS, Perforce и ClearCase, благодаря таким функциям, как дешевое локальное ветвление, удобные промежуточные области и несколько рабочих процессов.

## Имя пользователя

Первое, что вам следует сделать после установки Git — указать ваше имя и адрес электронной почты. Это важно, потому что каждый коммит в Git содержит эту информацию, и она включена в коммиты, передаваемые вами, и не может быть далее изменена:

$ git config --global user.name "John Doe"

$ git config --global user.email johndoe@example.com

Опять же, если указана опция --global, то эти настройки достаточно сделать только один раз, поскольку в этом случае Git будет использовать эти данные для всего, что вы делаете в этой системе. Если для каких-то отдельных проектов вы хотите указать другое имя или электронную почту, можно выполнить эту же команду без параметра --global в каталоге с нужным проектом.

## Создание git репозитория

Обычно вы получаете репозиторий Git одним из двух способов:
1.	Вы можете взять локальный каталог, который в настоящее время не находится под версионным контролем, и превратить его в репозиторий Git, либо
2.	Вы можете клонировать существующий репозиторий Git из любого места.
В обоих случаях вы получите готовый к работе Git репозиторий на вашем компьютере.


**Основные команды в Git:**

* git init - Инициализация репозитория

* git add . - Добавление всех файлов

* git commit -m "" - Создание коммита в репозитории

* git log - История коммитов

* git diff - Просмотр изменений до коммита

* git checkout "" - Переход к нужному коммиту

* git checkout master - Переход к поледней ветке коммита

* git status - показывает состояние файлов в рабочем каталоге

* git clean - команда git clean используется для удаления мусора из рабочего каталога. Это могут быть результаты сборки проекта или файлы конфликтов слияний.

* git cd - переход в другую директорию

**Основные команды при работе с ветками:**

1. git branch - просмотр текущей ветки

2. git branch "название ветки" - создание новой ветки

3. git checkout "название ветки" - переход к другой ветке

4. git branch -d "название ветки" - удалить ветку

5. git merge "название ветки" - слияние веток

**Основные команды при работе с удаленными репоизотрями githab**

* git clone - создание копии удаленного репозитория 

* git pull - эта команда позволяет скачать все 
из текущего репозитория и автоматически
сделать merge с нашей версией

* git push - эта команда позволяет отправить нашу
версию репозитория на внешний
репозиторий. ТРЕБУЕТ АВТОРИЗАЦИИ 
на внешнем репозитории.


![Изображение git](https://static.tildacdn.info/tild3662-3561-4133-b036-376130613930/noroot.png)

Cсылка на сайт git: https://git-scm.com/

## **Заключение**

>В данном файле описаны первыые шаги по работе с git, также основные команды необходимые для использования git. Была проведена работа с ссылками, цитатами, изображениями, различными шрифтами, и других возможностях расширения md.
