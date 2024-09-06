### Есть довольно много опций, с которыми можно играть, настроим самые важные: наше имя пользователя и адрес электронной почты

git config --global user.name "My Name"

git config --global user.email myEmail@example.com

### Инициализация/создание репозитория
git init

### Добавим все файлы проекта в нам будующий commit
git add .
### Или так
git add --all

### Определение состояния
git status


### Если хотим добавить конкретный файл то можно так
git add <имя_файла>

### Теперь создаем commit. Обязательно указываем комментарий.
И не забываем про кавычки


git commit -m "<комментарий>"

### Как посмотреть коммиты 
git log

### Пример клонирования репозитория
git clone https://github.com/tutorialzine/awesome-project

### Подключение к удаленному репозиторию
git remote add origin https://github.com/tutorialzine/awesome-project.git

### Отправка изменений на сервер
git push origin master

### Как удалить локальный репозиторий
cd repository-path/

rm -r .git