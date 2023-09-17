---
tag: app
context: keyboard
---
up:: [[Karabiner-Elements]]

https://github.com/yqrashawn/GokuRakuJoudo
```shell
brew install yqrashawn/goku/goku
```

Небольшая консольная утилита, которая конвертирует лаконичные [edn-файлы](https://github.com/edn-format/edn) в стандартный формат JSON-файла конфигурации для [[Karabiner-Elements]].

Документация представленна в виде двух основных файлов:
- [tutorial.md](https://github.com/yqrashawn/GokuRakuJoudo/blob/master/tutorial.md) - на примерах показана реализация разных механизмов работы (layers, templates, applications, devices, ...)
- [example.edn](https://github.com/yqrashawn/GokuRakuJoudo/blob/master/resources/configurations/edn/example.edn) - пример конфига целиком с несколькими примерами и комментариями

Дополнительном можно ориентироваться на [keys_info.clj](https://github.com/yqrashawn/GokuRakuJoudo/blob/master/src/karabiner_configurator/keys_info.clj) для сверки с кодами клавиш.

Мой [karabiner.edn](https://github.com/wierdbytes/.dotfiles/blob/main/.config/karabiner.edn), который я использую в работе каждый день.