# sql_developer_assignment3
SQL Developer Assignment 3 — PL/SQL Scripts

Student: SANO DANY
ID: 29271

Approach

For this assignment, I implemented multiple PL/SQL programs covering variables, conditional logic, CASE statements, and loops. The approach involved:

Question 1 — Variables & DBMS_OUTPUT:

Declaring different types of variables (VARCHAR2, NUMBER, BOOLEAN, ROWTYPE).

Using DBMS_OUTPUT.PUT_LINE to display values.

Performing simple logical evaluations, such as determining if a course is “heavy” based on credits.

Question 2 — IF / ELSIF / ELSE Conditions:

Implementing conditional checks for courses, student ages, and employee salaries.

Used NVL function to handle potential NULL values in salary computations.

Question 3 — CASE Statements:

Applied CASE logic to compute grades, department funding status, and employee rank.

Compared computed results with stored values to ensure correctness.

Question 4 — Loops:

Used cursors with LOOP and WHILE to iterate over multiple rows in tables like courses, students, and employees.

Performed accumulations, counts, and classifications, e.g., GPA performance, tuition calculations, and salary analysis.

Question 5 — Combined Challenge:

Integrated multiple concepts: variables, loops, conditionals, and CASE statements.

Generated a comprehensive employee profile report including years of service, pay grade, salary analysis, and department summary.

Lessons Learned

Learned to declare and use different PL/SQL variable types including %TYPE and %ROWTYPE.

Practiced conditional logic to make decisions dynamically based on table data.

Improved my cursor handling skills for iterating over multiple rows efficiently.

Learned to integrate loops, conditionals, and CASE statements for more complex data analysis tasks.

Gained hands-on experience with DBMS_OUTPUT for debugging and reporting results.

Challenges Faced

Handling NULL values in salary and commission calculations required careful use of NVL to avoid errors.

Managing rowtype variables and ensuring correct mapping of columns during SELECT INTO statements was initially tricky.

Writing nested conditions and ensuring logical flow without skipping important checks required attention to detail.

Understanding cursors with loops and knowing when to use EXIT WHEN c%NOTFOUND versus WHILE c%FOUND took some trial and error.

Overall, this assignment helped me strengthen my PL/SQL programming skills and taught me the importance of planning logic before coding
