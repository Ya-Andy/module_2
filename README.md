# module_2
Суть проекта — отследить влияние условий жизни учащихся на их успеваемость по математике.

<a name="ОГ"></a> 
## ОГЛАВЛЕНИЕ
[1. Основная информация.](#ОС:)
[2. Краткая информация о данных.](#КР)
[3. Этапы работы.](#ЭТ)
[4. Результаты.](#РЗ)

<a name="ОС"></a> 
## Основная информация о проекте:

Вас пригласили поучаствовать в одном из проектов UNICEF — международного подразделения ООН, 
чья миссия состоит в повышении уровня благополучия детей по всему миру. 

Необходимо выяснить влияние условий жизни учащихся в возрасте от 15 до 22 лет на их успеваемость по математике, 
чтобы на ранней стадии выявлять студентов, находящихся в группе риска.

Сделать это можно с помощью модели, которая предсказывала бы результаты госэкзамена по математике для каждого ученика школы. 
Чтобы определиться с параметрами будущей модели, необходимо провести разведывательный анализ данных и составить отчёт по его результатам. 

*Датасет, содержащий все доступные на данный момент сведения, находится в файле* **stud_math.csv**

:arrow_up:[к оглавлению](#ОГ)

<a name="КР"></a> 
**Краткая информация о данных** (переменные, которые содержит датасет):

1. **school** — аббревиатура школы, в которой учится ученик 
2. **sex** — пол ученика ('F' - женский, 'M' - мужской) 
3. **age** — возраст ученика (от 15 до 22) 
4. **address** — тип адреса ученика ('U' - городской, 'R' - за городом) 
5. **famsize** — размер семьи('LE3' <= 3, 'GT3' > 3) 
6. **Pstatus** — статус совместного жилья родителей ('T' - живут вместе 'A' - раздельно) 
7. **Medu** — образование матери (0 - нет, 1 - 4 класса, 2 - 5-9 классы, 3 - среднее специальное или 11 классов, 4 - высшее) 
8. **Fedu** — образование отца (0 - нет, 1 - 4 класса, 2 - 5-9 классы, 3 - среднее специальное или 11 классов, 4 - высшее) 
9. **Mjob** — работа матери ('teacher' - учитель, 'health' - сфера здравоохранения, 'services' - гос служба, 'at_home' - не работает, 'other' - другое) 
10. **Fjob** — работа отца ('teacher' - учитель, 'health' - сфера здравоохранения, 'services' - гос служба, 'at_home' - не работает, 'other' - другое) 
11. **reason** — причина выбора школы ('home' - близость к дому, 'reputation' - репутация школы, 'course' - образовательная программа, 'other' - другое) 
12. **guardian** — опекун ('mother' - мать, 'father' - отец, 'other' - другое) 
13. **traveltime** — время в пути до школы (1 - <15 мин., 2 - 15-30 мин., 3 - 30-60 мин., 4 - >60 мин.) 
14. **studytime** — время на учёбу помимо школы в неделю (1 - <2 часов, 2 - 2-5 часов, 3 - 5-10 часов, 4 - >10 часов) 
15. **failures** — количество внеучебных неудач (n, если 1<=n<3, иначе 0) 
16. **schoolsup** — дополнительная образовательная поддержка (yes или no) 
17. **famsup** — семейная образовательная поддержка (yes или no) 
18. **paid** — дополнительные платные занятия по математике (yes или no) 
19. **activities** — дополнительные внеучебные занятия (yes или no) 
20. **nursery** — посещал детский сад (yes или no) 
21. **higher** — хочет получить высшее образование (yes или no) 
22. **internet** — наличие интернета дома (yes или no) 
23. **romantic** — в романтических отношениях (yes или no) 
24. **famrel** — семейные отношения (от 1 - очень плохо до 5 - очень хорошо) 
25. **freetime** — свободное время после школы (от 1 - очень мало до 5 - очень мого) 
26. **goout** — проведение времени с друзьями (от 1 - очень мало до 5 - очень много) 
27. **health** — текущее состояние здоровья (от 1 - очень плохо до 5 - очень хорошо) 
28. **absences** — количество пропущенных занятий 
29. **score** — баллы по госэкзамену по математике

:arrow_up:[к оглавлению](#ОГ)

<a name="ЭТ"></a> 
## Этапы работы над проектом: 

1. Первичный осмотр данных датасет. 
2. Первичный анализ данных в столбцах. 
3. Рассмотреть распределение признака для числовых переменных, устранить выбросы. 
4. Оценить количество уникальных значений для номинативных переменных. 
5. Провести корреляционный анализ количественных переменных. 
6. Отобрать не коррелирующие переменные. 
7. Проанализировать номинативные переменные и устранить те, которые не влияют на предсказываемую величину 'score'. 
8. Cформулировать выводы относительно качества данных и тех переменных, которые будут использованы в дальнейшем построении модели.

:arrow_up:[к оглавлению](#ОГ)

<a name="РЗ"></a> 
## Результаты-работы: 



:arrow_up:[к оглавлению](#ОГ)
