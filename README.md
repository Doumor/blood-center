# blood-center / Центр крови

## About

I do not yet know how to name this repository properly, but in general terms it will be an information site with a personal account and a simple messenger.
<br><br>
Я пока не знаю как нормально назвать этот репозиторий, но в общих словах это будет информационный сайт с личным кабинетом и простым мессенджером.

## Functionality / Функциональность

The difference will be that it has no extra functionality as in the CMS. There will be functionality for authorization through social networks.
<br><br>
Отличаться он будет тем, что в нём нет лишнего функционала как в CMS. Будет функционал для авторизации через соц.сети.

## How do I run this? / Как это запустить?

Actually, you can't yet, but when the code is written it will be easy. You need a virtual machine or server on Windows, Linux or *BSD, as well as Bash or Zsh(Or something that can run a Bash script...), node, npm, mongoDB(Can be on another server) installed.
<br><br>
Собственно, пока никак, но когда код будет написан это будет просто. Потребуется витуальная машина или сервер на Windows, Linux или *BSD, а так же установленный там Bash или Zsh(Или что-то что может запустить Bash скрипт..), node, npm, mongoDB(Можно на другом сервере).

<br><br>
When all this is done, you need to run the following commands:
<br><br>
Когда всё это сделано, то нужно запустить следующие команды:
```
Clone this repository / Клонируем этот репозиторий
# git clone https://github.com/Doumor/blood-center

Go to the project directory / Переходим в директорию проекта
# cd blood-center

Make the script executable / Делаем исполняемым скрипт
# sudo chmod +x gen.sh

Run the config generation script and answer the questions from it
Запускаем скрипт генерации конфига и отвечаем на вопросы из него
# ./gen.sh

Start it up / Запускаем
# node index
```

## Anything else? / Что-то ещё?

After that you will need to configure the site manually. Change the design, understand what needs to be added to it. This is a task for your programmer. By the way, I can do it myself if you pay me for it. In any case, if I do not get money from it, I will abandon the development.
<br><br>
После этого нужно будет настроить сайт уже вручную. Изменить дизайн, понять то, что необходимо в него добавить. Это задача для вашего программиста. К слому, я могу это сделать сам, если вы заплатите мне за это. В любом случае, если я не буду получать денег с этого, то я заброшу разработку.

## License / Лицензия

It will be FLOSS, but a lot of the code will be from my other proprietary projects. There is also a chance that there will be code from an open mobile client of one of these projects, but it just hasn't even started yet. In any case, it will most likely be BSD license.
<br><br>
Это будет FLOSS, но много кода будет из других моих проприетарных проектов. Есть так же вероятность, что будет код из открытого мобильного клиента одного из таких проектов, но только он пока даже не начат. В любом случае, скорее всего это будет лицензия BSD.
