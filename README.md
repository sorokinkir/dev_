# dev_
Окружение для малой команды разработчиков


# Уставновка и запуск
1. mkdir -p -m 750 youtrack

2. chown -R 13001:13001 youtrack

3. sudo docker network create --subnet 172.20.0.0/24 git_net

4. sudo docker-compose up -d
