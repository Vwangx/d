# d
# Как перенести шаблон проекта себе на ПК

KVS(Kernel Video Sharing) - универсальный конструктор медийных сайтов.

Наш шаблон вы можете найти на нашем gitlab.

>  gitlab.mbunity.io/kernel-video-sharing/kvs-default-video-satellites
{.is-info}

Что бы склонировать себе шаблон на ПК нужно выполнить пару простых действий.

Для начала вам нужен ключ самого проекта с типом подключением `SSH` на `gitlab`.
(.https://github.com/Vwangx/d/blob/master/screenshot_from_2020-07-22_14-07-04.png)

После того как мы взяли нужный нам ключ с помощью простой команды утилиты `git` мы клонируем проект себе на ПК.

> git clone git@gitlab.mbunity.io:kernel-video-sharing/YOUR_PROJECT.git ./Desktop/project-1/kvs/
{.is-info}

![screenshot_from_2020-07-22_14-12-39.png](/rusuchka_white_background.jpg)


Обратите внимание на путь.Для удобной разработки ,и просто для удобного хранения файлов шаблон нужно склонировать именно в папку `kvs`. В ней находится всё,что касается разработки.

Теперь у вас на ПК есть шаблон, можно приступить к запуску проекта для разработки.
