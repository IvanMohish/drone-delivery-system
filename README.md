# Drone Delivery Management System

## Опис проєкту
Система керування дроном-кур'єром для автоматизації доставки товарів від складу до клієнта.

---

## Основний функціонал
- управління доставкою;
- контроль маршруту дрона;
- перевірка заряду батареї;
- моніторинг статусу доставки;
- автоматична корекція маршруту.

---

## Структура проєкту

```bash
project/
│
├── README.md
├── Dockerfile
├── .github/
│   └── workflows/
│       └── main.yml
├── src/
├── tests/
└── docs/
```

---

## Запуск проєкту

```bash
docker build -t drone-system .
docker run -p 8080:8080 drone-system
```

---

## GitHub Projects
Для управління задачами використовується Kanban-дошка GitHub Projects.

---

## Labels
- Bug
- Critical
- Enhancement
- Task
- Navigation
- Battery
- Delivery

---

## Status Badges

![Build](https://img.shields.io/badge/build-passing-brightgreen)

---

## Автор
Студент: Могіш Іван
Група: ІСТ-31
Варіант: 12
