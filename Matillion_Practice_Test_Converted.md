
# Practice Exam

Click on the **Answer** button for the correct answer and its explanation.

If this practice exam has been helpful to you please share it with others and react to this below.

---

1. You need to capture the row count from a write component in Matillion. How best do you do this?
    - A. Add a SQL component to the canvas after the write component and execute a SELECT COUNT(*) command. Write the output to a variable.
    - B. View the Tasks window and make a note of the row count each time the job runs.
    - C. Create a variable to store the result. Click on the write component click Export then Edit before mapping the 'Row Count' to your target variable.
    - D. You cannot obtain the row count from Matillion.

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: C
    <br>Explanation: Creating a variable and using the Export window to map the output to the target variable is the right approach. This allows you to add a fixed flow component to pick up the variable and write it to an audit table, for example.
    </details>

---

2. Which of the following is not a valid indicator for the detect changes component?
    - A. Deleted
    - B. Duplicate
    - C. New
    - D. Changed

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: B
    <br>Explanation: 'Duplicate' is not a valid indicator.
    </details>

---

3. It is possible to export and import jobs between projects using the project menu?
    - A. True
    - B. False

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: A
    <br>Explanation: Jobs, environments, and variables can be exported from one Matillion ETL instance to be imported into another using the Import/Export project menu.
    </details>

---

4. What is the maximum number of versions Matillion recommends?
    - A. 5
    - B. 10
    - C. 100
    - D. 12

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: B
    <br>Explanation: No more than 10 versions are recommended in Matillion.
    </details>

---

5. Which of the following can you not select from when in the import/export screen?
    - A. Environment Variables
    - B. Environment
    - C. Job Variables
    - D. Jobs

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: C
    <br>Explanation: Exporting/Importing jobs via the project menu allows selection of jobs, environment, and environment variables. Job variables are always included.
    </details>

---

6. Which of the following statements is true about JavaScript expressions in Matillion?
    - A. JavaScript expressions are available to use as parameter values within Matillion ETL components.
    - B. JavaScript is not supported.
    - C. JavaScript expressions are supported as default values for variables.

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: A
    <br>Explanation: JavaScript expressions are only available to use as parameter values within Matillion ETL components.
    </details>

---

7. “The rollback component only affects ___ statements”
    - A. TCL
    - B. DML
    - C. DDL

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: B
    <br>Explanation: Rollback affects only DML statements but not DDL statements. This means, for example, a Rollback can undo changes to a table's data but not the creation of a table.
    </details>

---

8. What component can be used to produce the column ‘cumulative airtime’?
    - A. Rank
    - B. Window
    - C. Distinct
    - D. Aggregate

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: B
    <br>Explanation: The data is partitioned by flight_date and ordered by airtime. The lower bound of unbounded preceding and the upper bound of current row define a window that starts from the lowest airtime for the date up to the current row, hence an accumulation.
    </details>

