# PERSONAL EXPENSES TRACKING APPLICATION


- ## **What will the application do?**
  The **personal expenses tracking application** aims to help users efficiently track and manage their daily expenditures. Users will be able to input details of expenses, categorize them, set budgets, and review summaries of their spending trends. The application will provide features to assist users in gaining insights into their financial habits and thereby helping them make financially wise decisions.

- ## **Who will use it?**
  The application can be used by individuals from all sorts of backgrounds to analyze their income and spending patterns and further make decisions in an effective way. The emergence of digital systems like these makes information available on the fingertips. The work becomes fully automated and this system increases efficiency and also saves a lot of time. Moreover, now it’s an age of computers, and automating such an organization gives a better look.

- ## **Why is this project of interest to you?**
  The idea of daily expenses has been an integral aspect of my life since I left my hometown and moved to Vancouver to begin my journey at UBC. It is what I resonate with the most in my ongoing life. This is the grounds on which I chose my project topic.

## User Stories:
- As a user, I want to be able to add a new expense record where I can input the amount spent, expense category, date, and a short description of the spending.
- As a user, I want to be able to remove an expense record from my list of expenses.
- As a user, I want to be able to update an expense record that has the given date.
- As a user, I want to be able to view a list of all expenses.
- As a user, I want to be able to reminded to save my expense list to the file.
- As a user, when I start the application, I want to be able to load my expense list from the file.

## Instructions for Grader:
- You can generate the first required action related to the user story "adding an expense record to the list of expenses"
by clicking the "Add Expense" button. It will then prompt you to enter the amount spent, expense category, date, and a
short description of the spending.
- You can generate the second required action related to the user story "removing an expense record from the list of expenses"
by clicking the "Remove Expense" button. It will then prompt you to enter the date for which the expense record
has to be removed.
- You can generate the third required action related to the user story "updating an expense record" by clicking the
"Update Expense" button. It will then prompt you to enter the date for the expense record that you want to update.
- You can generate the fourth required action related to the user story "viewing the list of expenses" by clicking 
the "View Expenses" button. It will display all the expenses in the form of a table.
- You can locate my visual component at the beginning of the application that shows the 
cover page of the "Personal Expenses Tracking Application".
- You can save the state of my application by clicking the "Save Expenses" button.
- You can reload the state of my application by clicking the "Load Expenses" button.

## Phase 4: Task 2
Logs:

Thu Nov 30 19:51:32 PST 2023: Expense added: 30.0

Thu Nov 30 19:51:32 PST 2023: Expense added: 75.0 

Thu Nov 30 19:51:32 PST 2023: Expense added: 150.0 

Thu Nov 30 19:51:32 PST 2023: Expense added: 80.0 

Thu Nov 30 19:51:32 PST 2023: Expense added: 106.0 

Thu Nov 30 19:51:32 PST 2023: Expense added: 40.0 

Thu Nov 30 19:51:32 PST 2023: Expense added: 14.0 

Thu Nov 30 19:51:32 PST 2023: Expense added: 72.0

## Phase 4: Task 3

While analysing my UML diagram, I realised that my GUI class is handling operations related to both JButton and logging events. This violates the single responsibility principle.
A refactoring approach could include extracting the methods used for logging into a separate class to make the code more maintainable.
This will in turn make debugging easier and improve the overall structure of my application.

