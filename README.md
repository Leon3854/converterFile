# Converter file for Gulp (work only sass no font and min images)
с помощь этих файйлов вы сможете быстро настроить сборку вашего проекта на Gulp.

## Структура каталогов для размещения файлов стилей и скриптов:
>./src/styles/\*\*/\*.less
>./src/scripts/\*\*/\*.js

## Инструкция:
1. Скачать все файлы в любую директорию, либо скопировать адрес открыть паку проекта
в терминале набрать команду git clone https://.... и вставляем скопированный адрес с проектом.
2. Ввести в терминале команду: npm i (должен быть установлен node.js)
3. Выполнить команду: gulp (запуск таска defalut)
4. Вестать, творить  и не думать об обновлении страницы всё уже работает само.

## Ссылки
[Докуменация по GULP on Russina language] (https://webdesign-master.ru/blog/docs/gulp-documnetation.html)

## Установленные NPM пакеты
[gulp] - Сборщик Gulp
[gulp-less] - Компеляция Less файлов
[gulp-babel] - Преобразовывает Java Scripts в старый стандарт
[gulp-concat] - Объеденение нескольких файлов в один
[gulp-uglify] - Сжатие и оптимизация Java Scripts кода
[gulp-rename] - Переменовывает файлы
[gulp-clean-css] - Минификация и оптимизация Css файлов
[del] - Удаление каталогов и файлов
[gulp-sourcemaps] - Создаёт специальные карты которые позволяют видить строки в файлах less
[gulp-autoprefixer] - Добавляет префексы для css стилей
[gulp-imagemin] - Для работы с изображениями - не пошел удалил
[gulp-htmlmin] - Сжимает html файл.
[gulp-browsersync]
[gulp-pug] - что бы он стал основным при работе то вам надо будет в const build заменить html на  pug
и у вас всё будет работать хорошо
[gulp-stylus] - предназначен для работы с css
[gulp-sass] - препроцессор sass и scss в css
[gulp-typscript] - препроцессор typscript в js script
