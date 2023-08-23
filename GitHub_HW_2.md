
### GitHub Homework #2
**1. На локальном репозитории сделать ветки для:**
- Postman
- Jmeter
- CheckLists
- Bag Reports
- SQL
- Charles
- Mobile testing
```
git branch Postman 
git branch Jmeter 
git branch CheckLists 
git branch Bug_Reports 
git branch SQL 
git branch Charles 
git branch Mobile_testing
```
**2. Запушить все ветки на внешний репозиторий**

Создаём внешний репозиторий "GitHub_branches"
```
git push -u origin 'Postman' 'Jmeter' 'CheckLists' 'Bug_Reports' 'SQL' 'Charles' 'Mobile_testing'
```
**3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта**
```
git checkout Bug_Reports
cat > bug_report_template.txt
Bug ID:
Title:
Description:
Created by:
Owner:
Project:
Version:
Environment:
Severity:
Priority:
Status:
Steps to reproduce:
Expected result:
Actual result:
Attachments:
```
**4. Запушить структуру багрепорта на внешний репозиторий**
```
git add . 
git commit -m "file added"
git push
```
**5. Вмержить ветку Bag Reports в Main**
```
git checkout main
git merge Bug_Reports
```
**6. Запушить main на внешний репозиторий.**
```
git push
```
**7. В ветке CheckLists набросать структуру чек листа.**
```
git checkout CheckLists
cat > checklist_template.txt
ID:
Title:
Precondition:
Expected Result:
Actual Result:
Status:
Comment:
```
**8. Запушить структуру на внешний репозиторий**
```
git add checklist_template.txt
git commit -m "file added"
git push
```
**9. На внешнем репозитории сделать Pull Request ветки CheckLists в main**

В репозитории Git_branches перейти в ветку CheckLists → Кликнуть на кнопку "Compare & pull request" → Кликнуть на кнопку "Create pull request" → Кликнуть на кнопку "Merge pull request" → Кликнуть на кнопку "Confirm merge"

**10. Синхронизировать Внешнюю и Локальную ветки Main**
```
git checkout main
git pull
```