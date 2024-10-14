The purpose of this document is to define the functional and non-functional requirements for the Personal Expense Tracker project. The system here is designed to help users manage their personal finances by allowing them to set budgets, track expenses, view reports and securely manage their financial data. It ensures accessibility on both desktop and mobile maintaining high level security and performance.

# Functional Requirements

1. **User Authentication and Profile Management**
    1. The system shall allow users to register for an account using an email address and password.
    2. The system shall allow users to log in securely using their credentials.
    3. The system shall implement a Remember me option to keep users logged in across sessions.
    4. The system shall allow users to reset their password via an email-based recovery process.
    5. The system shall allow users to log out securely from any device.

2. **Budget Management**
    1. The system shall allow users to input their monthly income and expected expenses.
    2. The system shall allow users to categorize expenses into different categories and add new ones (food, utilities, rent etc. )
    3. The system shall send a notification when the user spends more than the set predefined limit.
    4. The system shall allow users to set a budget for each expense category.

3. **Expense Tracking**
    1. The system shall allow users to manually add expenses with details such as date, amount, category, and description.
    2. The system shall allow users to edit or delete expenses.
    3. The system shall allow users to filter expenses by date, category, or amount.

4. **Reporting**
    1. The system shall generate a report of the expenses summarizing everything or customized
    2. The system shall allow users to view reports in graphical and textual formats.
    3. The system shall allow users to export reports in CSV or PDF format.

5. **User Settings**
    1. The system shall allow users to change their preferred currency.
    2. The system shall allow users to customize notification preferences


# Non-Functional Requirements

1. **User Experience**
    1. The system shall be responsive on both desktop and mobile
    2. The system shall have a user-friendly interface that allows primary actions to be completed within 2 clicks.

2. **Performance and Scalability**
    1. The system shall be able to maintain an uptime of at least 99.5%, ensuring high availability to users
    2. The system shall be compatible with all major web browsers

3. **Security**
    1. The system shall encrypt all the user data to maintain security and confidentiality
    2. The system shall comply with two-factor authentication (2FA) for added security during login.
    3. The system shall enforce strong password policies, requiring at least 8 characters, a mix of uppercase and lowercase letters, numbers, and special characters.

4. **Data Privacy and Compliance**
    1. The system shall comply with relevant data protection regulations to ensure user privacy.
    
