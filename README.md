<div align="center">

<img src="./PlasmaBladeRunner_1.gif" width="100%" alt="Blade Runner" />

<h1>Daniil Rybiakov</h1>

<p><b>Java Backend Engineer</b> · Java 17/21 · Spring Boot · микросервисы · DDD</p>

<a href="https://daniil2022ri.github.io/Portfolio_Backend/">
  <img src="https://img.shields.io/badge/PORTFOLIO-ff9d00?style=for-the-badge&labelColor=0b0b13&logo=githubpages&logoColor=ff9d00" alt="Portfolio" />
</a>
<a href="https://github.com/Daniil2022Ri/Bank-DDD">
  <img src="https://img.shields.io/badge/FLAGSHIP-Bank--DDD-25e7ff?style=for-the-badge&labelColor=0b0b13&logo=spring&logoColor=25e7ff" alt="Bank-DDD" />
</a>
<a href="mailto:hhffcgubv@gmail.com">
  <img src="https://img.shields.io/badge/EMAIL-hhffcgubv%40gmail.com-9a9ab0?style=for-the-badge&labelColor=0b0b13&logo=gmail&logoColor=white" alt="Email" />
</a>
<a href="https://t.me/danilRyDeveloperFullStack">
  <img src="https://img.shields.io/badge/TELEGRAM-25e7ff?style=for-the-badge&labelColor=0b0b13&logo=telegram&logoColor=25e7ff" alt="Telegram" />
</a>

<br><br>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=3400&pause=900&color=FF9D00&center=true&vCenter=true&width=720&lines=Java+17%2F21+%7C+Spring+Boot;Microservices+%7C+DDD+%7C+JWT;207+tests+%7C+80.3%25+coverage;AOP+audit+%7C+CI+%7C+Docker+Compose" alt="Java Backend Engineer" />

<br>

<a href="#user-content-ru"><b>🇷🇺 Русский</b></a> &nbsp;·&nbsp; <a href="#user-content-en"><b>🇬🇧 English</b></a>

</div>

---

<a id="ru" name="ru"></a>

## 🇷🇺 Русский

### 01 // О себе

Пишу backend на Java 17/21 и Spring. Начинаю не с контроллеров, а с границ домена и схемы данных: сначала bounded contexts, миграции и контракты API, потом код. Люблю проекты, которые поднимаются одной командой и проверяют качество автоматически — тестами, Checkstyle, JaCoCo-гейтом и CI.

Главный проект — **Bank-DDD**: банковский backend из семи сервисов, собранный по Liquibase-схеме, с JWT, сквозным AOP-аудитом, 207 тестами и покрытием 80,3%. Технический разбор каждого проекта — в [портфолио](https://daniil2022ri.github.io/Portfolio_Backend/).

<div align="center">

| 7 | 207 | 80,3% | 12 |
|:---:|:---:|:---:|:---:|
| микросервисов<br>в Bank-DDD | backend-тестов | покрытие строк | проектов<br>в портфолио |

</div>

### 02 // Флагманский кейс — Bank-DDD

Банковский backend не монолитом, а набором сервисов: у каждого своя схема в PostgreSQL, свой REST API и свои тесты.

```text
authorization  :8087   JWT · роли
profile        :8089   паспорт · адреса
account        :8085   банковские счета
transfer       :8092   переводы
antifraud      :8086   риск-скоринг
history        :8088   агрегация аудита
public-info    :8091   отделения · банкоматы
```

- **Границы домена** — 7 bounded contexts, у каждого свой порт, своя схема и свой набор тестов.
- **Аудит как срез** — Spring AOP пишет старое и новое состояние сущности в JSON, `history` агрегирует.
- **Качество процессом** — 207 backend-тестов и 39 тестов фронта, JaCoCo-гейт 60%, Checkstyle без нарушений, CI из двух job.
- **Воспроизводимость** — `docker compose up --build` поднимает PostgreSQL, 7 сервисов и React-кабинет.

[**Код и README →**](https://github.com/Daniil2022Ri/Bank-DDD) · [**Техпаспорт на сайте →**](https://daniil2022ri.github.io/Portfolio_Backend/#flagship)

### 03 // Проекты

**Backend**

| Проект | Что внутри | Стек |
|:--|:--|:--|
| **[Bank-DDD](https://github.com/Daniil2022Ri/Bank-DDD)** | 7 микросервисов, JWT, AOP-аудит, 207 тестов, CI | `Java 17` `Spring Boot 3.2` `PostgreSQL` `Liquibase` |
| **[PaymentService](https://github.com/Daniil2022Ri/PaymentService)** | Асинхронные платежи, кэш баланса, JWT, 80%+ покрытия | `Java 17` `Spring Boot 3.3` `RabbitMQ` `Redis` |
| **[AIAssistantBackend](https://github.com/Daniil2022Ri/AIAssistantBackend)** | Реактивный AI-backend, circuit breaker, контекст в Redis | `Java 25` `WebFlux` `R2DBC` `Resilience4j` |
| **[Bank_DDD_Antifraund](https://github.com/Daniil2022Ri/Bank_DDD_Antifraund)** | Первая версия банка: 7 сервисов, AOP-аудит, Liquibase | `Java 17` `Spring Boot` `Spring AOP` `Docker` |
| **[SpringSecurity_V2](https://github.com/Daniil2022Ri/SpringSercutiry_V2)** | RBAC, Spring Security изнутри, админ-панель | `Spring Security` `JPA` `Thymeleaf` `BCrypt` |
| **[MVC_Hibernate](https://github.com/Daniil2022Ri/MVC_Hibernate)** | Классический MVC: controller → service → DAO → JPA | `Spring MVC` `Hibernate` `Thymeleaf` |

**Frontend и Android**

| Проект | Что внутри | Стек |
|:--|:--|:--|
| **[TechStore](https://github.com/Daniil2022Ri/Portfolio_Backend/tree/main/Normal_verstka_Web/Site_Gadjet_Store)** | SPA-магазин: фильтры, корзина, адаптивная сетка | `Vue 3` `Composition API` `CSS Grid` |
| **[KickStore](https://github.com/Daniil2022Ri/Portfolio_Backend/tree/main/Normal_verstka_Web/Site_shooth_Store)** | Витрина с параллаксом и избранным в localStorage | `React 18` `Hooks` `CSS Animations` |
| **[Wanderlust](https://github.com/Daniil2022Ri/Portfolio_Backend/tree/main/Normal_verstka_Web/Site_Travel_Store)** | Туристический портал, lazy loading, модальные окна | `React 18` `CSS Grid` `Performance` |
| **[WeatherApp](https://github.com/Daniil2022Ri/Portfolio_Backend/tree/main/Web_API_sites/Weather_monitoring_site)** | Погода в реальном времени, 50+ городов, 7 дней | `React` `Open-Meteo API` |
| **[CurrencyHub](https://github.com/Daniil2022Ri/Portfolio_Backend/tree/main/Web_API_sites/CurrencyHub)** | Курсы валют, конвертер и кэш запросов | `React 18` `ExchangeRate API` |
| **[FlashLingua](https://github.com/Daniil2022Ri/AndroidApp_EnglishCard)** | Карточки английских слов, TTS, офлайн-хранение | `Kotlin` `Jetpack Compose` `Room` `MVVM` |

### 04 // Стек

| Слой | Технологии |
|:--|:--|
| **Backend** | `Java 17/21` `Spring Boot` `Spring Cloud` `Spring Security` `Kotlin` `REST API` |
| **Данные и сообщения** | `PostgreSQL` `Redis` `Apache Kafka` `Hibernate/JPA` `Liquibase` `Flyway` |
| **Архитектура** | `Microservices` `DDD` `CQRS` `Event-Driven` `Bounded contexts` |
| **Frontend** | `React 18` `Vue 3` `TypeScript` `CSS Grid` `Vite` `Accessibility` |
| **Android** | `Kotlin` `Jetpack Compose` `Room` `MVVM` `Coroutines` `Flow` |
| **Качество и DevOps** | `JUnit 5` `Mockito` `MockMvc` `JaCoCo` `Checkstyle` `Docker` `GitHub Actions` |

### 05 // Принципы

- **Границы прежде кода.** Сначала bounded contexts и схема БД, потом сервисы. Разнести домены позже дороже, чем сразу.
- **Тесты как контракт.** Unit на бизнес-логику, MockMvc на API, интеграционные на реальные миграции. Покрытие — гейт, а не отчёт.
- **Наблюдаемость и аудит.** Сквозной AOP-аудит, Actuator на отдельном порту, Swagger у каждого сервиса.
- **Воспроизводимость.** Docker Compose, multi-stage Dockerfile, CI на каждый push. Проект должен запускаться, а не «у меня работало».

### 06 // Контакты

- **Портфолио:** [daniil2022ri.github.io/Portfolio_Backend](https://daniil2022ri.github.io/Portfolio_Backend/)
- **Email:** [hhffcgubv@gmail.com](mailto:hhffcgubv@gmail.com)
- **Telegram:** [@danilRyDeveloperFullStack](https://t.me/danilRyDeveloperFullStack)
- **GitHub:** [github.com/Daniil2022Ri](https://github.com/Daniil2022Ri)

---

<a id="en" name="en"></a>

## 🇬🇧 English

### 01 // About

I build backend systems in Java 17/21 and Spring. I start with domain boundaries and the data schema, not controllers: bounded contexts, migrations and API contracts first, code second. I like projects that start with one command and check their own quality — tests, Checkstyle, a JaCoCo gate and CI.

The flagship project is **Bank-DDD**: a seven-service banking backend designed from a Liquibase schema, with JWT, cross-cutting AOP audit, 207 tests and 80.3% line coverage. Every project has a technical breakdown in the [portfolio](https://daniil2022ri.github.io/Portfolio_Backend/).

<div align="center">

| 7 | 207 | 80.3% | 12 |
|:---:|:---:|:---:|:---:|
| microservices<br>in Bank-DDD | backend tests | line coverage | projects<br>in the portfolio |

</div>

### 02 // Flagship case — Bank-DDD

A banking backend as a set of services, not a monolith: each one has its own PostgreSQL schema, REST API and tests.

```text
authorization  :8087   JWT · roles
profile        :8089   passport · addresses
account        :8085   bank accounts
transfer       :8092   transfers
antifraud      :8086   risk scoring
history        :8088   audit aggregation
public-info    :8091   branches · ATMs
```

- **Domain boundaries** — 7 bounded contexts, each with its own port, schema and test suite.
- **Audit as a slice** — Spring AOP stores the old and new entity state as JSON, `history` aggregates it.
- **Quality as process** — 207 backend tests and 39 frontend tests, a 60% JaCoCo gate, zero Checkstyle violations, a two-job CI.
- **Reproducibility** — `docker compose up --build` starts PostgreSQL, all 7 services and the React UI.

[**Code and README →**](https://github.com/Daniil2022Ri/Bank-DDD) · [**Tech dossier on the site →**](https://daniil2022ri.github.io/Portfolio_Backend/#flagship)

### 03 // Projects

**Backend**

| Project | What is inside | Stack |
|:--|:--|:--|
| **[Bank-DDD](https://github.com/Daniil2022Ri/Bank-DDD)** | 7 microservices, JWT, AOP audit, 207 tests, CI | `Java 17` `Spring Boot 3.2` `PostgreSQL` `Liquibase` |
| **[PaymentService](https://github.com/Daniil2022Ri/PaymentService)** | Async payments, balance cache, JWT, 80%+ coverage | `Java 17` `Spring Boot 3.3` `RabbitMQ` `Redis` |
| **[AIAssistantBackend](https://github.com/Daniil2022Ri/AIAssistantBackend)** | Reactive AI backend, circuit breaker, Redis context | `Java 25` `WebFlux` `R2DBC` `Resilience4j` |
| **[Bank_DDD_Antifraund](https://github.com/Daniil2022Ri/Bank_DDD_Antifraund)** | First bank iteration: 7 services, AOP audit, Liquibase | `Java 17` `Spring Boot` `Spring AOP` `Docker` |
| **[SpringSecurity_V2](https://github.com/Daniil2022Ri/SpringSercutiry_V2)** | RBAC, Spring Security internals, admin panel | `Spring Security` `JPA` `Thymeleaf` `BCrypt` |
| **[MVC_Hibernate](https://github.com/Daniil2022Ri/MVC_Hibernate)** | Classic MVC: controller → service → DAO → JPA | `Spring MVC` `Hibernate` `Thymeleaf` |

**Frontend & Android**

| Project | What is inside | Stack |
|:--|:--|:--|
| **[TechStore](https://github.com/Daniil2022Ri/Portfolio_Backend/tree/main/Normal_verstka_Web/Site_Gadjet_Store)** | Store SPA: filters, cart, responsive grid | `Vue 3` `Composition API` `CSS Grid` |
| **[KickStore](https://github.com/Daniil2022Ri/Portfolio_Backend/tree/main/Normal_verstka_Web/Site_shooth_Store)** | Storefront with parallax and localStorage favourites | `React 18` `Hooks` `CSS Animations` |
| **[Wanderlust](https://github.com/Daniil2022Ri/Portfolio_Backend/tree/main/Normal_verstka_Web/Site_Travel_Store)** | Travel portal, lazy loading, modals | `React 18` `CSS Grid` `Performance` |
| **[WeatherApp](https://github.com/Daniil2022Ri/Portfolio_Backend/tree/main/Web_API_sites/Weather_monitoring_site)** | Real-time weather, 50+ cities, 7 days | `React` `Open-Meteo API` |
| **[CurrencyHub](https://github.com/Daniil2022Ri/Portfolio_Backend/tree/main/Web_API_sites/CurrencyHub)** | Exchange rates, converter and request caching | `React 18` `ExchangeRate API` |
| **[FlashLingua](https://github.com/Daniil2022Ri/AndroidApp_EnglishCard)** | English flashcards, TTS, offline storage | `Kotlin` `Jetpack Compose` `Room` `MVVM` |

### 04 // Stack

| Layer | Technologies |
|:--|:--|
| **Backend** | `Java 17/21` `Spring Boot` `Spring Cloud` `Spring Security` `Kotlin` `REST API` |
| **Data & messaging** | `PostgreSQL` `Redis` `Apache Kafka` `Hibernate/JPA` `Liquibase` `Flyway` |
| **Architecture** | `Microservices` `DDD` `CQRS` `Event-Driven` `Bounded contexts` |
| **Frontend** | `React 18` `Vue 3` `TypeScript` `CSS Grid` `Vite` `Accessibility` |
| **Android** | `Kotlin` `Jetpack Compose` `Room` `MVVM` `Coroutines` `Flow` |
| **Quality & DevOps** | `JUnit 5` `Mockito` `MockMvc` `JaCoCo` `Checkstyle` `Docker` `GitHub Actions` |

### 05 // Principles

- **Boundaries before code.** Bounded contexts and the DB schema first, services second. Splitting domains later costs more.
- **Tests as a contract.** Unit tests for business logic, MockMvc for API, integration tests against real migrations. Coverage is a gate, not a report.
- **Observability & audit.** Cross-cutting AOP audit, Actuator on a separate port, Swagger for every service.
- **Reproducibility.** Docker Compose, multi-stage Dockerfile, CI on every push. A project must start, not “worked on my machine”.

### 06 // Contact

- **Portfolio:** [daniil2022ri.github.io/Portfolio_Backend](https://daniil2022ri.github.io/Portfolio_Backend/)
- **Email:** [hhffcgubv@gmail.com](mailto:hhffcgubv@gmail.com)
- **Telegram:** [@danilRyDeveloperFullStack](https://t.me/danilRyDeveloperFullStack)
- **GitHub:** [github.com/Daniil2022Ri](https://github.com/Daniil2022Ri)

---

<img src="./PlasmaBladeRunner_1.gif" width="100%" alt="Blade Runner" />

<div align="center">
<sub>Микросервисы · DDD · тесты · CI &nbsp;|&nbsp; Microservices · DDD · tests · CI</sub>
</div>
