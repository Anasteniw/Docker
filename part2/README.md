#### Сборка образа:
docker build ./ --tag=my_homework:1.0.

#### Запуск контейнера:
docker run --name homework_stock -d -p 8769:6060 my_homework:1.0.