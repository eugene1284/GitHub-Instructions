# Как сделать pull request

1. Делаем копию - fork (вилка) репозитория себе в аккаунт
2. git clone https://github.com/profile_name/repository_id - перетаскиваем удалённый репозиторий себе в локальный репозиторий через 
3. cd repository_name - переходим в папку клонированного репозитория 
4. git branch new_branch_name - создаём отдельную ветку
5. git checkout new_branch_name - переходим в созданную ветку
6. вносим изменения в проект
7. git add .\file_name
8. git commit -m "добавили изменения"
9. git push изменения в удалённый репозиторий из локального
10. тыкаем кнопочку pull request на github



### Команды для сохранения удалённого репозитория к себе в локальный репозиторий
git clone https://github.com/ilnar-geekbrains/version_control_lection_3.git - команда выполняет копирование репозитория по ссылке
cd .\version_control_lection_3\ - перейти в директорию version_control_lection_3
git pull - команда позволяет скачать актуальное состояние удалённого репозитория на локальный и автоматически смержить с текущей веткой
git push - эта команда позволяет отправить нашу версию репозитория на внешний репозиторий

### Команды для переноса своего локального репозитория в онлайн репозиторий на github
git remote add origin https://github.com/eugene1284/My-first-repository.git
git branch -M main
git push -u origin main

### Повторение
git init - инициализируем репозиторий в текущей папке
git add .\file_name - перед добавлением коммита
git commit -m "initial commit" - добавляем коммит