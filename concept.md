# Основные моменты разработки
## Codestyle
+ Для всего используем `snake_case`
+ Для макросов используем `SCREAMING_SNAKE_CASE`
+ Имена функций составляются по принципу: `название-модуля_название-функции`
+ Имена функций составляются по принципу: `глагол_объект` (например: `create_tree`, `fill_column`)
+ Если можно написать чистую функцию — пиши чистую

## Модули
Имена модулей уникальны.
+ Логгер и система ошибок, префикс `logos_`
+ Парсер, префикс `glossa_`
+ Библиотека деревьев `pld_tree_`

## Инструменты
+ Основной компилятор — `gcc`
+ Отладчик — `gdb`
+ Система сборки — `make`
+ Генератор документации — `doxygen`
