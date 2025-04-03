1. git status
   красным цеветом измененные файлы (либо созданные).
   зеленым - те файлы которые готовы к записи

2. git add [files] - добавляет файлы в stage (подготовительную область)
   git add . (точка- all) ,git add README.md index.html index.js

3. git commit -m "комментарий" -сделать запись в гит

4. git log / git log --oneline - проверить комиты и инфу
   commit id: , Author: , Date: , название комита initial project

5. git push [репозиторий_url] [branch_ветка]
   git push origin master
   ссылка на реп - git remote -v
   ветка - git branch
