# Планировании автоматизации тестирования

## Перечень автоматизируемых сценариев :
1. ### Тесты UI
#### Позитивные / негативные сценарии:
* Покупка тура по определенной цене по средствам дебетовой карты(валидные / невалидные значения);
* Покупака тура по определенной цене с помощью  уникальной технологии: выдача кредита по данным банковской карты (валидные /невалидные значения).
### Перечень тестируемых данных карт предоставлен в файле data.json:
 * 4444 4444 4444 4441,
status: APPROVED
  
* 4444 4444 4444 4442,
status: DECLINED.

2. ### Тестируемые Базы данных:
* MySQL
* PostgreSQL
## Перечень используемых инструментов 
1. IntelliJ IDEA - программа, в которой пишется код, автотесты.
2. Gradle - система автоматической сборки внутри IntelliJ IDEA.
3. JUnit 5 -  библиотека для модульного тестирования программного обеспечения на языке Java.
4. Selenide - фреймворк для автоматизированного тестирования веб-приложений.
5. Gradle/Allure/Report Portal -для генерации отчетов, а так же используем для наглядного изображения прохождения тестов и ошибок.
6. Faker - генерация пользовательских данных при тестировании.
7. Docker Compose -готовый контейнер с приложениями базы данных, позволяющий очень быстро развёртывать приложения, отличающиеся сложной архитектурой.
8. Git/GitHub - система контроля версий для хранения информации.

## Перечень и описание возможных рисков при автоматизации
* Сложности с поиском верных локаторов;
* Интеграция двух СУБД (MySQL, Postgres), возможны проблемы.
* Сложность сравнения результатов (ожидаемый/фактический) в связи с отсутствием ТЗ.

## Интервальная оценка с учётом рисков (в часах)
* Подготовка окружения, развертывание БД - 16 часов (при отсутствии дополнительных рисков);
* Написание автотестов, тестирование и отладка автотестов - 24 часа (при отсутствии дополнительных рисков);
* Формирование и анализ отчетов - 8 часов.

## План сдачи работ (когда будут авто-тесты, результаты их прогона и отчёт по автоматизации)

* 31.08.2021 - 15.09.2021  - настройка окружения, написание и отладка автотестов, тестирование;
* 16.09.2021 - 28.09.2021 - подготовка отчетной документации.