#### Сборка образа:
docker build . --tag=homework

#### Запуск контейнера:
docker run --name=homework_d -d -p 8768:80 homework

