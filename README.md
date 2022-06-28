 1. Создать внешний репозиторий c названием XML.
 2. Клонировать репозиторий XML на локальный компьютер.
 	git clone https://github.com/Strielka/XML.git
 3. Внутри локального XML создать файл “new.xml”.
 	cd XML
 	vim new.xml
 4. Добавить файл под гит.
 	git add new.xml
 5. Закоммитить файл.
 	git commit -m "add new.xml"
 6. Отправить файл на внешний GitHub репозиторий.
 	git push
 7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
 	<name>Lana</name>
	<age>23</age>
	<pets>1</pets>
	<future_desired_salary>500</future_desired_salary>
 8. Отправить изменения на внешний репозиторий.
 	git commit -am "add modify new.xml"
	git push
 9. Создать файл preferences.xml
 	vim preferences.xml
 10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
 	<favourite_film>The_Butterfly_Effect</favourite_film>
    <favourite_serial>Lost</favourite_serial>
    <favourite_food>strawberry</favourite_food>
    <favorite_season>summer</favorite_season>
    <country_I_would_like_to_visit>Norway</country_I_would_like_to_visit>

 11. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
 	vim skills.xml
 	<s1>Linux_terminal_(GitBash)_commands</s1>
    <s2>Visual_Studio_Code</s2>
    <s3>JS_functions</s3>
    <s4>Chai_JS</s4>
    <s5>Postman</s5>
    <s6>Git_Draw</s6>
    <s7>Git_branch_merge</s7>
    <s8>ClientServer</s8>
    <s9>Postman_scripts_environment</s9>
    <s10>Form_testing</s10>

 12. Сделать коммит в одну строку.
	git commit -am "preferences & skills"
	or   git add . && git commit -m 'Update file'
 13. Отправить сразу 2 файла на внешний репозиторий.
 	git push
 14. На веб интерфейсе создать файл bug_report.xml.
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 18. Синхронизировать внешний и локальный репозиторий XML
 	git pull
