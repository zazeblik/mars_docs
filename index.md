### MARS - Multi-channel Automatic Response Sysytem (Мультиканальная система обработки запросов )

- Автоматизация для колл-центров
- Обработка голосовой информации и тоновых сигналов с клавиатуры
- Обработка входящих и исходящих звонков
- Сбор информации от абонентов и занесение их в учетные системы

#### Лицензия
[GNU GPLv3](https://github.com/komunikator/mars/blob/master/License_(GNU_GPL_v3))

#### Описание
- для обозначения стабильных версий предусмотрены тэги
- для работы проекта с голосом нужен SoX


#### Установка
  1. скачать и установить LTS версию node.js (с сайта https://nodejs.org/en/)
  2. скачать и установить git (для linux есть в репозиториях, для windows качаем последнюю версию с http://git-scm.com/download/win )
  3. сделать локальную копию стабильной версии проекта: git clone -b stable https://github.com/komunikator/mars.git
  4. установить программу sox (для linux есть в репозиторях, для windows качаем последнюю версию с http://sourceforge.net/projects/sox/ )
  5. установить зависимости проекта командой npm i

#### Запуск
```sh
node mars
```

Для более подробного описания процесса установки и запуска можно обратиться к инструкции [MARS. Руководство по установке и запуску](http://mars.kloud.one/%D0%A3%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B0%20%D0%B8%20%D0%B7%D0%B0%D0%BF%D1%83%D1%81%D0%BA%20(%D1%81%D0%B5%D1%80%D0%B2%D0%B8%D1%81)/).