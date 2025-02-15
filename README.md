# service
1.Создаем докер образ, выгружаем его в докер хаб.
2.Клонируем себе этот репозиторий git clone https://github.com/Zerg-lfa/service.git
3.В файле auto-docker-lift.yml в блоке vars меняем переменные под свой докер образ
4.В файле hosts.ini меняем ip на ip сервера
5 Запускаем, создастся systemd и запустится докер образ.
