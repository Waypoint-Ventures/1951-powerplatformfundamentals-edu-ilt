# Lesson 1: Introduction to queries

## Topic 1: Create a basic query

### Activity: Show me how

This is a teacher-led demonstration to show you the various ways to create a query in an Access database.

#### Resources required

-   Open L0_T0_act_csa.accdb in this lesson’s Learning Activity Resources.

#### Activity instructions

Pay close attention and follow along as your teacher demonstrates how to create and run queries in Access. For each question that we answer with a query, fill in the results in the tables shown below.

**Question 1:** *"How can I find the first and last name of every customer in the database?"*

| | | |
| --- | --- | --- |
| **Field** | FirstName | LastName |
| **Table** | tblCustomers | tblCustomers |
| **Sort** | Ascending | Ascending |
| **Show** | ✔ | ✔ |
*Table 1: Query that lists the first and last name of all customers*

**Question 1 Results:**

| FirstName | LastName |
| --- | --- |
| &nbsp; | &nbsp; |
| &nbsp; | &nbsp; |
| &nbsp; | &nbsp; |
| &nbsp; | &nbsp; |
| &nbsp; | &nbsp; |
*Table 2: Results of query that lists the first and last name of all customers*

**Question 2:** *"How can I find the city and state of every customer in the database?"*

| | | |
| --- | --- | --- |
| **Field** | City | State |
| **Table** | tblCustomers | tblCustomers |
| **Sort** | | |
| **Show** | ✔ | ✔ |
*Table 3: Query that lists the city and state of all customers*

**Question 2 Results:**

| City | State |
| --- | --- |
| &nbsp; | &nbsp; |
| &nbsp; | &nbsp; |
| &nbsp; | &nbsp; |
| &nbsp; | &nbsp; |
| &nbsp; | &nbsp; |
*Table 4: Results of query that lists the city and state of all customers*

### Try-it: Create a basic query

🔵 In this try-it activity, you will open an existing database and create a basic query as directed in the following instructions.

#### Scenario

You've been tasked to use the database to streamline the shipping process. It's important to correctly pack and organize boxes for efficient delivery.

#### Resources

You will need the following resources for this try-it:

-   Open **L0_T0_try_csa_starter.accdb** in this lesson’s Learning Activity Resources.

#### Instructions

The following are the general tasks that you need to perform during this try-it:

1.  Create a new query using the **Design View**. 
1.  Add the **tblCustomers** table to the new query.
1.	Create two query fields with the following settings:
    | | | |
    | --- | --- | --- |
    | **Field** | State | City |
    | **Table** | tblCustomers | tblCustomers |
    | **Sort** | Ascending | Ascending |
    | **Show** | ✔ | ✔ |
    *Table 5: Select only city and state fields*
1.	**Run** the query.
1.	Observe the results of the query. The query should return an alphabetical list of cities, listed by state (also alphabetically) in which our customers reside.