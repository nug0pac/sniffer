# Анализатор трафика
## Реализованные функции
* Выбор сетевого интерфейса для сниффинга
* Выбор фильтра для анализа трафика
* Вывод информации, содержащейся в пакетах, в читабельном виде
* Вывод таблицы с IP и MAC адресами устройств в сети
* ARP-спуфинг
  * Для его корректной работы необходимо выполнить следующие команды:
  ```
  sudo -i
  echo 1 > /proc/sys/net/ipv4/ip_forward
  ```
* Обнаружение спуфинга
* Сохранение пакетов в .pcap файл 

## Пример работы
![](gif/howitworks-1.gif)
