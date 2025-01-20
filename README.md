# first-project-git

Команды для git:

//проверка установки git
git --version  

//конфигурация git
git config --global user.name "Твой юзернейм"
git config --global user.email твой емейл

//вывод настроек git
git config --list

//создание репозитория 
git init 

//удаление репозитория
rm -rf .git

//состояние репозитория
git status 

//подготовка файла к сохранению в репозиторий
git add имя файла
git add --all
git add .

//создать коммит
git commit -m 

//создание нового репозитория 
git remote add

//создание ветки
git branch

//переименование веток
git branch -M 

//переключение между ветками
git checkout <название_ветки>

//отправка из локального репозитория в удаленные 
git push

//загрузка репозитория из удаленного в локальное 
git pull
git fetch
git merge



