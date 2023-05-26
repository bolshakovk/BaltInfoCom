# BaltInfoCom

1) Добавлены контейнеры кассандры(1, 2, 3)
2) Добавлена сеть для связи кластеров кассандры networks
3) Установлены отдельные адреса для каждого кластера

Как запускал:

<b>Я поднимал в WSL2</b>

1) Поднять контейнеры docker-compose up -d
2) Можно проверить лог контейнера, например docker logs cassandra1
3) Проверка сети docker exec -it cassandra1 nodetool status

Полезности: 

[Полезный бложик](https://blog.digitalis.io/containerized-cassandra-cluster-for-local-testing-60d24d70dcc4)

[полезный стак оверфлоу](https://stackoverflow.com/questions/43754095/how-to-join-the-default-bridge-network-with-docker-compose-v2)
