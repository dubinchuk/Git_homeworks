### GitHub Homework #1
#### JSON
**1. Создать внешний репозиторий c названием JSON.**
 
Перейти на вкладку "Repositories" → Кликнуть на кнопку "New" → Дать название репозиторию в поле "Repository name" → Опционально: поставить чекбокс "Add a README file" → Кликнуть на кнопку "Create repository"

**2. Клонировать репозиторий JSON на локальный компьютер.**
```
git clone https://github.com/dubinchuk/JSON.git
```
**3. Внутри локального JSON создать файл “new.json”.**
```
cd JSON
touch new.json
```
**4. Добавить файл под гит.**
```
git add new.json
```
**5. Закоммитить файл.**
```
git commit -m "file added"
```
**6. Отправить файл на внешний GitHub репозиторий.**
```
git push
```
**7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.**
```
vim new.json
```
Здесь и далее при работе с vim нажать `i` или `Insert` для начала редактирования файла
```
{
	"ФИО":"Дубинчук Евгений",
	"Возраст":35,
	"Количество домашних животных":0,
	"Будущая желаемая зарплата":"100 т.р."
}
```
Здесь и далее при работе с vim для выхода из редактора нажать `Esc` → `:wq` → `Enter`

**8. Отправить изменения на внешний репозиторий.**
```
git commit -am "file update"
git push
```
**9. Создать файл preferences.json**
```
cat > preferences.json
```
**10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.**
```
{
	"Любимый фильм":"Начало",
	"Любимый сериал":"Очень странные дела",
	"Любимая еда":"Мясо по-французски",
	"Любимое время года":"Лето",
	"Страна, которую хотели бы посетить":"Аргентина"
}
```
Здесь и далее при добавлении текста в файл с помощью команды cat нажать `Enter` для перехода на следующую строку и далее `Ctrl+C` для выхода

**11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON**
```
cat > sklls.json
{
        "Tools": "Git Bash, JavaScript, Postman, VS Code, DevTools, DBeaver, Charles Proxy, Fiddler, Jmeter",
        "Programming basics": "JavaScript, Python, SQL",
	"Testing documentation": "Test cases, Check lists, Bug reports",
        "Testing skills": "Manual functional testing, Mobile testing, API testing, Stress testing"        
}
```
**12. Отправить сразу 2 файла на внешний репозиторий.**
```
git add .
git commit -m "new files added"
git push
```
**13. На веб интерфейсе создать файл bug_report.json.**

Зайти в репозиторий JSON → Кликнуть на кнопку с выпадающим списком "Add file" → Выбрать "Create new file" → В открывшемся окошке ввести имя файла "bug_report.json"

**14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.**

Кликнуть на кнопку "Commit new file" → Кликнуть на кнопку "Submit"

**15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.**

Кликнуть по названию файла "bug_report.json" → Кликнуть на иконку "карандаш" → В открывшемся окне добавить запись:
```
{
    "Bug report ID":1,
    "Title":"When the cart contains one item, it is not possible to add a second item via the add to cart button on a product page",
    "Steps to reproduce":{
      "Step 1":"add one item to cart",
      "Step 2":"go to product abc via the search bar",
      "Step 3":"add new item to cart via 'add to cart' button",
      "Step 4":"go to cart"
    },
    "Expected result":"The cart should contain 2 items",
    "Actual result":"The cart contains only 1 item"
}
```
**16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.**

Кликнуть на кнопку "Commit changes..." → Кликнуть на кнопку "Commit changes"

**17. Синхронизировать внешний и локальный репозиторий JSON**
```
git pull
```

#### XML
**1. Создать внешний репозиторий c названием XML.**

Перейти на вкладку "Repositories" → Кликнуть на кнопку "New" → Дать название репозиторию в поле "Repository name" → Опционально: поставить чекбокс "Add a README file" → Кликнуть на кнопку "Create repository"

**2. Клонировать репозиторий XML на локальный компьютер.**
```
git clone https://github.com/dubinchuk/XML.git
```
**3. Внутри локального XML создать файл “new.xml”.**
```
cd XML
touch new.xml
```
**4. Добавить файл под гит.**
```
git add new.xml
```
**5. Закоммитить файл.**
```
git commit -m "new.xml created"
```
**6. Отправить файл на внешний GitHub репозиторий.**
```
git push
```
**7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.**
```
vim new.xml
<?xml version="1.0" encoding="windows-1251"?>
<body>
	<ФИО> Дубинчук Евгений </ФИО>
	<Возраст> 35 </Возраст>
	<Количество_домашних_животных> 0 </Количество_домашних_животных>
	<Будущая_желаемая_зарплата> 100 т.р. </Будущая_желаемая_зарплата>
```
**8. Отправить изменения на внешний репозиторий.**
```
git commit -a -m "new.xml updated"
git push
```
**9. Создать файл preferences.xml**
```
cat > preferences.xml
```
**10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.**
```
<?xml version="1.0" encoding="windows-1251"?>
<body>
	<Любимый_фильм> Начало </Любимый_фильм>
	<Любимый_сериал> Очень странные дела </Любимый_сериал>
	<Любимая_еда> Мясо по-французски </Любимая_еда>
	<Любимое_время_года> Лето </Любимое_время_года>
	<Страна_которую_хотели_бы_посетить> Аргентина </Страна_которую_хотели_бы_посетить>
</body>
```
**11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML**
```
cat > skills.xml
<?xml version="1.0" encoding="windows-1251"?>
<body>
	<Tools> Git Bash, JavaScript, Postman, VS Code, DevTools, DBeaver, Charles Proxy, Fiddler, Jmeter </Tools>
	<Programming_basics> JavaScript, Python, SQL </Programming_basics>
	<Testing_documentation> Test cases, Check lists, Bug reports </Testing_documentation>
	<Testing_skills> Manual functional testing, Mobile testing, API testing, Stress testing </Testing_skills>
</body>
```
**12. Сделать коммит в одну строку.**
```
git add . | git commit -am "preferences.xml & skills.xml added"
```
**13. Отправить сразу 2 файла на внешний репозиторий.**
```
git push
```
**14. На веб интерфейсе создать файл bug_report.xml.**

Зайти в репозиторий XML → Кликнуть на кнопку с выпадающим списком "Add file" → Выбрать "Create new file"

**15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.**

Кликнуть на кнопку "Commit new file" → Кликнуть на кнопку "Submit"

**16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.**

Кликнуть по названию файла "bug_report.xml" → Кликнуть на иконку "карандаш"
```
<?xml version="1.0" encoding="windows-1251"?>
<body>	
	<Bug_report_ID> 1 </Bug_report_ID>
	<Title> When the cart contains one item, it is not possible to add a second item via the add to cart button on a product page </Title> 
	<Steps_to_reproduce>
        	<Step_1> add one item to cart </Step_1>
	        <Step_2> go to product abc via the search bar </Step_2>
        	<Step_3> add new item to cart via 'add to cart' button </Step_3>
	        <Step_4> go to cart </Step_4>
	</Steps_to_reproduce>
	<Expected_Result> The cart should contain 2 items </Expected_Result>
	<Actual_Result> The cart contains only 1 itemt </Actual_Result>
</body>
```
**17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.**

Кликнуть на кнопку "Commit changes..." → Кликнуть на кнопку "Commit changes"

**18. Синхронизировать внешний и локальный репозиторий XML**
```
git pull
```

#### TXT
**1. Создать внешний репозиторий c названием TXT.**

Перейти на вкладку "Repositories" → Кликнуть на кнопку "New" → Дать название репозиторию в поле "Repository name" → Опционально: поставить чекбокс "Add a README file" → Кликнуть на кнопку "Create repository"

**2. Клонировать репозиторий TXT на локальный компьютер.**
```
git clone https://github.com/dubinchuk/TXT.git
```
**3. Внутри локального TXT создать файл “new.txt”.**
```
cd TXT
touch new.txt
```
**4. Добавить файл под гит.**
```
git add new.txt
```
**5. Закоммитить файл.**
```
git commit -m "new.txt created"
```
**6. Отправить файл на внешний GitHub репозиторий.**
```
git push
```
**7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.**
```
vim new.txt
ФИО - Дубинчук Евгений
Возраст - 35
Количество домашних животных - 0 
Будущая желаемая зарплата - 100 т.р.
```
**8. Отправить изменения на внешний репозиторий.**
```
git commit -am "new.txt updated"
git push
```
**9. Создать файл preferences.txt**
```
cat > preferences.txt
```
**10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.**
```
Любимый фильм - Начало
Любимый сериал - Очень странные дела
Любимая еда - Мясо по-французски
Любимое время года - Лето
Страна, которую хотели бы посетить - Аргентина
```
**11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT**
```
cat > skills.txt
Tools - Git Bash, JavaScript, Postman, VS Code, DevTools, DBeaver, Charles Proxy, Fiddler, Jmeter
Programming basics - JavaScript, Python, SQL
Testing documentation - Test cases, Check lists, Bug reports
Testing skills - Manual functional testing, Mobile testing, API testing, Stress testing
```
**12. Сделать коммит в одну строку.**
```
git add . | git commit -m "preferences.txt & sklls.txt added"
```
**13. Отправить сразу 2 файла на внешний репозиторий.**
```
git push
```
**14. На веб интерфейсе создать файл bug_report.txt.**

Зайти в репозиторий TXT → Кликнуть на кнопку с выпадающим списком "Add file" → Выбрать "Create new file"

**15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.**

Кликнуть на кнопку "Commit new file" → Кликнуть на кнопку "Submit"

**16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.**
```
Bug report ID: 1
Title: When the cart contains one item, it is not possible to add a second item via the add to cart button on a product page
Steps to reproduce:
Step 1: add one item to cart
Step 2: go to product abc via the search bar
Step 3: add new item to cart via 'add to cart' button
Step 4: go to cart
Expected result: The cart should contain 2 items
Actual result: The cart contains only 1 item
```
**17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.**

Кликнуть на кнопку "Commit changes..." → Кликнуть на кнопку "Commit changes"

**18. Синхронизировать внешний и локальный репозиторий TXT**
```
git pull
```
