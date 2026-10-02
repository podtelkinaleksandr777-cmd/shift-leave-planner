cat > README.md << 'EOF'
# 🗓 Shift & Leave Planner

Веб-приложение для планирования графиков смен и отпусков персонала.

![Status](https://img.shields.io/badge/status-in%20development-yellow)
![License](https://img.shields.io/badge/license-MIT-blue)
![Node](https://img.shields.io/badge/node-20.x-green)

## 📋 О проекте

**Shift & Leave Planner** — это система для автоматизации процесса составления рабочих графиков и управления отпусками сотрудников.

### Возможности

- 📅 Создание и редактирование графиков смен
- 🏖 Учёт отпусков, отгулов и больничных
- ⚠️ Автоматическая проверка пересечений и переработок
- 👥 Ролевая модель: администратор, менеджер, сотрудник
- 📝 Подача и согласование заявок на отпуск
- 🔔 Уведомления о предстоящих сменах
- 📊 Дашборд с аналитикой загрузки персонала
- 📤 Экспорт графиков в Excel/PDF

## 🛠 Технологический стек

### Backend
- **Node.js 20 LTS** — среда выполнения
- **Express.js 4** — веб-фреймворк
- **Sequelize** — ORM для работы с MySQL
- **MySQL 8.0** — база данных
- **JWT + bcrypt** — аутентификация
- **Joi** — валидация данных
- **Swagger** — документация API

### Frontend
- **React 18** — UI-библиотека
- **Vite** — сборщик
- **Material UI** — компоненты
- **Axios** — HTTP-клиент

### DevOps
- **Docker + docker-compose** — контейнеризация
- **GitHub Actions** — CI/CD
- **ESLint + Prettier** — линтинг и форматирование

## 🚀 Быстрый старт

1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/username/shift-leave-planner.git
   cd shift-leave-planner

