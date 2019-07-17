1) Правый роутер
Сохранил его текущие настройки(не были сохранены > терялись при перезагрузке)
copy running-config startup-config

2) При симуляции переполняется буфер:
PT > preferences > Miscellaneous > Simulation- Buffer behavior > Buffer filtered events only

3) Проверил интерфейсы на всех устройствах 
port: ON, Bandwidth: auto, Duplex: auto

4) Проверил что для компьютерах в левой подсети выбрано GateWay/DNS/IPv4 через DHCP

5) В провой подсети для компьютеров назначил IP и gateway.

5) У левого роутера порт Internet (0/0) подключил к свичу, который идет к правому роутеру.



