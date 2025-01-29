# Day-10
git&;Postgresql&;Go

4shanbe , 10 , bahman , 1403

git
---

She will show herself in the projects in the future .

 Postgresql
-----------

filtering data : IN  , NOT IN
------------------------------

... WHERE felani IN (1,2,3,4, ...);    WHERE felani NOT IN (1,2,3,4, ...);

...WHERE bahmani IN ("hasan" , "bahman" , ...);    WHERE bahmani NOT IN ("hasan" , "bahman" , ...);


filtering data :BETWEEN , NOT BETWEEN
--------------------------------------

... WHERE yaroo BETWEEN 1500 AND 1600

... where age BETWEEN 20 AND 30

filtering data : LIKE , NOT LIKE
-----------------------------------

... WHERE first_name LIKE 'Ali%';

... WHERE first_name LIKE '%nian%';

... WHERE first_name LIKE '_Ali%';     it means first character can be any thing and next Ali then any thing

Use the ESCAPE option to specify the escape character.
Use the ILIKE operator to match data case-insensitively.

filtering data : IS NULL , IS NOT NULL
------------------------------------

... WHERE phone_number2 IS NULL; 

INNER JOIN  ... ON
------------------

FROM table_1 INNER JOIN table_2 ON col_1 = col_2;

![image](https://github.com/user-attachments/assets/055e098f-773e-40ff-8097-b7cf76c0c56c)

LEFTJOIN ... ON
------------

FROM table_1 LEFT JOIN table_2 ON col_1 = col_2;

![image](https://github.com/user-attachments/assets/6d0860d2-69a5-4b86-b79d-0281d2263634)

RIGHTJOIN ... ON
------------

FROM table_1 RIGHT JOIN table_2 ON col_1 = col_2;

![image](https://github.com/user-attachments/assets/76faaf42-e7d5-4f80-9659-5471499ada92)


OUTER JOIN ... ON
------------

FROM table_1 OUTER JOIN table_2 ON col_1 = col_2;

![image](https://github.com/user-attachments/assets/a92da86f-c88b-4c1e-817b-39df72eaa608)

SUMMARY

![image](https://github.com/user-attachments/assets/d871c91b-6a59-4d2c-a9a2-0cb79ae506c4)



