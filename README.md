# Git_Branches
Repo for Git_Homework2


1. На локальном репозитории сделать ветки для:
- Postman
- Jmeter
- CheckLists
- Bag Reports
- SQL
- Charles
- Mobile testing     - git branch имяветки

2. Запушить все ветки на внешний репозиторий - git push --all origin
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта - git checkout BugReports -> vim report.txt 
4. Запушить структуру багрепорта на внешний репозиторий - git add . -> git commit -m "add new report" -> git push -u origin BugReports
5. Вмержить ветку Bag Reports в Main - git checkout main -> git merge BugReports
6. Запушить main на внешний репозиторий. - git push
7. В ветке CheckLists набросать структуру чек листа. -  git checkout CheckLists -> vim checklist.txt
8. Запушить структуру на внешний репозиторий - git add . -> git commit -m "add new checklist" -> git push -u origin CheckLists
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
10. Синхронизировать Внешнюю и Локальную ветки Main - git checkout main -> git fetch -> git pull
