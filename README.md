# MCQ Test Application

## Overview
The **MCQ Test Application** is a **web-based platform** designed to help users take and evaluate multiple-choice question (MCQ) tests. Built using **Flask**, a lightweight Python web framework, it offers features like **user authentication**, **test management**, and **result tracking**. The application is fully responsive, ensuring compatibility across various devices and screen sizes.

---

## Features

### 1. **User Authentication**
- **Signup**: Users can create an account by providing a username and password.
- **Login**: Users can log in using their credentials.
- **Logout**: Users can securely log out of their accounts.

### 2. **Test Management**
- **Dashboard**: Users can view their test history and performance.
- **Start Test**: Users can start a new test, which includes 20 randomly selected questions.
- **Submit Test**: Users can submit their answers, and the application calculates the score and displays the result.

### 3. **Result Tracking**
- **History**: Users' test scores and results are saved and displayed on the dashboard.
- **Incorrect Questions**: Users can review the questions they answered incorrectly along with the correct answers.

### 4. **Responsive Design**
The application uses **Bootstrap** to provide a responsive and consistent user interface across different devices and screen sizes.

---

## How to Run the Application

### Step 1: Install Dependencies
Ensure Python and Flask are installed on your system. Use the following command to install Flask:
```bash
pip install flask
```
### Step 2: Run the Application
1. Navigate to the directory containing the `mcq_test_ui.py` file.
2. Run the application using the following command:
   ```bash
   python3 mcq_test_ui.py
   ```
3. The application will be available at:
   ```bash
   http://127.0.0.1:5000/
   ``` 

