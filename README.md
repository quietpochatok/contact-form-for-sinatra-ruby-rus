# Форма заявки для Sinatra (Ruby) сайта. Русская версия.

Форма заявки реализована для внедрения в проект на Sinatra (Ruby). Данные отправленные в форму заявки сохраняются в базе данных SQLite.

### Описание
Для работы формы требуется подключить гемы:

```ruby
require 'sinatra'
require 'sqlite3'
```

### TODO:
- сделать метод валидации форм
- сделать метод отправки на почту
- сделать английскую версию программы
- сделать поле прикрепления файла
- сделать страницу отображения отправленных данных (вход для администратора)
