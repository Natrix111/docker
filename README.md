# Docker

# Инструкция

1. Склонируйте репозиторий:

```bash
   git clone https://github.com/Natrix111/docker.git
```

2. Перейдите в директорию проекта:

```bash
    cd .../docker
```

3. Для запуска окружения введите следующие команды в терминал:


Для запуска окружения разработки:
```bash
      cd dev
      Создайте файл .env на основе .env.example
      docker-compose up --build
```
Для запуска окружения продакшина:
```bash
      cd prod
      Создайте файл .env на основе .env.example
      docker-compose up --build
```

