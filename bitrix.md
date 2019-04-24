# Материалы по 1C-Bitrix

## Общая информация об 1C-Bitrix

### Документация

- Стандартная документация: [https://dev.1c-bitrix.ru/api_help/](https://dev.1c-bitrix.ru/api_help/)
- Документация по ядру d7: [https://dev.1c-bitrix.ru/api_d7/](https://dev.1c-bitrix.ru/api_d7/)

### Обучение

- [Быстрый старт разработчика](https://dev.1c-bitrix.ru/learning/course/index.php?COURSE_ID=95)
- [Интеграция дизайна и настройка платформы](https://academy.1c-bitrix.ru/education/index.php?login=yes&COURSE_ID=65&LESSON_ID=5872&)
- [Разработчик Bitrix Framework](https://dev.1c-bitrix.ru/learning/course/index.php?COURSE_ID=43)
- [Администратор. Базовый](https://dev.1c-bitrix.ru/learning/course/index.php?COURSE_ID=35)<span style="text-decoration:underline;"> </span>
- [Администратор. Модули](https://dev.1c-bitrix.ru/learning/course/index.php?COURSE_ID=41)
- [Администратор. Бизнес](https://dev.1c-bitrix.ru/learning/course/index.php?COURSE_ID=42)
- [Все курсы](https://dev.1c-bitrix.ru/learning/index.php)

#### Видеокурсы

- [Видео-курсы для разработчиков](https://dev.1c-bitrix.ru/learning/dev.php)
- [Разработка на D7](https://www.youtube.com/watch?v=0HOUlRoNu0I&list=PLzPivwyXljVWyIN-AuV1j-9XHR_b4mf9k)
- [Основные технологии](https://www.youtube.com/watch?v=1QoYv_R7Iv0&index=1&list=PLzPivwyXljVVXMH5VNSfSocd1P33kJZVj)
- [Интеграция и Настройка](https://www.youtube.com/watch?v=rO-jU41kcb4&list=PLzPivwyXljVVcsFkOan-ZpyjnjU3SDUgg) 2

### Тестирование

- В каждом из представленных выше курсов можно пройти бесплатное тестирование.
- Можно пройти официальную [сертификацию разработчиков](https://dev.1c-bitrix.ru/learning/certification.php) в Битриксе.

## Первый уровень

### Материалы

- [Быстрый старт разработчика](https://dev.1c-bitrix.ru/learning/course/index.php?COURSE_ID=95)
- [Простой пример создания компонента](https://dev.1c-bitrix.ru/learning/course/index.php?COURSE_ID=43&LESSON_ID=2305)
- [Компоненты](https://dev.1c-bitrix.ru/learning/course/index.php?COURSE_ID=43&CHAPTER_ID=04565)
- [Плейлист](https://www.youtube.com/playlist?list=PLzPivwyXljVV100GMKcQAekdThrN2z6DQ).

Первоначально смотреть видео до 2.15. Видео 2.9 в конце плейлиста...

### Система контроля версий и Bitrix

Исключаем папки и файлы:
- /bitrix
- /upload
- .htaccess
- .htsecure

## Общая архитектура 1C-Bitrix
- Ядро папка bitrix
- Папка upload
- Папка local
    - components
    - modules
    - php_interface
        - [init.php](https://dev.1c-bitrix.ru/learning/course/index.php?COURSE_ID=43&LESSON_ID=2916) (нельзя редактировать из веб интерфейса)
    - templates
- Работа с БД
    - dbconn.php 
    - .settings.php 
- Модули
- Компоненты
    - component.php (class.php)
    - template.php
    - script.js
    - style.css
    - result_modifier.php
    - component_epilog.php
    - после копирования шаблона компонента удаляем все лишнее
- [Шаблоны сайта](https://www.youtube.com/watch?v=JJ5wbD0x65A&index=10&list=PLzPivwyXljVVcsFkOan-ZpyjnjU3SDUgg)
- urlrewrite.php
- .htaccess
- .access.php
- .top.menu.php
- .section.php
- 404.php
- [Порядок выполнения страницы](https://dev.1c-bitrix.ru/api_help/main/general/page/pageplan.php)
- [Свойства страницы](https://www.youtube.com/watch?v=-E-5-uvIDbo&list=PLzPivwyXljVVcsFkOan-ZpyjnjU3SDUgg&index=7)
- Свойства раздела
- [Меню](https://www.youtube.com/watch?v=_p_6FhOoKXE&index=8&list=PLzPivwyXljVVcsFkOan-ZpyjnjU3SDUgg)


## Контент

- [Инфоблоки](https://www.youtube.com/watch?v=NQAvk1mrlKA&list=PLzPivwyXljVVcsFkOan-ZpyjnjU3SDUgg&index=24)
    - добавление свойств (имена свойств капсом)
- Highload блоки
- Таблицы БД

## Поиск


## Кеширование


## Почта

- Типы почтовых событий
- Почтовые шаблоны
- Отправка сообщений

## Администрирование

- Точка входа /bitrix/admin/
- Администрирование пользователей
    - Группы пользователей
    - Авторизация под пользователем
- Проверка настроек
- Панель производительности
- Резервное копирование
- Обновление

[Установка Bitrix](https://www.youtube.com/watch?v=6hdVFIYflSE&index=2&list=PLzPivwyXljVVcsFkOan-ZpyjnjU3SDUgg)

Разделение функционала на компоненты

[Многоуровневое меню](https://www.youtube.com/watch?v=DGgIPif5S38&index=16&list=PLzPivwyXljVVcsFkOan-ZpyjnjU3SDUgg)

Включаемые области

[Разделение страниц на компоненты](https://www.youtube.com/watch?v=dKWnC0eNlOw&index=25&list=PLzPivwyXljVVcsFkOan-ZpyjnjU3SDUgg)


## Второй уровень

### Создание собственных компонентов

- Кастомизация компонентов
- Собственные компоненты
- Агенты
- События
- Объединение файлов
- Composer
- Композитный сайт
- Монитор производительности
- Скорость работы сайта

- [Виртуальная машина](https://www.youtube.com/watch?v=pl0Y4-MeUDI&list=PLzPivwyXljVVcsFkOan-ZpyjnjU3SDUgg&index=3)
- [Цепочка навигации](https://www.youtube.com/watch?v=GF0giteL58k&index=18&list=PLzPivwyXljVVcsFkOan-ZpyjnjU3SDUgg)
- [Авторизация](https://www.youtube.com/watch?v=rDVt10-v3Cw&index=19&list=PLzPivwyXljVVcsFkOan-ZpyjnjU3SDUgg)


## Экзамены Bitrix

- Общая информация о процессе: [https://academy.1c-bitrix.ru/certification/examination-metod.php](https://academy.1c-bitrix.ru/certification/examination-metod.php)

- Материалы для подготовки: [https://academy.1c-bitrix.ru/certification/exams.php](https://academy.1c-bitrix.ru/certification/exams.php)

Там же есть ссылки на примеры заданий, варианты билетов, курсы, которые помогут пройти. Самое основное там - это ссылка на курс [http://academy.1c-bitrix.ru/training/course/5862/](http://academy.1c-bitrix.ru/training/course/5862/), который крайне рекомендуется для прохождения, так как в нём повествование идёт по всем темам, задаваемым в экзамене.

**ОЧЕНЬ** рекомендую при подготовке к экзамену потратить время на просмотр разбора типовых ошибок на вебинаре (но уже после того, как будут пройдены все подготовительные процедуры), запись вебинара находится здесь: [http://dev.1c-bitrix.ru/community/blogs/dev_bx/how-to-successfully-pass-the-exam-no-1.php](http://dev.1c-bitrix.ru/community/blogs/dev_bx/how-to-successfully-pass-the-exam-no-1.php)

После всех этих подготовок нужно будет попробовать порешать задания.

По ссылкам в левом меню можно скачать виртуальную машину с окружением, идентичным тому, которое будет на экзамене. Лучше пробовать именно там, чтобы окружение на экзамене не вводило в ступор и не отнимало лишнего времени.