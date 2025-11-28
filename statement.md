📝 Problem Statement
In the modern digital landscape, individuals often subscribe to multiple recurring services (streaming, software, news, etc.). Keeping track of these various subscriptions, their individual costs, and the total monthly expenditure can be challenging. This lack of centralized tracking often leads to budget overruns and difficulty in identifying unnecessary expenses.

The problem this project addresses is the need for a simple, accessible, and free tool that allows a user to quickly input their subscriptions and receive an accurate, consolidated summary of their total recurring financial commitment.

🔭 Scope of the Project
The scope of this initial project is narrow and focused on core data management and calculation in a command-line environment.

In Scope:

Data entry for subscription name and cost.

Input validation to ensure costs are positive, numeric values.

Storage of data using basic Python structures (e.g., list of lists).

Calculation and display of the final total cost.

Handling of input/output (I/O) via the command-line interface (CLI).

Out of Scope (Potential Future Enhancements):

Permanent data storage (e.g., saving to a file or database).

Advanced features like deleting, modifying, or sorting subscriptions.

Graphical User Interface (GUI) development.

Handling different billing cycles (e.g., annual vs. monthly).

👤 Target Users
The primary target users are individuals who:

Are looking for a quick, no-frills method to budget their monthly expenses.

Are students or individuals with limited technical skills who need a simple tool without complex installations or features.

Are developers or learners who are practicing basic Python scripting and command-line applications.

🌟 High-Level Features
Subscription Data Entry: An iterative prompt system that allows users to input the name and associated monthly cost for any number of subscriptions.

Robust Input Validation: Built-in checks to ensure the user provides valid numerical input for costs, preventing program crashes from non-numeric or negative entries.

Summary Generation: After data entry is complete, the application generates a clear, readable list of all subscriptions entered.

Total Cost Calculation: The application calculates and displays the grand total monthly cost of all services entered, formatted correctly as currency.
