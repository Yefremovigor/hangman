# Игра виселица
![Виселица](https://upload.wikimedia.org/wikipedia/commons/0/0b/%D0%92%D0%B8%D1%81%D0%B5%D0%BB%D0%B8%D1%86%D0%B0.svg)

Программа представляет собой консольную версию известной игры "[Виселица](https://ru.wikipedia.org/wiki/%D0%92%D0%B8%D1%81%D0%B5%D0%BB%D0%B8%D1%86%D0%B0_(%D0%B8%D0%B3%D1%80%D0%B0))"

##### Структура проекта:
```
.
├── data
|   └── words.txt
├── image
├── lib
|   ├── game.rb
|   ├── result_printer.rb
|   └── word_reader.rb
├── README.md
├── main.rb

```
data/words.txt - текстовый документ со списком слов, которые могут быть загаданы.

lib/game.rb - основной скрипт с логикой игры.

lib/result_printer.rb - класс вывода результата в консоль, использует текстовую псевдографику из папки image, гда номер файла соотведствует накопленному количеству ошибов.

lib/word_reader.rb - класс для получения отвечающий за чтение загадываемых слова.

##### Запуск программы из консоли:
```ruby
main.rb
```
##### Версия:
4.1

##### Требования:
Ruby 3.0+

###### Автор:
[Ефремов Игорь](https://github.com/Yefremovigor) & [goodprogrammer.ru](https://goodprogrammer.ru)