This project had a goal to test the ability to analyse a given data set and 
to process the given data.

The task was to analyse the information about a group of students and 
process the data in preparation for a program, that will predict
student's math exam score using certain information about the student.

The values with low correlation to the score had to be found amongst the
tables with numerical values, and T-test had to be done to find the non-numerical
columns with significant difference between the mean values of score amognst
the values of the column.

Two verisions of the code were made, one with data imputation, the other
one is without.
Median imputation was done to fill in the NaN values in the columns with
numerical values in the program "Student Analysis", and no
imputation was done in the program "Student Analysis(no imputation)" to
see if imputation affected the results in any way.

Any correlation coefficiant below 0.8 or above -0.8 was considered
a weak correlation, therefore all the columns with the correlation coefficient
in this range was added to the final Data Frame.

For T-test, 5% level of significance was used. 1% level of significance was
considered, but it was decided to use 5% to avoid accidental loss of data.

Columns in the data set "stud_math.csv" had the following information:

1.school - the abbreviation of the name of the school the student attends.
2.sex - biological gender of a student(M for "Male", F for "Female")
3.age - age of a student(15 to 22)
4.address - the area student lives in(U for "Urban", R for "Rural")
5.famsize - size of the family(LE3 - "3 or less", GT3 - "greater than 3")
6.Pstatus - parents' cohabitation status(T for "Together", A for "Apart")
7.Medu - education of a mother(0 - no education, 1 - 4 years of school,
2 - 5-9 years of school, 3 - 11 years of school, 4 - degree or above)*
8.Fedu - education of a father(see above)
9.Mjob - which area mother's job falls into("teacher" - education,
"health" - healthcare, "services" - civil services,
"at_home" - unemployed or "other" for any other areas)
10.Fjob - which area father's job falls into(see above)
11.reason - reason of applying to school("home" - close to
student's house, "reputation" - school's reputation,
"course" - school's course, "other" for any other reasons)
12.guardian - student's legal guardian(mother, father or other)
13.traveltime - how long does it take for student to reach the school
(1 - less than 15 min, 2 - 15 to 30 min, 3 - 30 to 60 min, 4 - over 60 min)
14.studytime - how much time student spends studying outside the class per week
(1 - less than 2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, 4 - more than 10 hours)
15.failures - number of non-academic failures of a student
16.schoolsup - does student recieve any educational support from the school(yes or no)
17.famsup - does student's family asssits his education directly(yes or no)
18.paid - does student has any extra lessons with a tutor(yes or no)
19.activities - does student take part in extracurricular activities(yes or no)
20.nursery - did student attend nursery(yes or no)
21.studytime, granular - exact time student spends on studying(the number is negative for some reason)
22.higher - does student pursue higher education(yes or no)
23.internet - does student have an internet access at home(yes or no)
24.romantic - is student in a romantic relationship(yes or no)
25.famrel - family relationship(1 - very bad, 5 - very good)
26.freetime - free time outside of school(1 - very little, 5 - a lot)
27.goout - how much time student spends with their friends(1 - very little, 5 - a lot)
28.health - current state of health(1 - very bad, 5 - very good)
29.score - student's math score 

*The numbers reffer to Russian educational system, with no college or A-levels
between the school and university.