# Вопросы для собеседования Golang разработчика

## Содержание

1. [Общие вопросы](#common_questions)
2. [Вопросы про микросервисы](#microseivice_questions)
3. [Вопросы про инфраструктуру и деплой](#infrastructure_deploy_questions)
4. [Вопросы про кеширование и БД](#database_cache_questions)
5. [Вопросы по языку Golang](#golang_questions)

### <a name="common_questions"></a>Общие вопросы

**1. В чем отличие протоколов TCP и UDP? В каком случае UDP предпочтительнее?**

__TCP__ – транспортный протокол передачи данных в сетях TCP/IP, предварительно устанавливающий соединение с сетью.

__UDP__ – транспортный протокол, передающий сообщения-датаграммы без необходимости установки соединения в IP-сети.

Разница между протоколами TCP и UDP – в так называемой _"гарантии доставки"_. 
TCP требует отклика от клиента, которому доставлен пакет данных, подтверждения доставки, и для этого ему необходимо установленное заранее соединение. 
Также протокол TCP считается надежным, тогда как UDP получил даже именование “протокол ненадежных датаграмм. 
TCP исключает потери данных, дублирование и перемешивание пакетов, задержки. 
UDP все это допускает, и соединение для работы ему не требуется. 
Процессы, которым данные передаются по UDP, должны обходиться полученным, даже и с потерями. 
TCP контролирует загруженность соединения, UDP не контролирует ничего, кроме целостности полученных датаграмм.

С другой стороны, благодаря такой не избирательности и бесконтрольности, UDP доставляет пакеты данных (датаграммы) гораздо быстрее, потому для приложений, которые рассчитаны на широкую пропускную способность и быстрый обмен, UDP можно считать оптимальным протоколом. 
К таковым относятся сетевые и браузерные игры, а также программы просмотра потокового видео и приложения для видеосвязи (или голосовой): от потери пакета, полной или частичной, ничего не меняется, повторять запрос не обязательно, зато загрузка происходит намного быстрее. 
Протокол TCP, как более надежный, с успехом применяется даже в почтовых программах, позволяя контролировать не только трафик, но и длину сообщения и скорость обмена трафиком.

### <a name="microseivice_questions"></a>Вопросы про микросервисы

### <a name="infrastructure_deploy_questions"></a>Вопросы про инфраструктуру и деплой

### <a name="database_cache_questions"></a>Вопросы про кеширование и БД

### <a name="golang_questions"></a>Вопросы по языку Golang
