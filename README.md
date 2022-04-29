# Игра виселица

![Виселица](https://upload.wikimedia.org/wikipedia/commons/0/0b/%D0%92%D0%B8%D1%81%D0%B5%D0%BB%D0%B8%D1%86%D0%B0.svg)

Программа представляет собой консольную версию известной
игры "[Виселица](https://ru.wikipedia.org/wiki/%D0%92%D0%B8%D1%81%D0%B5%D0%BB%D0%B8%D1%86%D0%B0_(%D0%B8%D0%B3%D1%80%D0%B0))"

##### Структура проекта:

```
.
├── data
|   ├── figures
|   └── words.txt
├── lib
|   ├── console_interface.rb
|   └── game.rb
├── README.md
├── main.rb

```

data/figures - Папка с псевдографикой.

data/words.txt - текстовый документ со списком слов, которые могут быть
загаданы.

lib/console_interface.rb - Вывод информации об игре и псевдографики в консоль.

lib/game.rb - основной скрипт с логикой игры.


##### Запуск программы из консоли:

```ruby
ruby main.rb
```

##### Версия:

4.1

##### Требования:

Ruby 2.4+

###### Автор:

[Ефремов Игорь](https://github.com/Yefremovigor)
& [goodprogrammer.ru](https://goodprogrammer.ru)