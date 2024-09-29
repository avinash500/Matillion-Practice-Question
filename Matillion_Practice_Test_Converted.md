
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

---

9. A user wants to capture the row count from a component. Which of the following is the best way to approach this?
    - A. Use a SQL script after the component to select the row count
    - B. Use the export tab of the component to map the row count to a target variable
    - C. Use the row count component
    - D. Go into the task history to find the row count.

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: B
    <br>Explanation: All orchestration components and some transformation components support exporting runtime information into variables during job execution. The component's Export tab allows you to edit mappings between runtime information that the component makes available and variables you have already defined.
    </details>

---

10. If a job variable has a visibility of ‘private’, it cannot be overwritten when the job is called from a Run Orchestration or Run transformation - True or False?
    - A. True
    - B. False

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: B
    <br>Explanation: When a variable is private, it cannot be discovered or overwritten when this job is called from a Run Orchestration or Run Transformation component.
    </details>

---

11. Look at the properties of this component:

    - A. Pivot
    - B. Filter
    - C. Rank
    - D. Map Values

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: D
    <br>Explanation: In this example, the Map Values component was used to replace one value with another in the dataset based on a specified condition.
    </details>

---

12. ‘Shared’ variable behavior is when each branch in a job has an independent copy of that variable - True or False?
    - A. True
    - B. False

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: B
    <br>Explanation: When a variable is copied, each branch in the job has an independent copy of that variable that can hold different values.
    </details>

---

---

11. Look at the properties of this component:
    - A. Pivot
    - B. Filter
    - C. Rank
    - D. Map Values

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: D
    <br>Explanation: In this example, the Map Values component was used to replace one value with another in the dataset based on a specified condition.
    </details>

---

12. ‘Shared’ variable behavior is when each branch in a job has an independent copy of that variable - True or False?
    - A. True
    - B. False

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: B
    <br>Explanation: When a variable is copied, each branch in the job has an independent copy of that variable that can hold different values.
    </details>

---

13. Which of the following is set at the Project group level?
    - A. OAuth
    - B. Passwords
    - C. API Query Profiles
    - D. Shared Jobs

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: B
    <br>Explanation: API Query Profiles, Shared Jobs, and OAuth are set at the instance level.
    </details>

---

14. You have a calculator component which carries out two separate operations on a field. The first casts the data type while the other adds 10% to a numeric field. You wish to split out the casting of the data type to a separate component. Which other component could do this job?
    - A. Lead-lag
    - B. Convert Type
    - C. Aggregate
    - D. Filter

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: B
    <br>Explanation: Convert Type allows converting data types of the input flow.
    </details>

---

15. Which of the following is an enterprise mode feature?
    - A. Versions
    - B. Git Integration
    - C. Custom API query profiles
    - D. Shared jobs

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: B
    <br>Explanation: Git integration is a feature of enterprise mode in Matillion.
    </details>

---

16. You have a list of static numbers you require Matillion to iterate over. Which component is best suited to this task?
    - A. Loop Iterator
    - B. Grid Iterator
    - C. Fixed Iterator
    - D. File Iterator

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: C
    <br>Explanation: The fixed iterator component implements a simple loop over rows of fixed data values.
    </details>

---

17. You can view a sample of table data in your data warehouse from within the Matillion UI - True or False?
    - A. True
    - B. False

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: A
    <br>Explanation: You can click on a write component, click sample, and then click data to see a sample of data in your target data warehouse.
    </details>

---

18. What happens when you use the calculator component to add a new column with the same name as an existing column?
    - A. It will append '_new' to the field name
    - B. It will overwrite the existing column with the same name
    - C. You will get an error

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: B
    <br>Explanation: The Calculator Component adds new columns by performing calculations. Any pre-existing columns that share a name with a created column will be overwritten.
    </details>

---

19. What component was used to transpose the data in the first image to the data in the second image?
    - A. Transpose columns
    - B. Transpose rows
    - C. Unpivot
    - D. Pivot

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: A
    <br>Explanation: The Transpose columns component reshapes data by outputting multiple rows for each individual input row.
    </details>

---

20. You need to share a complex Matillion job with another user. What is the best way to do this?
    - A. Take a screenshot of the job and send it over email
    - B. Export the job as a JSON file and send it to the user to import into their project
    - C. Provide the user access to your job so they can copy it
    - D. Export the job as an XML file and send it to the user to import into their project

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: B
    <br>Explanation: Exporting the job as a JSON file is the best way to share a complex Matillion job.
    </details>

---

---

21. SQL scripts can be used in both transformations and orchestrations. What SQL statement cannot be used in Orchestrations?
    - A. Create
    - B. Update
    - C. Truncate
    - D. Select

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: D
    <br>Explanation: The SQL component in Orchestrations cannot use the SELECT statement. This component is used for DDL statements, whereas the SQL transformation component is used for DML statements.
    </details>

---

22. “An API query profile is a collection of ____ files describing the API.”
    - A. TXT
    - B. JSON
    - C. SQL
    - D. XML

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: D
    <br>Explanation: An API query profile is described using a collection of XML files mapping the API to tables, rows, and columns.
    </details>

---

23. What is the correct syntax to reference a job variable ‘jv_data’ in a Python script?
    - A. context.getVariable(‘jv_data’)
    - B. ${jv_data}
    - C. context.getJobVariable(‘jv_data’)
    - D. jv_data

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: D
    <br>Explanation: Variables become first-class variables in Python and Bash scripts.
    </details>

---

24. You have multiple different environments in Matillion, each requiring a different set of passwords to manage. Assuming you have no access to external password manager tools, how best do you do this?
    - A. In a S3 bucket
    - B. Save the password internally as encoded
    - C. In a file within the Matillion project

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: B
    <br>Explanation: Internal passwords are stored on the Matillion ETL server as encoded. They are not encrypted but merely obfuscated.
    </details>

---

25. You need to use an airport code to map the airport's full name into the data set. Which component allows you to do this?
    - A. Rename
    - B. Map Values
    - C. Rank
    - D. Split field

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: B
    <br>Explanation: The Map Values component replaces one value with another in the dataset based on a specified condition.
    </details>

---

26. You need to loop through rows of data in a table and call another component for each iteration. Which iterator do you use?
    - A. Loop
    - B. Table
    - C. Grid
    - D. File

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: B
    <br>Explanation: The table iterator loops over rows of data within a table or view and runs another component for each row.
    </details>

---

27. The search functionality in Matillion will return results from the following:
    - A. Jobs and components
    - B. Jobs, components, notes, and folders
    - C. Jobs, components, and notes
    - D. Jobs, schedules, components, and notes

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: C
    <br>Explanation: The search tab returns matches for jobs, notes, and components.
    </details>

---

28. The import/export mechanism uses which file format?
    - A. JSON
    - B. XML
    - C. AVRO

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: A
    <br>Explanation: You can export to a JSON file for later import into another instance or for backup purposes.
    </details>

---

29. What component allows you to redefine column names?
    - A. Rank
    - B. Rename
    - C. Table Input
    - D. Convert Type

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: B
    <br>Explanation: The Rename component allows you to redefine column names.
    </details>

---

30. A user creates an expression in a calculator column and names it the same as an existing column. What will happen to the new column?
    - A. An error will occur at runtime
    - B. The new column will overwrite the old column
    - C. The new column will be appended the suffix _new
    - D. The new column will be appended the suffix _copy

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: B
    <br>Explanation: If an expression in a calculator component has the same name as an existing column, the new column will overwrite the old column.
    </details>

---

31. Components in Matillion can connect to other components via a grey output line. What is the functionality of this connection?
    - A. Continue to the next component upon success
    - B. Continue to the next component regardless of success or failure
    - C. Continue to the next component upon failure
    - D. Do not continue to the next component

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: B
    <br>Explanation: Grey/Unconditional lines allow continuation to the next component regardless of success or failure.
    </details>

---

32. Which of the following best describes the Matillion ETL Versioning system?
    - A. Versions are a fail-safe export of all your Matillion jobs
    - B. Versions are created by Matillion’s auto-save feature and allow the user to return to an older state of the project
    - C. Versions represent different branches of the Git integration screen
    - D. Versions create a copy of all jobs in your current project at that point in time

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: D
    <br>Explanation: Matillion's versioning system creates a copy of all the jobs in your current project at that point in time.
    </details>

---

33. Where are join expressions defined in the join component?
    - A. Join properties > join expressions
    - B. Main table > join expressions
    - C. Join expressions
    - D. Joins > join expressions

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: C
    <br>Explanation: Join expressions are defined in the Join Expressions tab.
    </details>

---

34. What is the best way to view the value of a variable at runtime?
    - A. Change the visibility of the job variable from ‘private’ to ‘public’
    - B. Open up the task history and find the runtime information for the variable
    - C. Add an ‘Export’ tab for the variable to display at runtime
    - D. Add a Python script to the job to print out the variable

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: D
    <br>Explanation: Printing out the variable via a Python script will show the value of the variable at runtime.
    </details>

---

35. After the fact table is created, some optional housekeeping is run, which may fail if another vacuum is running elsewhere on the database. What should be done so that the job completes successfully even if the housekeeping fails?
    - A. Success and Successfully
    - B. Success and Unsuccessfully
    - C. Failure and Successfully

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: C
    <br>Explanation: If a housekeeping step fails, the job can still complete successfully if treated as such with the appropriate component.
    </details>

---

36. A job variable with ‘copied’ behavior has a default value of ‘1’. Python scripts ‘A’ and ‘B’ update the variable to different values before an ‘AND’ component is used. What value will the job variable have?
    - A. 1
    - B. The job will fail at runtime
    - C. 2
    - D. 3

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: A
    <br>Explanation: Copied variables reset to default values when passed through 'AND' or 'OR' components.
    </details>

---

37. What does the ‘D’ indicator stand for in the detect changes component?
    - A. Deleted
    - B. Different
    - C. Duplicate
    - D. Dropped

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: A
    <br>Explanation: 'D' indicates that the record has been deleted.
    </details>

---

38. What is the main working version of a project’s code called?
    - A. Main
    - B. Trunk
    - C. Default
    - D. Live

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: C
    <br>Explanation: All projects have a Default Version, which is the main working version.
    </details>

---

39. How many output connectors does an ‘IF’ component have?
    - A. 3
    - B. 1
    - C. 6
    - D. 2

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: A
    <br>Explanation: The If component has three output connectors for true, false, and error cases.
    </details>

---

40. You want to view the value of a variable at runtime. What is the best way to do this?
    - A. Set a breakpoint and view the locals window for the value against the variable
    - B. Add a watch on the variable
    - C. Add a Python script component and print out the variable

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: C
    <br>Explanation: The best way is to use a Python Script component and print the variable value.
    </details>

---

41. You need to back up your jobs and associated metadata in case of failure. What do you do?
    - A. Export the project to XML using the export project option
    - B. Take a snapshot of your EC2 instance
    - C. Back up the EC2 storage
    - D. Export the project to JSON using the export project option

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: D
    <br>Explanation: Exporting the project to JSON is the best way to back up jobs and associated metadata.
    </details>

---

42. Which of the following is **not** at the project level?
    - A. Environment Variables
    - B. API Profiles
    - C. Schedule
    - D. Versions

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: B
    <br>Explanation: API Profiles are set at the instance level.
    </details>

---

43. What component do you use to unpivot your data?
    - A. Transpose
    - B. List
    - C. Pivot
    - D. Aggregate
    - E. Array

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: A
    <br>Explanation: The transpose component maps a set of input columns into new output columns, performing an unpivot.
    </details>

---

44. What does the 'I' refer to in the Indicator field when using the detect changes component?
    - A. Infer
    - B. Insert
    - C. Identical

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: C
    <br>Explanation: 'I' shows the record is identical.
    </details>

---

45. A generate sequence component is shown below. What will the data output in rows be?
    - A. 2810
    - B. 28
    - C. 2610
    - D. 26

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: B
    <br>Explanation: The sequence starts at 2 and adds increments of 6. Any value of 10 is excluded, so the sequence is 28.
    </details>

---

46. What does the 'D' refer to in the Indicator field when using the detect changes component?
    - A. Defered
    - B. Drop
    - C. Deleted

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: C
    <br>Explanation: 'D' shows the record has been deleted.
    </details>

---

47. What does an environment represent in Matillion?
    - A. An environment related to your version of GitHub to support version control
    - B. An environment relates to your specific VM your Matillion service runs upon
    - C. An environment in Matillion ETL describes how your instance connects to a data warehouse

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: C
    <br>Explanation: An environment in Matillion ETL describes how your instance connects to a data warehouse and which credentials to use.
    </details>

---

48. What is the behavior of the blue connector ring?
    - A. Continue on to the next component regardless of success or failure
    - B. Continue on to the next component if failed to execute
    - C. Continue on to the next component if executed successfully

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: C
    <br>Explanation: Blue means to continue on to the next component if executed successfully.
    </details>

---

49. What is the field called which is added to the flow when using the detect changes component?
    - A. Indicator
    - B. CDC Flag
    - C. Flag
    - D. Change type

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: A
    <br>Explanation: The field is called "Indicator" by default and shows the status of each record.
    </details>

---

50. You have a transformation job which detects changes from new incoming data. You now need to insert new rows into the target table as well as update changed records within the same job. Which component do you use to create two copies of the data before filtering for either new or changed records?
    - A. Multicast
    - B. Replicate
    - C. Duplicate

    <details markdown=1><summary markdown='span'>Answer</summary>
    Correct answer: A
    <br>Explanation: The Multicast component sends the output to several components, allowing you to handle new and changed data separately.
    </details>

---


