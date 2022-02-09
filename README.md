<div align="center">
  <img width="325" height="281" src="https://github.com/goavengers/go-interview/blob/master/img/go-inter.jpeg">
  <h1>Вопросы и ответы для собеседования Back-end/Golang разработчика и не только</h1>
  <h5>Вместе мы разберемся!</h5>
</div>

Здесь собирается большая коллекция вопросов и ответов на них, необходимых не только для прохождения собеседований, но и для комплексного развития кругозора

## Содержание

1. [Общие вопросы](docs/COMMON.md)
    - [В чем отличие протоколов TCP и UDP? В каком случае UDP предпочтительнее?](docs/COMMON.md#1)
    - [Что такое NAT?](docs/COMMON.md#2)
    - [Что такое HTTP и HTTPS, в чем их отличия?](docs/COMMON.md#3)
    - [Что такое SSL и TLS, есть ли между ними отличия?](docs/COMMON.md#4)
    - coming soon
2. [Вопросы по шаблонам проектирования](docs/DESIGN_PATTERNS.md)
    - TODO
3. [Вопросы про микросервисы](docs/MICROSERVICES.md)
    - TODO
4. [Вопросы про инфраструктуру и деплой](docs/INFRASTRUCTURE_AND_DEPLOY.md)
    - Что такое сине-зеленый деплой(blue-green deployment)?
    - Что такое Canary (канареечные развертывания)?
    - Что такое Dark (скрытые) или А/В-развертывания?
    - coming soon
5. [Вопросы про кеширование и базам данных](docs/CACHE_AND_DB.md)
    - Что такое индексы в MySQL, как и для чего их использовать и создавать?
    - Что такое составной индекс, как и для чего их использовать и создавать?
    - Как использовать индексы в JOIN запросах Mysql?
    - Что такое частичные индексы, как и для чего их использовать и создавать?
    - В чем отличия InnoDB и MyISAM?
    - Возможен ли JOIN со вложенными запросами, как?
    - Что такое дедлоки (deadlock), почему возникают, как можно недопускать?
    - Что такое HAVING, что он делает как и зачем его использовать?
    - Разница между WHERE и HAVING и можно ли использовать HAVING без группировки данных?
    - Что такое EXPLAIN?
    - Как узнать версию Mysql?
    - Как можно оптимизировать ORDER BY RAND()?
    - Как удалить индекс MySQL?
    - Как правильно выбрать тип данных в Mysql, когда нужны:
      - NULL значения, когда лучше использовать?
      - Целые числа (TINYINT, SMALLINT, INT, BIGINT) и UNSIGNED, длинна числовых типов?
      - Большие числа: demical, что это и как работает?
      - Float | Double VS Demical, в чем разница, что и как использовать?
      - Строки VARCHAR и CHAR, отличия когда лучше использовать?
      - BLOB / TEXT, чем отличаются, как выполнять сортировку по полям данного типа?
      - ENUM, когда может пригодится?
      - DATETIME / TIMESTAMP, в чем их разница, какие максимальные значения?
    - Когда и зачем может пригодиться денормализация данных?
    - Что такое шардинг и репликация?
    - coming soon
6. [Вопросы по языку Golang](docs/GOLANG.md)
    - [Что из себя представляет тип данных string в языке Golang? Можно ли изменить определенный символ в строке? Что происходит при склеивании строк?](docs/GOLANG.md#1)
    - [Вытекающий вопрос — как эффективно склеивать множество строк?](docs/GOLANG.md#2)
    - Что будет происходить при конкурентной записи в map? Как можно решить эту проблему?
    - Расскажите о ООП в Golang.
    - В чем различия goroutine от потока системы?
    - Как огранить число потоков на системы при запуске Golang программы и возможно ли огранить их до 1 потока?
    - [Как задать направление канала?](docs/GOLANG.md#8)
    - [Напишите собственную функцию Sleep, используя time.After](docs/GOLANG.md#9)
    - [Что такое буферизированный канал? Как создать такой канал с ёмкостью в 20 сообщений?](docs/GOLANG.md#10)
    - [Напишите программу, которая меняет местами два числа (x := 1; y := 2; swap(&x, &y) должно дать x=2 и y=1)](docs/GOLANG.md#11)
    - [Какое будет значение у переменной x после выполнения программы?](docs/GOLANG.md#12)
    - [Какое значение примет выражение (true && false) || (false && true) || !(false && false)?](docs/GOLANG.md#13)
    - [Мы знаем, что в десятичной системе самое большое число из одной цифры - это 9, а из двух - 99. В бинарной системе самое большое число из двух цифр это 11 (3), самое большое число из трех цифр это 111 (7) и самое большое число из 4 цифр это 1111 (15). Вопрос: каково самое большое число из 8 цифр? (Подсказка: 101-1=9 и 102-1=99)](docs/GOLANG.md#14)
    - [Что выведет следующая программа?](docs/GOLANG.md#15)
    - [Что выведет следующая программа?](docs/GOLANG.md#16)
    - [Как работает Garbage Collection в Go?](docs/GOLANG.md#17)
    - Что такое interface, как они работают в Go?
    - Что такое slice, как устроены и чем отличаются от массивов?
    - Что такое len и capacity в slice Go?
    - Возможно ли предугадать, что GC отработает за константное время N?
    - Что будет, если создать канал и отправить туда запись, но у него нет читателей?
7. [Вопросы о распределённых системах](docs/DISTRIBUTED_SYSTEMS.md)
    - Как тестировать распределённую систему?
    - coming soon
8. [Вопросы по организации кода](docs/CODE_DESIGN.md)
    - Как тесты и TDD влияют на организацию кода?
    - В чём разница между сцеплением и связанностью?
    - Почему в TDD тесты пишутся прежде кода?
    - Если у вашего кода плохая организация, как вы это поймёте?
9. [Вопросы от Данила Подольского на позицию Senior Golang Backend Developer в компанию Evrone](docs/PODOLSKY.md)
    - [Go — императивный или декларативный? А в чем разница?](docs/PODOLSKY.md#1)
    - [Что такое type switch?](docs/PODOLSKY.md#2)
    - Как сообщить компилятору, что наш тип реализует интерфейс?
    - Как работает append?
    - Какое у slice zero value? Какие операции над ним возможны?
    - Как устроен тип map?
    - Каков порядок перебора map?
    - Что будет, если читать из закрытого канала?
    - Что будет, если писать в закрытый канал?
    - Как вы отсортируете массив структур по алфавиту по полю Name?
    - Что такое сериализация? Зачем она нужна?
    - Сколько времени в минутах займет у вас написание процедуры обращения односвязного списка?
    - Где следует поместить описание интерфейса: в пакете с реализацией или в пакете, где этот интерфейс используется? Почему?
    - Предположим, ваша функция должна возвращать детализированные Recoverable и Fatal ошибки. Как это реализовано в пакете net? Как это надо делать в современном Go?
    - Главный недостаток стандартного логгера?
    - Есть ли для Go хороший orm? Ответ обоснуйте.
    - Какой у вас любимый линтер?
    - Можно ли использовать один и тот же буфер []byte в нескольких горутинах?
    - Какие типы мьютексов предоставляет stdlib?
    - Что такое lock-free структуры данных, и есть ли в Go такие?
    - Способы поиска проблем производительности на проде?
    - Стандартный набор метрик prometheus в Go -программе?
    - Как встроить стандартный профайлер в свое приложение?
    - Overhead от стандартного профайлера?
    - Почему встраивание — не наследование?
    - Какие средства обобщенного программирования есть в Go?
    - Какие технологические преимущества языка Go вы можете назвать?
    - Какие технологические недостатки языка Go вы можете назвать?
10. [Популярные задачи на собеседованиях](docs/POPULAR_TASKS.md)
    - [На вход подаются два неупорядоченных слайса любой длины. Надо написать функцию, которая возвращает их пересечение](docs/POPULAR_TASKS.md#1)
    - [Написать генератор случайных чисел](docs/POPULAR_TASKS.md#2)
    - [Слить N каналов в один](docs/POPULAR_TASKS.md#3)
    - [Сделать конвейер чисел](docs/POPULAR_TASKS.md#4)
    - [Написать WorkerPool с заданной функцией](docs/POPULAR_TASKS.md#5)
    - [Сделать кастомную waitGroup на семафоре](docs/POPULAR_TASKS.md#6)
   
## Как мне добавить свой вопрос-ответ?

- [Ознакомьтесь с шаблоном составления](TEMPLATE.md)
