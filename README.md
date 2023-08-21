## GitHub. HW_2
### 1. На локальном репозитории сделать ветки для:
- Postman
- Jmeter
- CheckLists
- Bag Reports
- SQL
- Charles
- Mobile testing
git clone SSH
cd git_hw_2/
git branch Postman 
git branch Jmeter 
git branch CheckLists
git branch Bag_Reports 
git branch SQL 
git branch Charles 
git branch Mobile_testing

### 2. Запушить все ветки на внешний репозиторий
git push origin --all

### 3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта
git checkout Bag_Reports
vim br.txt
git add .
git commit -m "new add"

### 4. Запушить структуру багрепорта на внешний репозиторий
git push origin Bag_Reports

### 5. Вмержить ветку Bag Reports в Main
git checkout main
git merge Bag_Reports

### 6. Запушить main на внешний репозиторий.
git push origin main

### 7. В ветке CheckLists набросать структуру чек листа.
git checkout CheckLists
vim check.txt

### 8. Запушить структуру на внешний репозиторий
git add .
git commit -m "add check"
git push origin CheckLists

### 9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
выполнить

### 10. Синхронизировать Внешнюю и Локальную ветки Main
git pull
