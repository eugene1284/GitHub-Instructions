
## Команды для сохранения удалённого репозитория к себе в локальный репозиторий
git clone https://github.com/profile_name/repository_name.git - выполняем копирование удалённого репозитория repository_name.git расположенного по ссылке https://github.com/profile_name/repository_name.git себе локально
cd .\repository_name\ - переходим в директорию repository_name
git pull - команда позволяет скачать актуальное состояние удалённого репозитория на локальный и автоматически смержить с текущей веткой
git push - эта команда позволяет отправить нашу версию репозитория на внешний репозиторий

## Инструкция по переносу своего локального репозитория в онлайн репозиторий на github
git remote add origin https://github.com/eugene1284/My-first-repository.git
git branch -M main
git push -u origin main


### Повторение
git init - инициализируем репозиторий в текущей папке
git add .\file_name - перед добавлением коммита
git commit -m "initial commit" - добавляем коммит
