PESATRAK
PESATRAK is a financial spending tracker that monitors user expenses via M-Pesa transaction messages. It registers transactions, calculates cumulative spending, and notifies users when they exceed their predefined spending limits. The application is designed with an interactive frontend and a robust backend, with optional integration of the M-Pesa API.

Features
User Registration & Authentication: Secure user authentication using JWT.
M-Pesa Transaction Parsing: Register and categorize M-Pesa transactions for easy tracking.
Spending Limit Alerts: Receive notifications when spending exceeds set limits.
Interactive Dashboard: Visualize your spending patterns with real-time updates.
Transaction Categorization: Automatically categorize expenses or manually edit categories.
Spending Reports: Filter transactions by date, category, or amount and generate reports.
Tech Stack
Frontend:
React: Used to build a dynamic, interactive user interface.
Bootstrap: For responsive design and quick UI development.
React-Router: For navigation and routing between views.
React-Toastify: For notifications (alerts when spending exceeds limits).
Backend:
Node.js: Used for building the backend logic and REST API.
Express: Backend framework for handling HTTP requests and responses.
MongoDB: Database to store user data and transaction details.
JWT (JSON Web Tokens): For secure authentication.
M-Pesa API (Optional): For fetching real-time M-Pesa transactions.
Other Tools:
Mongoose: For managing MongoDB data with schema models.
Axios: For making HTTP requests from the frontend to the backend.
Twilio (Optional): For sending SMS notifications.
