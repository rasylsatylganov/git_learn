cmd
cd d:\Git\git-course

1. Инициализация git новой папки
git init

2. Увидеть статус ветки
git status

3. Добавление на отслеживание
git add <filename>

Удаление на отслеживание
git rm --cached <filename>

Добавление всех файлов
git add .

4. Commit 
git commit -m "сообщение"

5. Увидеть все ветки
git branch

Увидеть все ветки с коммитами
git branch -v

Удаление ветки
git branch -D <name_branch>

6. Создание новой ветки 
git branch <name_branch>

7. Переключение на новую ветку
git checkout name_branch

8. Сливание веток. в master 
git merge <branch_name>

9. Связывание локального git с глобальным github
git remote add origin git@github.com:rasylsatylganov/git_learn.git

10. Отправить проект на удаленный github
git push -u origin <branch_name>

заливаем измнение в проекте
git push