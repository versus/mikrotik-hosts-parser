# MikroTik hosts parser

[![styleci](https://styleci.io/repos/39877790/shield)](https://styleci.io/repos/39877790) [![Build Status](https://scrutinizer-ci.com/g/tarampampam/mikrotik-hosts-parser/badges/build.png?b=master)](https://scrutinizer-ci.com/g/tarampampam/mikrotik-hosts-parser/build-status/master)  [![Dependency Status](https://www.versioneye.com/user/projects/5980d48f0fb24f005bcbf104/badge.svg?style=flat-square)](https://www.versioneye.com/user/projects/5980d48f0fb24f005bcbf104) [![Code Coverage](https://scrutinizer-ci.com/g/tarampampam/mikrotik-hosts-parser/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/tarampampam/mikrotik-hosts-parser/?branch=master) [![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/tarampampam/mikrotik-hosts-parser/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/tarampampam/mikrotik-hosts-parser/?branch=master)  [![GitHub issues](https://img.shields.io/github/issues/tarampampam/mikrotik-hosts-parser.svg?style=flat-square)](https://github.com/tarampampam/mikrotik-hosts-parser/issues) [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](https://raw.githubusercontent.com/tarampampam/mikrotik-hosts-parser/master/LICENSE)

Приложение, которое генерирует скрипт для роутера на базе `RouterOS`, который блокирует "рекламные" хосты.

Более подробно о нем можно прочитать по [этой ссылке (хабр)][habr].

### Установка

Для развертывания приложения достаточно выполнить в терминале:

```bash
$ composer create-project tarampampam/mikrotik-hosts-parser
```

Все интересные настройки вынесены в файлы конфигурации, что лежат в директории `./config`:

### Демо

Не гарантирую что приложение будет жить вечно, что пользоваться им можешь [тут][demo].

### Лицензия

[MIT license](./LICENSE) *(да делай ты что хочешь, просто не удаляй имя автора)*.

[demo]: https://stopad.kplus.pro/
[habr]: https://habrahabr.ru/post/264001/
