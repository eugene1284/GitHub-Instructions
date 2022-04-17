
## Команды для сохранения удалённого репозитория к себе в локальный репозиторий
1. Создаём локально (у себя на компьютере) папку, открываем её через ПКМ с помощью VSC 
2. git clone https://github.com/profile_name/repository_name.git - выполняем копирование удалённого репозитория repository_name.git расположенного по ссылке https://github.com/profile_name/repository_name.git себе локально
3. cd .\repository_name\ - переходим в директорию repository_name
4. работаем над файлами
5. git pull - команда позволяет скачать актуальное состояние удалённого репозитория на локальный и автоматически смержить с текущей веткой
6. git push - эта команда позволяет отправить нашу версию репозитория на внешний репозиторий

## Инструкция по переносу своего локального репозитория в онлайн репозиторий на github
0. создаём папку и открываем её с помощью VSC
3. git init - инициализируем репозиторий в текущей папке test
4. создаём файл file.md в папке test
5. git add .\file.md - добавляем file.md к локальному репозиторию test
6. git commit -m "initial commit"
7. создаём новый репозиторий на github
8. git remote add origin https://github.com/eugene1284/My-first-repository.git
9. git branch -M main
10. git push -u origin main


### Повторение
git init - инициализируем репозиторий в текущей папке
git add .\file_name - перед добавлением коммита
git commit -m "initial commit" - добавляем коммит
