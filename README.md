# Задание по VCS
Опишем весь процесс: 
1. Создаем проект на GitHub с файлом README
2. Делаем локальный репозиторий: git clone https://github.com/pashmentov96/VCS_COURSE.git
3. Создаем новую ветку с названием develop: git checkout -b develop
4. Вносим изменения. В данном примере будет изменен файл README
5. Добавляем все файлы, которые мы хотим внести: git add README.md
6. Делаем commit с комментарием для всех добавленных файлов: git commit -m "Edited README file"
7. Необходимо задать upstream ветку. Для этого можно использовать команду git push: git push --set-upstream origin develop
8. Для того, что создать pull request, необходимо выбрать две ветки для объединения. В нашем случае: делаем pull request из develop в master
9. Далее этот pull request можно комментировать и после всех правок принять его. 