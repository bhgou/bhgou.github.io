---
title: Резюме
---
# Швачкин Никита
**Middle Unity Developer**

- **Телефон:** +7 (952) 406-72-02
- **Email:** bratihkintime@gmail.com
- **GitHub:** [github.com/bhgou](https://github.com/bhgou)
- **Telegram:** [@bhgou](https://t.me/bhgou)
- **Дата рождения:** 12 декабря 2007
- **Гражданство:** Россия
- **Занятость:** полная / проектная, удалёнка / офис, без командировок

---

## Опыт работы

### Unity-разработчик (PerseiLine)
*2023 — 2024 (1 год)*

Разработка и поддержка AR-приложения на Unity для iOS и Android.

- Проектирование и реализация UI/UX по макетам Figma
- Интеграция image tracking / image recognition с динамической загрузкой 3D-моделей
- Оптимизация производительности и подготовка приложения к production-релизу (App Store, Google Play)
- Работа с AR SDK, доработка функционала под конкретные задачи

**Стек:** C#, Unity, AR SDK (image tracking), Figma

Ссылка: [PerseiLine в RuStore](https://www.rustore.ru/catalog/app/com.VinchyAR.PerseiLine)

### C#/.NET-разработчик (ACRELIS)
*С 2025 — настоящее время*

#### 1. Разработка AI-промптов (Prompt Engineering)
- Проектирование и отладка промптов для LLM-моделей (классификация / генерация / валидация) с повышением точности на 30%
- Система рейтингования ответов (0-5 баллов): релевантность, следование инструкциям, проверка QR-кода, грамматика, спам-детекция
- Реализация очереди офлайн-событий (OfflineEventQueue) для гарантированной доставки аналитики при отсутствии сети
- Защита от инъекций — экранирование промптов от SQL-подобных инъекций и XSS-атак, валидация через Firestore security rules
- Unit-тесты для движка промптов (PromptValidationEngineTests, ScoreCalculatorTests)

#### 2. Работа с данными и архитектура (DataLoader)
- DataLoadManager для асинхронной загрузки данных с кэшированием и фолбэком на Firebase Firestore
- Внедрение Dependency Injection через Zenject (DataLoaderInstaller, ProfileService, SceneDataInitializer)
- Типизированные модели данных Firestore в C#-структурах с доменной валидацией (TimeWindow, Enums)
- CRUD-операции для игроков в реальном времени с синхронизацией состояний

#### 3. UI и управление активностями
- UiController для единого управления через UI Toolkit с поддержкой вложенных состояний
- ActivityDataManager для управления стеком активностей с историей навигации
- Визуальные переходы между активностями с плавной анимацией
- Интеграция кастомных элементов: GPS-индикатор, QR-сканер, взаимодействие с картой

#### 4. Модульность и безопасность
- Модульная архитектура (asmdef-сборки: Training, DataLoader, Prompt, Core)
- Интеграция Firebase Authentication (анонимный, email, телефон)
- Локализация текста (TextLocalizationService) для мультиязычности
- Серверная валидация (FraudDetector, HaversineCalculator, HmacVerifier) с HMAC-подписью

#### 5. Достижения и UI-компоненты
- Система достижений (AchievementView) с анимацией и визуальной обратной связью
- Кастомный рендеринг прогресса на кривой Безье с градиентом, анимацией и маскированием
- Система тегов с категоризацией и фильтрацией

**Стек:** C#, Unity, Firebase (Firestore, Authentication), Zenject (DI), Git, Unit-тестирование (NUnit)

---

## Pet-проекты

### Horror Game (в разработке)
*Жанр: хоррор от первого лица, ПК*

- [github.com/bhgou/horrorGame](https://github.com/bhgou/horrorGame)
- Оптимизация FPS с 45 до 70 на среднем железе: Occlusion Culling, lightmapping, Static Batching
- Отказ от GameObject.Find в Update, пулинг объектов, замена Update на события
- Переход на URP с кастомными VFX
- Анимации через DOTween

### TBKK
*3D Puzzle-Adventure*

- [github.com/bhgou/TBKK](https://github.com/bhgou/TBKK)
- Click-to-move, инвентарь, AI машин

---

## Навыки

### Основные
C#, Unity, Zenject (DI), Firebase (Firestore, Authentication), Git, Unit-тестирование, URP (VFX, кастомные шейдеры), DOTween, Occlusion Culling, Static Batching, AR SDK, Android, iOS

### Знаком
Addressables, ASP.NET, ASP.NET MVC, SQL, PostgreSQL, JavaScript, HTML, Python

---

## Образование
Техникум / Колледж (специальность, год)

---

## Языки
- **Русский** — родной
- **Английский** — B1 (средний)
