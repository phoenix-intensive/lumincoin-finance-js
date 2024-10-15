## Lumincoin Finance — платформа для отслеживания доходов и расходов

## Обзор проекта

## Lumincoin Finance — это одностраничное приложение (SPA), созданное с использованием JavaScript, которое помогает пользователям эффективно отслеживать свои доходы и расходы. Платформа позволяет пользователям создавать и удалять категории доходов и расходов, предоставляя четкий обзор своего финансового состояния с помощью динамических диаграмм.
## Функции
* Управление категориями : пользователи могут создавать, обновлять и удалять категории как доходов, так и расходов.
* Визуализация данных : приложение включает интерактивные диаграммы (на основе библиотеки Charts.js), которые визуализируют распределение доходов и расходов с течением времени.
* Маршрутизация : как современное SPA, Lumincoin Finance использует маршрутизацию JavaScript для бесперебойной навигации между различными частями приложения без полной перезагрузки страницы.
* Удобный интерфейс : платформа имеет понятный и интуитивно понятный интерфейс на базе Bootstrap для адаптивного дизайна и простоты использования.
## Используемые технологии
* JavaScript (ES6+) : основная функциональность платформы, реализующая логику управления доходами/расходами, маршрутизацией и интерактивностью.
* Chart.js : для построения динамических диаграмм, отображающих данные о доходах и расходах.
* Bootstrap 5 : для адаптивного дизайна, гарантирующего, что приложение будет хорошо выглядеть на всех устройствах.
* Webpack : используется как модульный упаковщик для управления активами и оптимизации структуры проекта.
* Node.js и npm : для управления зависимостями проекта и упрощения процессов разработки.



## Установка и запуск проекта

Этот проект состоит из двух частей: backend и frontend. Следуйте инструкциям ниже, чтобы клонировать и развернуть проект в своей IDE.

### 1. Клонирование проекта

1. Скопируйте ссылку на репозиторий:  
   ```bash
   https://github.com/phoenix-intensive/Lumincoin-Finance-JS.git
   ```

2. Откройте вашу IDE (например, WebStorm или VS Code) и выполните следующие шаги:
   - Создайте новый проект.
   - Выберите пункт "Project from Version Control" (или аналогичный в вашей IDE).
   - Вставьте скопированную ссылку в поле URL.
   - Клонируйте репозиторий на ваш локальный компьютер.

### 2. Установка и запуск backend

1. Откройте терминал в вашей IDE.
2. Перейдите в папку backend:
   ```bash
   cd backend
   ```
3. Установите все необходимые пакеты:
   ```bash
   npm install
   ```
4. Запустите сервер:
   ```bash
   npm start
   ```

### 3. Установка и запуск frontend

1. Откройте новый терминал в IDE.
2. Перейдите в папку frontend:
   ```bash
   cd frontend
   ```
3. Установите все необходимые пакеты:
   ```bash
   npm install
   ```
4. Запустите проект:
   ```bash
   npm run dev
   ```

Теперь ваш проект развернут и доступен для просмотра

### Примечания

- **Node.js**: убедитесь, что на вашем компьютере установлена актуальная версия Node.js и npm.
- **Frontend** будет доступен по адресу, указанному в терминале после выполнения команды `npm run dev`.
- **Backend** работает по адресу, указанному в терминале после выполнения команды `npm start`.
