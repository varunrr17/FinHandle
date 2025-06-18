# FinHandle

FinHandle is a comprehensive financial management application designed to help users track their income, expenses, and investments effectively. It provides a user-friendly interface to manage personal finances, set budgets, and gain insights into spending habits.

## Features

- **Income Tracking**: Easily record and categorize all sources of income.
- **Expense Management**: Log daily expenses, categorize them, and visualize spending patterns.
- **Investment Portfolio**: Monitor your investments and track their performance.
- **Budgeting Tools**: Set financial goals and create budgets to stay on track.
- **Financial Reports**: Generate detailed reports to understand your financial health.
- **User Authentication**: Secure user login and registration.

## Technologies Used

### Backend

- **Node.js**: JavaScript runtime environment.
- **Express.js**: Web application framework for Node.js.
- **MongoDB**: NoSQL database for data storage.
- **Mongoose**: ODM for MongoDB and Node.js.
- **JWT (JSON Web Tokens)**: For authentication and authorization.
- **Bcrypt**: For password hashing.

### Frontend

- **React**: JavaScript library for building user interfaces.
- **Vite**: Next-generation frontend tooling.
- **Tailwind CSS**: A utility-first CSS framework for rapid UI development.
- **React Router**: For declarative routing.
- **Axios**: For making HTTP requests.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js**: [Download & Install Node.js](https://nodejs.org/en/download/)
- **npm** (Node Package Manager) or **Yarn**: Comes with Node.js, or install Yarn globally: `npm install -g yarn`
- **MongoDB**: [Download & Install MongoDB](https://docs.mongodb.com/manual/installation/)

### Cloning the Repository

```bash
git clone https://github.com/your-username/FinHandle.git
cd FinHandle
```

### Backend Setup

1.  Navigate to the `backend` directory:

    ```bash
    cd backend
    ```

2.  Install backend dependencies:

    ```bash
    npm install
    # or yarn install
    ```

3.  Create a `.env` file in the `backend` directory and add your environment variables. A `config` folder exists within the backend, so this is where the .env would likely be used.

    ```env
    PORT=5000
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    ```

    _Replace `your_mongodb_connection_string` with your MongoDB URI (e.g., `mongodb://localhost:27017/finhandle` for local or a MongoDB Atlas URI)._  
    _Replace `your_jwt_secret` with a strong, random string._

4.  Run the backend server:
    ```bash
    npm start
    # or yarn start
    ```
    The backend server will run on `http://localhost:5000` (or your specified PORT).

### Frontend Setup

1.  Navigate to the `frontend` directory:

    ```bash
    cd ../frontend
    ```

2.  Install frontend dependencies:

    ```bash
    npm install
    # or yarn install
    ```

3.  Run the frontend development server:
    ```bash
    npm run dev
    # or yarn dev
    ```
    The frontend application will be available at `http://localhost:5173` (or the default Vite port).

## Usage

Once both the backend and frontend servers are running, open your web browser and navigate to `http://localhost:5173`. You can then register a new user or log in with existing credentials to start managing your finances.


