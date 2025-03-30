В базах даних створено таблиці, зв‘язки між ними та заповнено їх даними. Вимоги:
a) Таблиця Universities з колонками Id, UniName, City. Один чи більше університет в назві повинен містити букву У (ЛНУ, ЧНУ)
b) Таблиця Faculties з колонками Id, Name, UniversityId (прив’язаний foreign ключем до таблиці Universities).
c) Таблиця Groups з клонками Id, GroupNumber, FacultyId (прив’язаний foreign ключем до таблиці Faculties). 
d) Таблиця Students з колонками Id, Name, Surname, Age, GroupId (прив’язаний foreign ключем до таблиці Groups). 
