 vityarthi
 # 5.1 💰 Basic Python Subscription Manager (List Version)

---

## 💡 Overview of the Project

This is a simple, console-based application written in Python designed to help users track their recurring monthly subscription expenses. The program prompts the user to input the name and cost of their services and then calculates and displays the total monthly expenditure.

The core data structure used in this version is a **list of lists**, where each inner list stores the name and cost of a single subscription (e.g., `['Netflix', 15.99]`).

---

## ✨ Features

* **Subscription Entry:** Allows users to continuously add subscription names and costs.
* **Input Validation:** Ensures the cost entered is a valid positive number (floating point).
* **Total Calculation:** Automatically sums all entered subscription costs.
* **Clear Summary:** Displays a formatted list of all entered subscriptions and the final total monthly cost.

---

## 🛠️ Technologies/Tools Used

* **Programming Language:** Python 3 (specifically, Python 3.6+ is recommended for f-string support).
* **Platform:** Any standard command-line interface (CLI) or terminal.
* **Core Libraries:** Standard Python built-in features only (no external dependencies).

---

## 🚀 Steps to Install & Run the Project

Since this is a single-file Python script, installation is minimal.

### Prerequisites

You must have **Python 3** installed on your system.

### Installation & Execution

1.  **Save the Code:** Save the provided Python code into a file named `subscription_manager.py`.
2.  **Open Terminal:** Navigate to the directory where you saved the file using your terminal or command prompt.
    ```bash
    cd /path/to/your/project/folder
    ```
3.  **Run the Script:** Execute the file using the Python interpreter.
    ```bash
    python subscription_manager.py
    ```

The program will immediately start by greeting you and asking for the first subscription name.

---

## 🧪 Instructions for Testing

Follow these steps to test the key functionalities of the application:

1.  **Start the script** as shown above: `python subscription_manager.py`

2.  **Test Normal Data Entry:**
    * Enter **'Netflix'** for the name.
    * Enter **'15.99'** for the cost.
    * Enter **'Spotify'** for the name.
    * Enter **'10.99'** for the cost.

3.  **Test Input Validation (Non-numeric):**
    * Enter **'Hulu'** for the name.
    * When prompted for the cost, enter **'ten dollars'**.
    * *Expected Result:* The program should display an "Invalid input" message and re-prompt you for a valid number.
    * Enter **'7.99'** to continue.

4.  **Test Input Validation (Negative Cost):**
    * Enter **'Gym'** for the name.
    * When prompted for the cost, enter **'-50'**.
    * *Expected Result:* The program should display a "Cost cannot be negative" message and re-prompt you for a positive value.
    * Enter **'50.00'** to continue.

5.  **Exit and View Summary:**
    * When prompted for the next subscription name, enter **'done'**.
    * *Expected Result:* The program should break the input loop, print a list of all your entered subscriptions, and display the final total monthly cost (which should be $84.97 based on the examples above).
