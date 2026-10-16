# boot88

**Веб-разработчик · PHP / Laravel · React / JavaScript**

Разрабатываю и дорабатываю веб-приложения: внутренние сервисы, каталоги, сайты услуг и инструменты автоматизации. В проектах работаю с серверной логикой, базами данных, интерфейсами и интеграциями.

## Выбранные проекты

| Проект | Что реализовано | Технологии |
| --- | --- | --- |
| **[Service Desk / React_Suz](https://github.com/boot88/React_Suz/tree/dev/test-stand)** | Учёт заявок, роли сотрудников и администраторов, корпоративный чат, база знаний, статистика и резервные копии | React, Node.js, Express, MySQL, Docker, GitHub Actions |
| **[TechZone / InternetShop](https://github.com/boot88/InternetShop)** | Каталог электроники, категории, фильтры, карточки товаров, авторизация и корзина | PHP, Laravel, Eloquent, Blade, JavaScript |
| **[Website Auditor](https://github.com/boot88/auditor)** | Прототип аудита страницы: браузерный рендер, извлечение данных, фоновая задача и рекомендации через API языковой модели | Laravel, Playwright, очереди, OpenAI API |
| **[DreamDigit](https://github.com/boot88/DreamDigital)** | Сайт студии с услугами, кейсами и формой обращения с доставкой в email и MAX | Laravel, Blade, JavaScript, Vite |
| **[Sandblasting](https://github.com/boot88/Sandblasting)** | Сайт услуг с галереей, заявкой с фотографией и уведомлениями в email и мессенджеры | Laravel, Blade, JavaScript, HTTP API |
| **[ZuluGIS Demo Lab](https://github.com/boot88/ZuluGis)** | Карта инфраструктуры: поиск, фильтры, измерения, GeoJSON и подключение WFS | React, Leaflet, React Leaflet, GeoJSON |

У **InternetShop** реализованы каталог и корзина; оформление заказа и личный кабинет остаются в разработке. **Website Auditor** требует настройки внешнего API и браузерного окружения.

## Что посмотреть в первую очередь

- **Полный стек и сопровождение приложения:** [актуальная ветка React_Suz](https://github.com/boot88/React_Suz/tree/dev/test-stand), [серверные маршруты](https://github.com/boot88/React_Suz/tree/dev/test-stand/server/routes), [автоматические проверки](https://github.com/boot88/React_Suz/actions/workflows/ci.yml).
- **PHP и работа с данными:** [контроллер каталога](https://github.com/boot88/InternetShop/blob/master/app/Http/Controllers/ProductController.php), [модель товара](https://github.com/boot88/InternetShop/blob/master/app/Models/Product.php), [фоновая задача аудита](https://github.com/boot88/auditor/blob/main/app/Jobs/RunSiteAuditJob.php).
- **Интерфейсы и интеграции:** [компонент карты](https://github.com/boot88/ZuluGis/blob/main/src/components/MapComponent.js), [обработка заявки](https://github.com/boot88/DreamDigital/blob/main/app/Http/Controllers/ContactController.php), [тест отправки заявки с фото](https://github.com/boot88/Sandblasting/blob/main/tests/Feature/LeadSubmissionTest.php).

## Технологии в репозиториях

**Сервер:** PHP, Laravel, Node.js, Express, SQL, MySQL, Eloquent, HTTP API, очереди задач.

**Интерфейсы:** JavaScript, React, Vue, Blade, HTML/CSS, адаптивная вёрстка, Leaflet.

**Разработка и сопровождение:** Git, Docker, GitHub Actions, автоматические тесты, миграции, резервное копирование.

## Другие примеры

- [VideoHosting](https://github.com/boot88/VideoHosting) — видеокаталог на Laravel с категориями, просмотром, комментариями и лайками.
- [Web Alarm Clock](https://github.com/boot88/blog) — веб-будильник с расписанием, днями недели и звуковыми сигналами.
- [Art Gallery](https://github.com/boot88/banki-shop-test) — демонстрационная витрина картин на Vue с поиском, модальным просмотром и локальным состоянием корзины.

Инструкции, особенности запуска и текущие ограничения находятся в README соответствующих проектов.
