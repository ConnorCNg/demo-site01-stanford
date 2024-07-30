# demo-site01-stanford

## Scope

### Project Goals
The Personal Finance Management App aims to help users manage their personal finances by providing tools for tracking expenses, creating budgets, and generating financial reports. The primary objectives are:
- To provide a user-friendly interface for recording and categorizing expenses.
- To enable users to set and monitor budgets.
- To offer insights and analytics on spending habits through detailed reports and visualizations.

### Key Features
1. **Expense Tracking**
   - Add, edit, and delete expenses.
   - Categorize expenses into predefined or custom categories.
   - Attach receipts or notes to expenses.

2. **Budget Management**
   - Create monthly, quarterly, or yearly budgets.
   - Track spending against the budget in real-time.
   - Receive alerts when nearing or exceeding budget limits.

3. **Financial Reports and Analytics**
   - Generate monthly and yearly expense reports.
   - Visualize spending patterns with charts and graphs.
   - Compare expenses across different periods.

4. **User Accounts and Security**
   - User registration and authentication.
   - Securely store user data with encryption.
   - Options for data backup and recovery.

### Out of Scope
- **Investment Tracking**: This version of the app will not include features for tracking investments or stock portfolios.
- **Multi-Currency Support**: The app will initially support only one currency (USD).
- **Automated Expense Import**: Importing expenses automatically from bank accounts or credit cards will not be included in this version.
- **Mobile App**: The initial release will be a web-based application only, with no native mobile app.

### Assumptions
- Users have a basic understanding of personal finance and budgeting.
- Users will manually input their expenses and incomes.
- The app will be used by individual users, not for business purposes.

### Constraints
- The app must be developed and deployed within 6 months.
- The development team will consist of 4 members: 2 frontend developers, 1 backend developer, and 1 UX/UI designer.
- The project budget is limited to $20,000.

### Dependencies
- **Technology Stack**:
  - Frontend: React
  - Backend: Node.js with Express
  - Database: MongoDB
- **Third-Party Services**:
  - Authentication: Firebase Auth
  - Hosting: AWS
  - Email Notifications: SendGrid

### Deliverables
- A fully functional web application accessible via modern web browsers.
- User documentation, including a user guide and FAQ.
- Technical documentation for developers, including API documentation and system architecture.
- A test suite with unit, integration, and end-to-end tests.
