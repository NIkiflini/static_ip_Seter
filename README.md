# Хомяк сделал
<p align="center">
  <a href="https://github.com/NIkiflini">
    <img src="https://i3.wp.com/opis-cdn.tinkoffjournal.ru/mercury/in-sad-hamster.mbfryzbsrhv6..jpg?ssl=1">
  </a>
</p>

## Network_setup.sh

скрипт создан для изменения IP.

## Функционал 

- выбираешь интерфейса
- вводишь IP
- жмаешь y(да) .... нет шутки не будет
- результат: отвал интернета

## Запуск

Скачивай файл

накидывайте права:
```
chmod a+x network_setup.sh
```
и неееет Sora меня не учил давать права 777 ))))

после этого запускай скрипт:
```
./network_setup.sh
```

## Если не разобрался в моем интуитивно понятном управлении
вот так жмаешь
```
sudo ./network_setap.sh
```
получаешь:
```
[sudo] password for USER: (свой pASSword пишешь сюда) 
Текушие настройки:
Interface: lo:, IP Address: 127.0.0.1/8
Interface: eth0:, IP Address: 10.0.2.15/24
Interface: docker0:, IP Address: 172.17.0.1/16
```
```
Выбери что менять (e.g. eth0, wlan0, etc.): (тут вводишь какой интерфейс менять будешь)
Новый IP намаляй: (новый IP пишешь)
тебе оно надо? - Interface поменять в нем IP на Твой новый IP? (y/n): y(да) n(нет)
Ну все интернета не будет твой IP-  (твой новый IP)
```
