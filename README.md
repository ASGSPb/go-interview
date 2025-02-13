<div align="center">
  <img width="325" height="281" src="https://github.com/goavengers/go-interview/blob/master/img/go-inter.jpeg">
  <h1>Вопросы и ответы для собеседования Back-end/Golang разработчика и не только</h1>
  <h5>Вместе мы разберемся!</h5>
</div>

Здесь собирается большая коллекция вопросов и ответов на них, необходимых не только для прохождения собеседований, но и для комплексного развития кругозора

## Содержание

0. [Разогрев](docs/what_is_going_on)
1. [Общие вопросы](docs/common)
    - [В чем отличие протоколов TCP и UDP? В каком случае UDP предпочтительнее?](docs/common#1-в-чем-отличие-протоколов-tcp-и-udp-в-каком-случае-udp-предпочтительнее)
    - [Что такое NAT?](docs/common#2-что-такое-nat)
    - [Что такое HTTP и HTTPS, в чем их отличия?](docs/common#3-что-такое-http-и-https-в-чем-их-отличия)
    - [Что такое SSL и TLS, есть ли между ними отличия?](docs/common#4-что-такое-ssl-и-tls-есть-ли-между-ними-отличия)
    - coming soon
2. [Вопросы по шаблонам проектирования](docs/design_patterns)
    - TODO
3. [Вопросы про микросервисы](docs/microservices)
    - TODO
4. [Вопросы про инфраструктуру и деплой](docs/infrastructure_and_deploy)
    - Что такое сине-зеленый деплой(blue-green deployment)?
    - Что такое Canary (канареечные развертывания)?
    - Что такое Dark (скрытые) или А/В-развертывания?
    - coming soon
5. [Вопросы про кеширование и базам данных](docs/cache_and_db)
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
6. [Вопросы по языку Golang](docs/golang)
    - [Что из себя представляет тип данных string в языке Golang? Можно ли изменить определенный символ в строке? Что происходит при склеивании строк?](docs/golang#1)
    - [Вытекающий вопрос — как эффективно склеивать множество строк?](docs/golang#2)
    - Что будет происходить при конкурентной записи в map? Как можно решить эту проблему?
    - Расскажите о ООП в Golang.#1
    - [Какое будет значение у переменной x после выполнения программы?](docs/golang#12)
    - [Какое значение примет выражение (true && false) || (false && true) || !(false && false)?](docs/golang#13)
    - [Мы знаем, что в десятичной системе самое большое число из одной цифры - это 9, а из двух - 99. В бинарной системе самое большое число из двух цифр это 11 (3), самое большое число из трех цифр это 111 (7) и самое большое число из 4 цифр это 1111 (15). Вопрос: каково самое большое число из 8 цифр? (Подсказка: 101-1=9 и 102-1=99)](docs/golang#14)
    - [Что выведет следующая программа?](docs/golang#15)
    - [Что выведет следующая программа?](docs/golang#16)
    - [Как работает Garbage Collection в Go?](docs/golang#17)
    - Что такое interface, как они работают в Go?
    - Что такое slice, как устроены и чем отличаются от массивов?
    - Что такое len и capacity в slice Go?
    - Возможно ли предугадать, что GC отработает за константное время N?
    - Что будет, если создать канал и отправить туда запись, но у него нет читателей?
7. [Вопросы о распределённых системах](docs/distributed_systems)
    - Как тестировать распределённую систему?
    - coming soon
8. [Вопросы по организации кода](docs/code_design)
    - Как тесты и TDD влияют на организацию кода?
    - В чём разница между сцеплением и связанностью?
    - Почему в TDD тесты пишутся прежде кода?
    - Если у вашего кода плохая организация, как вы это поймёте?
9. [Вопросы от Данила Подольского на позицию Senior Golang Backend Developer в компанию Evrone](docs/podolsky/)
    - [Go — императивный или декларативный? А в чем разница?](docs/podolsky#1)
    - [Что такое type switch?](docs/podolsky#2)
    - [Как сообщить компилятору, что наш тип реализует интерфейс?](docs/podolsky#3)
    - [Как работает append?](docs/podolsky#4)
    - [Какое у slice zero value? Какие операции над ним возможны?](docs/podolsky#5)
    - [Как устроен тип map?](docs/podolsky#6)
    - [Каков порядок перебора map?](docs/podolsky#7)
    - [Что будет, если читать из закрытого канала?](docs/podolsky#8)
    - [Что будет, если писать в закрытый канал?](docs/podolsky#9)
    - [Как вы отсортируете массив структур по алфавиту по полю Name?](docs/podolsky#10)
    - [Что такое сериализация? Зачем она нужна?](docs/podolsky#11)
    - [Сколько времени в минутах займет у вас написание процедуры обращения односвязного списка?](docs/podolsky#12)
    - [Где следует поместить описание интерфейса: в пакете с реализацией или в пакете, где этот интерфейс используется? Почему?](docs/podolsky#13)
    - [Предположим, ваша функция должна возвращать детализированные Recoverable и Fatal ошибки. Как это реализовано в пакете net? Как это надо делать в современном Go?](docs/podolsky#14)
    - [Главный недостаток стандартного логгера?](docs/podolsky#15)
    - [Есть ли для Go хороший orm? Ответ обоснуйте.](docs/podolsky#16)
    - [Какой у вас любимый линтер?](docs/podolsky#17)
    - [Можно ли использовать один и тот же буфер []byte в нескольких горутинах?](docs/podolsky#18)
    - [Какие типы мьютексов предоставляет stdlib?](docs/podolsky#19)
    - [Что такое lock-free структуры данных, и есть ли в Go такие?](docs/podolsky#20)
    - [Способы поиска проблем производительности на проде?](docs/podolsky#21)
    - [Стандартный набор метрик prometheus в Go -программе?](docs/podolsky#22)
    - [Как встроить стандартный профайлер в свое приложение?](docs/podolsky#23)
    - [Overhead от стандартного профайлера?](docs/podolsky#24)
    - [Почему встраивание — не наследование?](docs/podolsky#25)
    - [Какие средства обобщенного программирования есть в Go?](docs/podolsky#26)
    - [Какие технологические преимущества языка Go вы можете назвать?](docs/podolsky#27)
    - [Какие технологические недостатки языка Go вы можете назвать?](docs/podolsky#28)
10. [Популярные задачи на собеседованиях](docs/popular_tasks)
    - [На вход подаются два неупорядоченных слайса любой длины. Надо написать функцию, которая возвращает их пересечение](docs/popular_tasks#1)
    - [Написать генератор случайных чисел](docs/popular_tasks#2)
    - [Слить N каналов в один](docs/popular_tasks#3)
    - [Сделать конвейер чисел](docs/popular_tasks#4)
    - [Написать WorkerPool с заданной функцией](docs/popular_tasks#5)
    - [Сделать кастомную waitGroup на семафоре](docs/popular_tasks#6)
   
## Как мне добавить свой вопрос-ответ?

- [Ознакомьтесь с шаблоном составления](TEMPLATE.md)

### Maintainers

<table>
<tr>
<td align="center">
<img src="https://avatars1.githubusercontent.com/u/23422968?s=460&u=668229465690637b50f6581df0fa9918d7fb6c1e&v=4" width="100px;" alt=""/>
<br /><sub><b>zikwall</b></sub></a><br />
</td>
<td align="center">
<img src="https://avatars.githubusercontent.com/u/2690403?v=4" width="100px;" alt=""/>
<br /><sub><b>dreddsa5dies</b></sub></a><br />
</td>
</tr>
</table>
