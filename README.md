# Redny-lp
Подробнее - vk.com/lp_cm

## Команды модуля ЛП
- `{сервисный префикс}` пинг/кинг/пиу — пинг
- `{сервисный префикс}` инфо — информация о модуле ЛП
***
- `{сервисный префикс}` префиксы свои — просмотр своих префиксов
- `{сервисный префикс}` префиксы дежурный — просмотр префиксов для дежурного
- `{сервисный префикс}` +префикс `[свой/дежурный]` — создание префикса
- `{сервисный префикс}` -префикс `[свой/дежурный]` — удаление префикса
***
- `{сервисный префикс}` алиасы - просмотр алиасов
- `{сервисный префикс}` +алиас `{имя}` {enter} `{команда которую получает модуль ЛП}` {enter} `{команда которую отсылает модуль ЛП}`  — создание алиаса
- `{сервисный префикс}` -алиас `{имя}` — удаление алиаса
- `{сервисный префикс}` алиасы паки — просмотр паков алиасов
- `{сервисный префикс}` алиасы пак `{имя пака}` — просмотр пака алиасов
- `{сервисный префикс}` алиасы импорт `{имя пака}` — импорт пака алиасов
***
- `{сервисный префикс}` игнорлист — просмотр игнорлиста
- `{сервисный префикс}` игнорлист все — просмотр игнорлиста по всем чатам
- `{сервисный префикс}` +игнор `[{ссылка}/{упоминание}/{реплай}]` — добавить в игнорлист
- `{сервисный префикс}` -игнор `[{ссылка}/{упоминание}/{реплай}]` — удалить из игнорлиста
***
- `{сервисный префикс}` глоигнорлист — просмотр глоигнорлиста
- `{сервисный префикс}` +глоигнор `[{ссылка}/{упоминание}/{реплай}]` — добавить в глоигнорлист
- `{сервисный префикс}` -глоигнор `[{ссылка}/{упоминание}/{реплай}]` — удалить из глоигнорлиста
***
- `{сервисный префикс}` мутлист — просмотр мутлиста
- `{сервисный префикс}` мутлист все — просмотр мутлиста по всем чатам
- `{сервисный префикс}` +мут `[{ссылка}/{упоминание}/{реплай}]` `{задержка}` — добавить в мутлист
- `{сервисный префикс}` -мут `[{ссылка}/{упоминание}/{реплай}]` — удалить из мутлиста
***
- `{сервисный префикс}` довы — просмотр доверенных пользователей
- `{сервисный префикс}` +дов `[{ссылка}/{упоминание}/{реплай}]` — добавить в дов-лист
- `{сервисный префикс}` -дов `[{ссылка}/{упоминание}/{реплай}]` — удалить из дов-листа
***
- `{сервисный префикс}` regex — Просмотр шаблонов для удаления
- `{сервисный префикс}` +regex `{имя}` `{regex}` `{для всех:да|нет}` — Добавить шаблон
- `{сервисный префикс}` -regex `{имя}` — Удалить шаблон
***
- `{сервисный префикс}` +потворялка — включить повторялку
- `{сервисный префикс}` -потворялка — выключить повторялку
- `{триггер повторялки}``{сообщение}` — повторить сообщение
***
- `{сервисный префикс}` eval/exec `{script}` — выполнение скрипта
***
- `{сервисный префикс}` -уведы — модуль будет удалять упоминания типа `@all`, `@online`...
- `{сервисный префикс}` +уведы — не будет удалять упоминания типа `@all`, `@online`...
***
- `{сервисный префикс}` рп — просмотр РП команд
***
- `{сервисный префикс}` секретный код — установка секретного кода
***
- `{сервисный префикс}` +автовыход — включить автовыход из бесед в которые вас пригласили
- `{сервисный префикс}` -автовыход — выключить автовыход из бесед в которые вас пригласили
- `{сервисный префикс}` автовыход +удаление — удалять диалог при выходе
- `{сервисный префикс}` автовыход -удаление — неудалять диалог при выходе
- `{сервисный префикс}` автовыход +чс — включить добавление в ЧС пригласившего 
- `{сервисный префикс}` автовыход -чс — выключить добавление в ЧС пригласившего 
***
- `{сервисный префикс}` +слоумо `{время}`\n`{текст}` — установка слоумо режима
- `{сервисный префикс}` -слоумо — удаление слоумо режима
- `{сервисный префикс}` слоумо — просмотр настроек слоумо режима
- `{сервисный префикс}` слоумо +белый список `{пользователь}` — добавление пользователя в белый список
- `{сервисный префикс}` слоумо -белый список `{пользователь}` — удаление пользователя из белого списка
- `{сервисный префикс}` слоумо время `{время}` — изменение времени задержки
- `{сервисный префикс}` слоумо текст `{текст}` — изменение текста предупреждения
***
- `{сервисный префикс}` +добавление `{текст}` — включить отправку запросов в друзья, пользователям, которые заходят в чат. При этом будет отправляться приветственный `{текст}`.
- `{сервисный префикс}` -добавление — отключить отправку запросов в друзья, пользователям, которые заходят в чат.
***
- `{сервисный префикс}` выключать уведы — включить выключение уведомлений при входе в беседу 
- `{сервисный префикс}` не выключать уведы — выключить выключение уведомлений при входе в беседу 
