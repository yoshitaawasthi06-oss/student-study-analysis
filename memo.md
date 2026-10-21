# Does Studying More Actually Help?

**Data:** Math students (student-mat.csv), 395 students, from the UCI Student Performance dataset.

## What I found
- Study time has only a very weak relationship with the final grade (G3). The correlation is 0.098. Average grades rise a little, from about 10 out of 20 for students who study under 2 hours a week to about 11 for those who study 5-10 hours, then stop rising.
- The earlier period grade (G2) is by far the strongest factor, with a correlation of 0.905.
- Past failures have a moderate negative relationship with G3, at -0.360. More past failures go with lower final grades.

## Advice for students
1. Do not rely on study hours alone. More hours do not guarantee a better grade.
2. Do well early. Grades in earlier periods are the best sign of the final grade, so a weak start is the time to ask for help, not later.
3. If you have failed before, get support early, because past failures go with lower final grades.

## A claim I chose NOT to make
I am not claiming that "studying more causes better grades", or that a good G2 causes a good G3. This data only shows relationships, not causes. Study time is also self-reported in four broad bands, so it is a rough measure. Other things, such as ability or motivation, may affect both study time and grades.

## Limits
38 students have a final grade of 0, and I kept them in the data because they are real students. This covers 395 Math students from two schools, so the results may not apply to every student.
