### _Vue component generator_ - утилита для генерации блоков
Есть 2 режима:  
* Консольный - поддерживает множественное создание
* Интерактивный - не поддерживает множественное создание, но позволяет выбирать функции в компоненте по умолчанию.

Аргументы для консольного режима:  
* `<name-block ...>` - имена блоков через пробел.
* `-t, --type` - тип блока (block|element), по умолчанию block.
* `--no-folder` - создает без папки.

Команды в package.json:  
* `yarn create:block` - вызывает интерактивный режим, передавать аргументы не нужно.
* `yarn create:component` - вызывает консольный режим, нужно передавать аргументы для его активации. По умолчанию создает в папке с именем компонента.
* `yarn create:element` - вызывает консольный режим для создания элемента. По умолчанию создает без папки с именем компонента.
