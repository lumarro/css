|Nivel|Solución|Apunte|
|:---:|:---:|:---:|
|Intro|li:first-child|-|
|Level 1|p:not(.foo)|-|
|Level 2|li:nth-of-type(2n+3) / li:nth-child(2n + 3)|La única diferencia que veo es que nth-of-type pueden ser los elementos del tipo que sean sin que tengan que ser hijos de alguien|
|Level 3|div > *|Selecciona los hijos|
|Level 4|span[data-item]|-|
|Level 5|p ~ span|-|
|Level 6|:enabled|-|
|Level 7|#one,#two,#five,#six,#nine|-|
|Level 8|a + span|-|
|Level 9|#foo > div[class]|-|
|Level 10|div div code:last-child:not(.foo) / div div span + code:not(.foo)|Se pueden concatenar los pseudo-selectores es decir, en este caso seleccionar los code que sean los últimos hijos y que no contengan la clase foo|
|Tiempo|16:09:5 min|-|