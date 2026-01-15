# 1. Создайте локальную структуру
mkdir petrushka-zelenaya-assignment
cd petrushka-zelenaya-assignment

# 2. Инициализируйте git репозиторий
git init

# 3. Создайте структуру папок и файлов как выше

# 4. Добавьте файлы в git
git add .

# 5. Сделайте коммит
git commit -m "Initial commit: Solutions for Petrushka Zelenaya assignment"

# 6. Создайте репозиторий на GitHub
# Перейдите на https://github.com/new
# Название: petrushka-zelenaya-assignment
# Описание: Test assignment solutions for System Analyst position

# 7. Привяжите удаленный репозиторий
git remote add origin https://github.com/ваш-username/petrushka-zelenaya-assignment.git

# 8. Запушьте код
git push -u origin main

# 9. (Опционально) Добавьте визуализацию
# Создайте файл assignment-3-architecture/architecture-diagram.mmd
# Подготовка к собеседованию

## Технические вопросы

### 1. Требования
- **Виды требований от заказчика:** бизнес-требования, пользовательские истории, нефункциональные требования
- **Виды требований разработчикам:** функциональные спецификации, API контракты, архитектурные решения

### 2. Базы данных
- **ER диаграмма:** сущности, атрибуты, связи (1:1, 1:N, M:N)
- **Основы SQL:** SELECT, JOIN, GROUP BY, индексы, транзакции

### 3. Архитектура
- **Frontend vs Backend:** клиентская/серверная части
- **HTTP vs REST:** протокол vs архитектурный стиль
- **Микросервисы vs Монолит:** trade-offs в масштабировании и сложности

### 4. Инфраструктура
- **Работа интернета:** DNS, TCP/IP, HTTP запрос, рендеринг
- **Message Queues:** Kafka (лог-ориентированный) vs RabbitMQ (брокер сообщений)
- **Backend for Frontend:** паттерн для оптимизации API под конкретный клиент

## Бизнес-кейсы

1. Как бы вы приоритизировали исправления в ТЗ корзины?
2. Какие метрики для оценки успешности push-уведомлений?
3. Как обеспечить доставку критических уведомлений (отмена заказа)?
