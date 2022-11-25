Конфиги:
![img](https://github.com/AzarnoyKir/10-01KA/blob/f31efac68ad2074a452097b0af9449b6cef3dd78/img/CONFIG.png)

Статусы:
![img](https://github.com/AzarnoyKir/10-01KA/blob/f31efac68ad2074a452097b0af9449b6cef3dd78/img/STATUS.png)

команда ip address:
![img](https://github.com/AzarnoyKir/10-01KA/blob/f31efac68ad2074a452097b0af9449b6cef3dd78/img/IP%20ADDRESS.png)

Тут я решил выкинуть финт ушами. Отрубив вначале мастер попытался поймать момент "переключения". Тщетно.
На скрине я пингую с винды где стоит ВБ с виртуалками VIP. Вначале отключил master (systemctl stop keepalived) - эффекта никакого
Далее я отключил и backup - VIP пропал. Затем я влючил backup и спустя заметный миг всё снова поднялось.
![img](https://github.com/AzarnoyKir/10-01KA/blob/f31efac68ad2074a452097b0af9449b6cef3dd78/img/WINDOWS%20PING.png)

В общем сплошное колдунство.
![img](https://github.com/AzarnoyKir/10-01KA/blob/920e990af24ba64bd29590b2d6092ca1e8ad01e5/img/magic.png)
