### XML
 21. Создать внешний репозиторий c названием XML:
     + GitHuB > reposytori > new > XML > add README file > create repository
 22. Клонировать репозиторий XML на локальный компьютер:
     + в терминале git clone https://github.com/DaryaShramko/XML.git
 23. Внутри локального XML создать файл “new.xml”:
     + cd XML cat > new.xml
 24. Добавить файл под гит:
     + git status  >  git add new.xml > git status  
 25. Закоммитить файл:
     + git commit -m "send"  
 26. Отправить файл на внешний GitHub репозиторий:
      + git push
 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML: cat > new.xml>
 ````
 <AboutMe>
 <MyName>Darya Shramko </MyName>
 <age>25</age>
 <MyPets>
 <DogsName>Roki</DogsName>
 <Rat1>Shura</Rat1>
 <Rat2>Mura</Rat2>
 <Fish>Eduard</Fish>
 </MyPets>
 <MySalary>500</MySalary>
</AboutMe>
  CTRL + C
  `````
 28. Отправить изменения на внешний репозиторий:
      + git status, git add new.xml, git status , git commit -m "change" git push 
 29. Создать файл preferences.xml:
     + cat > preferences.xml
 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML:

````
<Preferences>

<FavouriteSeason>Every season</FavouriteSeason>

<Movie>All genre other than horror</Movie>


<CountryWhichIWantToVisit>

<Country1>Czech</Country1>

<Country2>Spain</Country2>

<Country3>Georgia</Country3>

</CountryWhichIWantToVisit>

</Preferences> 
 CTRL + C
 ````
 31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML:
  cat > 
````
<MySkillsAfterCourse>

<Skill1>Jmeter</Skill1>

<Skill2>GitBash</Skill2>

<Skill3>Some script</Skill3>

<Skill4>Postman</Skill4>

<Skill5>Android Studio</Skill5>

<Skill6> Xcode </Skill6>

<Skill7>Charlie</Skill7>

<Skill8>SQL</Skill8>

</MySkillsAfterCourse> 
> CTRL + C
````

 32. Сделать коммит в одну строку:
     + git status && git add . && git status && git commit -m "change" 
 33. Отправить сразу 2 файла на внешний репозиторий:
     + git push
 34. На веб интерфейсе создать файл bug_report.xml:
     + GitHub > add new > bug_report.xml
 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе:
    + Commit Changes 
 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML:
     + зайти в репозиторий, нажать на bug_report.xml > edit file 
````
<BugReport>

<summary>PHP_error_appears_in_window_after_input_SQL_request_in_lield_of_login </summary>

<description>:if_enter_SQL_request_in_lield_of_login_and_press_Поехали_button_PHP_error </description>

<RequitementID> no </RequitementID>

<ReproducedOn> Chrome </ReproducedOn>

<Reproducibility> always </Reproducibility>

<Workaround> no </Workaround>

<StepsToReproduce> Open_page_via_URL_http:megatask_Enter_DB_request_(SELECT_FROM_users_WHERE_u_ul_LIKE_in_field_Enter_correct_password__in_field_Press_Поехали_button </StepsToReproduce>

<severity> minor </severity>

<priority> no </priority>

</BugReport>
````

 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе:
     + comit changes
 38. Синхронизировать внешний и локальный репозиторий XML:
     + git pull
