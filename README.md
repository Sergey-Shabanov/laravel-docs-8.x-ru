## Документация Laravel 8.x

Вольный перевод [репозитория](https://github.com/laravel/docs/tree/8.x) документации **laravel/docs** ветка 8.x на русский язык.

Ссылка на [лицензию](https://github.com/laravel/docs/blob/8.x/license.md) оригинала документации **laravel/docs**.

Актуализация с основным репозиторием документации Laravel осуществляется не реже одного раза в неделю. Орфографические, пунктуационные и грубые смысловые ошибки исправляются по мере их выявления. Ошибки в примерах кода текущей документации не исправляются прежде, чем это будет зафиксировано в основном репозитории, так как это может повлечь за собой смещение или изменение количества строк в файлах документации.

### Содержание документации

> Перед чтением документации ознакомьтесь с [соглашением по переводу](#dictionary).

Разделы, помеченные галочками, уже имеют актуализированные переводы **полностью на русском языке**.

- ## Пролог
    - [x] [Примечания к релизу](./docs/releases.md)
    - [x] [Руководство по обновлению](./docs/upgrade.md)
    - [x] [Рекомендации по участию](./docs/contributions.md)
- ## Начало
    - [x] [Установка](./docs/installation.md)
    - [x] [Конфигурирование](./docs/configuration.md)
    - [x] [Структура каталогов](./docs/structure.md)
    - [x] [Стартовые комплекты](./docs/starter-kits.md)
    - [x] [Развертывание](./docs/deployment.md)
- ## Архитектурные концепции
    - [x] [Жизненный цикл запроса](./docs/lifecycle.md)
    - [x] [Контейнер служб](./docs/container.md)
    - [x] [Поставщики служб](./docs/providers.md)
    - [x] [Фасады](./docs/facades.md)
- ## Основы
    - [x] [Маршрутизация](./docs/routing.md)
    - [x] [Посредники](./docs/middleware.md)
    - [x] [Предотвращение атак CSRF](./docs/csrf.md)
    - [x] [Контроллеры](./docs/controllers.md)
    - [x] [HTTP-запросы](./docs/requests.md)
    - [x] [HTTP-ответы](./docs/responses.md)
    - [x] [HTML-шаблоны](./docs/views.md)
    - [x] [Шаблонизатор Blade](./docs/blade.md)
    - [x] [Генерация URL-адресов](./docs/urls.md)
    - [x] [Сессия HTTP](./docs/session.md)
    - [x] [Валидация](./docs/validation.md)
    - [x] [Обработка ошибок](./docs/errors.md)
    - [x] [Логирование](./docs/logging.md)
- ## Углубленное изучение
    - [x] [Консоль Artisan](./docs/artisan.md)
    - [x] [Трансляция событий](./docs/broadcasting.md)
    - [x] [Кеш приложения](./docs/cache.md)
    - [x] [Коллекции](./docs/collections.md)
    - [x] [Компиляция исходников (Mix)](./docs/mix.md)
    - [x] [Контракты](./docs/contracts.md)
    - [x] [События](./docs/events.md)
    - [x] [Файловое хранилище](./docs/filesystem.md)
    - [x] [Глобальные помощники](./docs/helpers.md)
    - [x] [HTTP-клиент](./docs/http-client.md)
    - [x] [Локализация](./docs/localization.md)
    - [x] [Почтовые отправления](./docs/mail.md)
    - [x] [Уведомления](./docs/notifications.md)
    - [x] [Разработка пакетов](./docs/packages.md)
    - [x] [Очереди](./docs/queues.md)
    - [x] [Планирование задач](./docs/scheduling.md)
- ## Безопасность
    - [x] [Аутентификация](./docs/authentication.md)
    - [x] [Авторизация](./docs/authorization.md)
    - [x] [Подтверждение адреса электронной почты](./docs/verification.md)
    - [x] [Шифрование](./docs/encryption.md)
    - [x] [Хеширование](./docs/hashing.md)
    - [x] [Сброс пароля](./docs/passwords.md)
- ## База данных
    - [x] [Начало работы](./docs/database.md)
    - [x] [Построитель запросов](./docs/queries.md)
    - [x] [Постраничная навигация](./docs/pagination.md)
    - [x] [Миграции](./docs/migrations.md)
    - [x] [Наполнение фиктивными данными](./docs/seeding.md)
    - [x] [Использование Redis](./docs/redis.md)
- ## Eloquent ORM
    - [x] [Начало работы](./docs/eloquent.md)
    - [x] [Отношения](./docs/eloquent-relationships.md)
    - [x] [Коллекции](./docs/eloquent-collections.md)
    - [x] [Мутаторы и типизация](./docs/eloquent-mutators.md)
    - [x] [Ресурсы API](./docs/eloquent-resources.md)
    - [x] [Сериализация](./docs/eloquent-serialization.md)
- ## Тестирование
    - [x] [Начало работы](./docs/testing.md)
    - [x] [Тесты HTTP](./docs/http-tests.md)
    - [x] [Консольные тесты](./docs/console-tests.md)
    - [x] [Браузерные тесты](./docs/dusk.md)
    - [x] [База данных](./docs/database-testing.md)
    - [x] [Имитация](./docs/mocking.md)
- ## Пакеты
    - [x] [Breeze](./docs/starter-kits.md#laravel-breeze)  
        Легковесная реализация аутентификации Laravel для ознакомления с функционалом. Включает простые шаблоны Blade, стилизованные с помощью Tailwind CSS. Содержит маршруты для публикации.
    - [ ] [Cashier (Stripe)](./docs/billing.md)
    - [ ] [Cashier (Paddle)](./docs/cashier-paddle.md)
    - [x] [Dusk](./docs/dusk.md)  
        Автоматизация поведения браузера и тестирование с использованием ChromeDriver.
    - [x] [Envoy](./docs/envoy.md)  
        Инструмент для запуска задач, выполняемых на удаленных серверах. Задачи определяются в файле `Envoy.blade.php` в корне приложения с использованием директив шаблонизатора Blade.
    - [x] [Fortify](./docs/fortify.md)  
        Серверная реализация аутентификации Laravel. Не содержит никаких шаблонов. Используется в Laravel Jetstream.
    - [ ] [Homestead](./docs/homestead.md)
    - [ ] [Horizon](./docs/horizon.md)
    - [ ] [Jetstream](https://jetstream.laravel.com)  
        Красиво оформленный каркас приложений. Включает в себя Fortify и Sanctum.
    - [ ] [Passport](./docs/passport.md)
    - [ ] [Sail](./docs/sail.md)
    - [x] [Sanctum](./docs/sanctum.md)  
        Легковесная система аутентификации для SPA (одностраничных приложений), мобильных приложений и простых API на основе токенов. Управление токенами API, аутентификация сессии. Не содержит никаких шаблонов. Используется в Laravel Jetstream.
    - [ ] [Scout](./docs/scout.md)
    - [x] [Socialite](./docs/socialite.md)  
        Аутентификация через провайдеров OAuth: Facebook, Twitter, LinkedIn, Google, GitHub, GitLab, и Bitbucket.
    - [x] [Telescope](./docs/telescope.md)  
        Панель управления, отображающая записи о произошедших в приложении событиях.
    - [ ] [Valet](./docs/valet.md)
- [Документация API](https://laravel.com/api/8.x/)

<a name="dictionary"></a>
### Соглашения по переводу

В русской раскладке используются двойные кавычки в формате `«слово»`.

В следующей таблице перечислены варианты принятых переводов некоторых терминов и словосочетаний, используемых в переводе документации для общей согласованности.

**Оглавление**
0-9
[A](#dictionary-a)
[B](#dictionary-b)
[C](#dictionary-c)
[D](#dictionary-d)
[E](#dictionary-e)
[F](#dictionary-f)
[G](#dictionary-g)
[H](#dictionary-h)
[I](#dictionary-i)
[J](#dictionary-j)
K
[L](#dictionary-l)
[M](#dictionary-m)
[N](#dictionary-n)
[O](#dictionary-o)
[P](#dictionary-p)
[Q](#dictionary-q)
[R](#dictionary-r)
[S](#dictionary-s)
[T](#dictionary-t)
[U](#dictionary-u)
[V](#dictionary-v)
[W](#dictionary-w)
X
[Y](#dictionary-y)
Z

Исходный вариант  |  Вариации перевода  |  Замечания
----------------- | ------------------- | -------------
<a name="dictionary-a">**A**</a>
abilities  |  полномочия, компетенции  |  
accessors  |  аксессоры  |  
argument  |  аргумент  |  
asset pipeline  |  сценарий по сборки исходников  |  
asset  |  исходник  |  
assets  |  исходники  |  Директория исходных файлов проекта для фронтенда
atomic  |  атомарный, неделимый  |  
attach (a relation)  |  назначить (отношение)  |  
attaching  |  прикрепление, присоединение  |  
attempting  |  пытается  |  
authentication  |  аутентификация  |  
authorization  |  авторизация  |  
auto-incrementing ID  |  автоинкрементный идентификатор  |  
<a name="dictionary-b">**B**</a>
backend  |  серверная часть  |  
bag, message bag, attribute bag  |  коллекция, коллекция сообщений, коллекция атрибутов  |  
basic example  |  отвлеченный пример  |  Правильнее «пример основ» (чего-либо)
binding  |  связывание  |  
broadcaster  |  вещатель  |  
<a name="dictionary-c">**C**</a>
cache  |  кеш  |  
casting  |  типизация  |  
cast type  |  типизатор  |  
chain  |  связать (например, методы)  |  
chaining  |  цепочка (например, заданий)  |  
chunking  |  разбиение  |  
clauses  |  выражения  |  
сlosure  |  замыкание  |  
command bus  |  командная шина  |  
command line interface (CLI)  |  интерфейс командной строки  |  
commit  |  коммит, фиксация  |  
composer  |  компоновщик, конструктор  |  Менеджер пакетов Composer не переводится
condition  |  условие  |  
conditional  |  кондиционный  |  
configuration  |  конфигурация, конфигурирование  |  
constraints  |  ограничения, условия  |  
contract  |  контракт  |  
cookie  |  (файл) cookie  |  
custom  |  ваш, пользовательский, желаемый, собственный  |  
customization  |  настройка  |  
customizing  |  корректировка, изменение  |  
<a name="dictionary-d">**D**</a>
defining  |  определение  |  
deployment  |  развертывание  |  
desired capabilities  |  требуемые характеристики  |  
detaching  |  отсоединение  |  
directory  |  каталог, директория  |  
dispatch  |  выполнение, исполнение, запуск, направление  |  Прежде всего «постановка в очередь»
dump  |  вывод, отображение  |  
<a name="dictionary-e">**E**</a>
eager  |  нетерпеливый  |  
encrypter  |  шифровальщик  |  
encryption  |  шифрование  |  
environment  |  среда, окружение  |  
evaluated  |  проанализированы  |  
event  |  событие  |  
examining  |  изучение, исследование, интерпретация  |  
exit code  |  код выхода / возврата  |  
experience  |  опыт / продуктивность / возможности / удобство (разработки или разработчика)  |  
<a name="dictionary-f">**F**</a>
facade  |  фасад  |  
factory callbacks  |  хуки фабрики  |  
fake  |  фальсификация, фальшивка  |  
feature  |  функционал, особенность  |  
filesystem  |  файловое хранилище, файловая система  |  
fired  |  инициировано, сработано  |  
flash data  |  кратковременные данные, флеш-данные  |  Данные, имеющие непродолжительный срок существования
flashed to the session  |  записаны (краткосрочно) в сессию  |  
flexibility  |  гибкость  |  
fluent  |  текучий, гибкий, последовательный  |  
force  |  принудительно  |  
foreign key constraints  |  ограничения внешнего ключа  |  
<a name="dictionary-g">**G**</a>
gate  |  шлюз (авторизации)  |  
generating  |  генерация  |  Незаменимо словом «создание». Предполагается генерация ч.-л. с использованием команд Artisan.
given  |  переданный, указанный, конкретный  |  
guard  |  охранник (аутентификатора)  |  
guarding  |  защита  |  
<a name="dictionary-h">**H**</a>
hashing  |  хеширование  |  
helpful  |  полезный  |  
helpers  |  помощники, глобальные вспомогательные функции  |  
hydrated  |  присоединены (включены в результирующий набор)  |  Например, в коллекцию при использовании генераторов на основе курсоров
<a name="dictionary-i">**I**</a>
in-memory  |  хранимые в памяти  |  
<a name="dictionary-j">**J**</a>
job  |  задание, задача  |  
job batching  |  пакетная обработка заданий  |  
<a name="dictionary-l">**L**</a>
layer over  |  обертка над  |  
lazy  |  отложенный  |  
listener  |  слушатель  |  
load balancer  |  балансировщик нагрузки  |  
localization  |  локализация  |  
log  |  журнал  |  
logger  |  регистратор  |  
logging  |  логирование  |  
loose comparisons  |  гибкое сравнение  |  Противоположное `strict comparisons`
<a name="dictionary-m">**M**</a>
macro (macros)  |  макрокоманда (макрокоманды)  |  
macroable  |  макропрограммируемый  |  
maintenance mode  |  режим обслуживания  |  
making  |  инициализация  |  Например, метод фабрики `make` инициализирует, но не создает запись о модели в БД.
manually  |  самостоятельно, вручную, по требованию  |  
mapping  |  сопоставление, картирование, перебор, _реже_ итерация  |  
mass assignment  |  массовое присвоение  |  
middleware  |  посредник  |  
migration  |  миграция  |  
migration squashing  |  сжатие миграций  |  
miscellaneous  |  разное  |  
mock  |  подставной объект  |  
mocking  |  имитация  |  
mutator  |  мутатор  |  
<a name="dictionary-n">**N**</a>
named error bag  |  именованные коллекции ошибок  |  
<a name="dictionary-o">**O**</a>
observers  |  наблюдатели  |  
old input  |  прежний ввод  |  
on-demand  |  по требованию, по запросу  |  
opinion  |  мнение  |  
opinions  |  представления (о чем-либо), принципы (например, работы)  |  
optional  |  необязательный  |  
options  |  параметры  |  
overriding  |  переопределение  |  
<a name="dictionary-p">**P**</a>
pagination  |  постраничная навигация, пагинация  |  
payload  |  информационная часть данных (HTTP-запроса)  |  
permanently  |  окончательно  |  
pipelining commands  |  конвейерное выполнение команд  |  
placeholder  |  заполнитель, метка-заполнитель, символ-заполнитель, заменитель  |  
policy  |  политика  |  
power  |  возможность  |  В контексте о функциональности
progress bar  |  индикатор выполнения  |  
production  |  эксплуатация  |  
<a name="dictionary-q">**Q**</a>
query builder  |  построитель запросов  |  
query constraints  |  ограничения запроса  |  
queue  |  очередь  |  
queue worker  |  обработчик очереди  |  
queueable  |  поочередный, последовательный  |  
<a name="dictionary-r">**R**</a>
rate limit  |  предел (лимит) частоты  |  
rate limiting  |  ограничение частоты  |  
redirect  |  перенаправление  |  
redirector  |  перенаправитель  |  
refreshing  |  обновление  |  
reflection  |  рефлексия (отражение)  |  
release  |  релиз, выпуск, проброс (задания в очереди)  |  Не уточнено.
relationships  |  отношения  |  
rendered  |  обработанный (HTML-код)  |  
rendering  |  отображение, визуализация, рендеринг  |  
replicating  |  репликация, тиражирование  |  
request  |  запрос  |  
resource  |  ресурс  |  Источник информации, например, API-ресурс
resources  |  ресурсы  |  Директория исходных файлов проекта для фронтенда
response  |  ответ  |  
retrieving  |  получение, извлечение  |  
route  |  маршрут  |  
routing  |  маршрутизация  |  
<a name="dictionary-s">**S**</a>
scaffold  |  каркас  |  
scaffolding  |  каркасное программирование  |  Автоматизация по написанию кода на основе заготовок
skeleton  |  каркас  |  
scope  |  область, сфера, диапазон  |  То, что имеет ограничения
seeding  |  наполнение  |  
sequence  |  последовательность, серия  |  
serialization  |  сериализация  |  
service container  |  контейнер служб  |  
service providers  |  поставщики служб  |  
session  |  сессия  |  
schema builder  |  построитель схемы  |  
shortcut  |  ярлык, псевдоним  |  
slug  |  дружественный URI (фрагмент URL-адреса)  |  
soft deleting  |  программное удаление  |  
Sometimes you may need, Sometimes you may wish  |  По желанию можно (может)  |  
source maps  |  карты исходников  |  
spy on an object  |  наблюдать за объектом  |  
specific  |  конкретный, определенный  |  
squashing  |  сжатие  |  
staging  |  промежуточная (стадия разработки)  |  
statement  |  оператор, выражение  |  
starter kit  |  стартовый комплект  |  
strict comparisons  |  жесткое сравнение  |  Противоположное `loose comparisons`
stub  |  заглушка, заготовка  |  «Заготовка» может употребляться, например, относительно пустого класса с нереализованными методами, а «заглушка» – в контексте тестов.
<a name="dictionary-t">**T**</a>
terms of service  |  условия использования  |  
timestamp  |  временная метка  |  
type-hinting  |  типизация (аргументов), объявление зависимостей  |  
toggling  |  переключение  |  
<a name="dictionary-u">**U**</a>
user-land  |  пользовательский слой ПО  |  
<a name="dictionary-v">**V**</a>
valid  |  действительный, допустимый  |  
validation  |  валидация, проверка  |  
validator  |  валидатор  |  
vendor  |  поставщик  |  Директория `vendor` с библиотеками от сторонних поставщиков
verb, HTTP  |  HTTP-метод  |  
verification  |  подтверждение  |  
view  |  шаблон, представление  |  
<a name="dictionary-w">**W**</a>
wildcard  |  метасимвол подстановки  |  
work factor  |  коэффициент работы  |  
<a name="dictionary-y">**Y**</a>
yield  |  дополнение, дополнять  |  
