---
tag: app
context: keyboard
---
up:: [[Программы на все случаи жизни]]

[karabiner-elements.pqrs.org](https://karabiner-elements.pqrs.org/)
```shell
brew install --cask karabiner-elements
```

Программа для [[MacOS]], которая позворяет очень гибко настраивать работу клавиатур (и других устройств ввода).

Один из сценариев использования, например: при зажатии CapsLock в ОС отправляются нажатия `Cmd+Shift+Option+Control` - это полезно использовать как глобальные горячие клавиши для запуска каких-то приложений. У меня, например на комбинацию `CapsLock+O` установлен запуск [[Obsidian]]. При этом при кратковременном нажатии на `CapsLock` можно оставить отправку кода `CapsLock` в операционную систему.

Другой пример - чтобы не тянуться мизинцем на клавиатуре MacBook'а до клавиши `Enter` можно создать правило, по которому при одновременном нажатии на `J+I` в операционную систему будет посылаться нажатие клавиши `Enter`

Также разные правила можно применять при разных активных приложениях, [например](https://github.com/wierdbytes/.dotfiles/blob/d2f9e0f79eb948641c32e1aef3278949680b0ce5/.config/karabiner.edn#L574), в приложении [[Telegram]] при нажатии `Cmd+J` Karabiner может отправлять комбинацию `Cmd+Enter`. Аналогично и для разных [раскладок](https://github.com/wierdbytes/.dotfiles/blob/d2f9e0f79eb948641c32e1aef3278949680b0ce5/.config/karabiner.edn#LL21C6-L21C19) или [клавиатур](https://github.com/wierdbytes/.dotfiles/blob/d2f9e0f79eb948641c32e1aef3278949680b0ce5/.config/karabiner.edn#LL2C1-L2C1)

Штатный конфигуратор сделан очень неудобным, можно писать правила с использованием JSON'а, но есть вспомогательные [утилиты](https://karabiner-elements.pqrs.org/docs/json/external-json-generators/) наподобие [[GokuRakuJoudo]]

Пример моего [конфига](https://github.com/wierdbytes/.dotfiles/blob/main/.config/karabiner.edn) с разделением на две клавиатуры: встроенная в MacBook Air и внешняя Lyly58 Pro