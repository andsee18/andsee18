# Andrey Afanasev | Java Backend Engineer
### **Backend developer**

<p align="left">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
</p>

---

## Обо мне
Я бэкенд-разработчик и студент **МТУСИ**. Специализируюсь на создании отказоустойчивых сервисов на **Java**. Мой основной фокус - чистая архитектура, оптимизация производительности и создание архитектуры. 

Имею опыт работы над реальными проектами.

---

## Технологический стек

| Категория | Технологии |
| :--- | :--- |
| **Языки** | **Java 21**, Python 3.12, SQL |
| **Бэкенд** | **Spring Boot 3.4**, FastAPI, Hibernate, Spring Data JPA |
| **Инфраструктура** | **Docker & Compose**, Nginx, GitHub Actions, Flyway, Maven |
| **Данные и Кэш** | **PostgreSQL**, Redis, Caffeine, MinIO S3 |
| **Тестирование** | JUnit 5, Mockito, Pytest, Testcontainers |

---

## Проекты

### Data Sync Service (Automation & Data Consistency)
*Разработка для сети магазинов "Traffic"*
- **Stack:** Java 21, Spring Boot 3, PostgreSQL.
- **Задача:** Реализовал сервис синхронизации транзакционных данных между кассовыми узлами и центральной БД.
- **Результат:** Внедрил механизм **идемпотентности**, исключив дублирование проводок. Оптимизировал SQL-запросы, что ускорило генерацию аналитических отчетов.

### Book Exchange Platform
*Платформа для обмена книгами*
- **Безопасность:** Реализовал Stateless-аутентификацию (**JWT + HttpOnly Cookies**) и ролевую модель доступа (RBAC).
- **Качество:** Централизованная обработка ошибок через `@ControllerAdvice` и транзакционная целостность при обмене данными.

### Smart Dining System (Lead Developer)
*Система управления нагрузкой в реальном времени*
- **Оптимизация:** Интегрировал синхронные драйверы БД через `run_in_threadpool`, предотвратив блокировку Event Loop в асинхронном FastAPI приложении.
- **Данные:** Спроектировал механизмы агрегации пиковых нагрузок с использованием стратегий `ON CONFLICT`.

---

## Образование и детали
- **МТУСИ:** Программная инженерия.
- **Локация:** Москва / Химки.
- **Английский:** B1 (чтение технической документации).

---

## 📫 Контакты
<p align="left">
<a href="https://t.me/afanasefff_a" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/telegram.svg" alt="afanasefff_a" height="30" width="40" /></a>
<a href="mailto:krllx6@mail.ru"><img align="center" src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" height="24" /></a>
</p>

---
*Built with care, Java 21 and a bit of caffeine.*
