# README

Тестовое приложение для изучения TailwindCSS. Сделано по статье: "[How to Use Tailwind CSS for Your Ruby On Rails Project](https://blog.appsignal.com/2024/06/05/how-to-use-tailwind-css-for-your-ruby-on-rails-project.html)". В этом учебном проекте использовался TailwindCSS v4, в статье v3. Поэтому есть различия в создании конфига Tailwind и кастомных стилей.


Чтобы запустить проект нужно выполнить последовательно эти команды в дирректории проекта:

1. `bundle install
2. `rails db:create`(Нужен SQlite, если его нету, то нужно установить:`sudo apt update && apt install sqlite3 sqlite-tool`)
3. `rails db:migrate`
4. `./bin/dev`

В приложение есть пути:

- `http://localhost:3000/landing/index` с примером кастомных стилей
- `http://localhost:3000/grids/index` с примером адаптивной сетки и кастомными стилями
- `http://localhost:3000/users/new` с примером использования TailwindCSS
