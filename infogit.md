# Основные команды Git:


* **git init** - инициализация локального репозитория

* **git status** - получить информацию от git о его текущем состоянии
***
* **git add path** - добавить файл или файлы к следующему коммиту

    *git add .* - добавляет все файлы в проекте в отслеживание
***
* **git commit -m "message"** - создание коммита

    *git commit -am "message"* - git add + git commit, работает только после ручного добавления в отслеживание через add "path" или add .
***
* **git log** - выводит на экран историю всех коммитов с их хеш-кодами (если не хватает места переходит в режим просмотра и пишет END в конце, чтобы снова работало надо нажать q)

* **git checkout** - переход от одного коммита к другому, нужно использовать первые 4 цифры хеш-кода после checkout

* **git checkout master** - вернуться к актуальному состоянию и продолжить работать, если не работает надо попробовать git checkout main

* **git diff** - показывает разницу между текущим файлом (несохраненным) и закоммиченным

>Git - это лучшее, что случалось в жизни! 


# Шрифты и заголовки

* \# - Большой заголовок (1)
* \## - Заголовок поменьше (2)
* Всего заголовков 6, чем меньше \#, тем больше текст
* \###### - Заголовок 6 (выглядит вот так) 
    ###### заголовок 6

***
* \* - *делает курсив*
* \** - **делает текст жирным**
* \~~ -  ~~делает текст зачеркнутым~~

## Примечания
* Для того, чтобы добавить картинку или ссылку, пробелов ставить не надо, иначе не будет работать
* Для того, чтобы работали символы заголовков, надо ставить пробел, иначе будет выглядеть вот так:
*тут должен быть пункт списка



# Слияние веток:

* **git branch** - посмотреть список веток в репозитории

* **git branch название ветки** – создать новую ветку

* **git checkout название ветки** – переход к другой ветке

* **git merge название ветки** - слить данную ветку с master

* **git branch -d название ветки** – удалить ветку

* **git log --graph** - визуализирует коммиты

* **git checkout -b название ветки** – Создание и переход в новую ветку

* **git commit --amend -m "text"** - изменение текста последнего коммита

# Удаленные репозитории :

* **git clone url-адрес репозитория** - клонирование внешнего репозитория на локальный ПК

* **git pull** - получение изменений и слияние с локальной версией

* **git push** - отправляет локальную версию репозитория на внешний

    Для того, чтобы git push работала нормально git должен знать адрес удаленного репозитория и быть авторизован на внесенеи изменений в удаленном репозитории 
