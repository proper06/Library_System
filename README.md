# Library Management System (LCMS) 📚

A web application built with the MERN stack for managing library activities, including member management, book transactions, and more.

## Features 🚀

- **User Authentication:** Admin and Student login functionality.
- **Dashboards:** Separate dashboards for Admin and Student users.
- **Member Management:** Add, update, and manage library members.
- **Book Management:** Add books with details like available copies, issue, return, and reservation tracking.
- **Event Gallery:** Showcase library achievements and events.

---

## Setup 🔧

### Prerequisites
- Install [Node.js](https://nodejs.org/) on your machine.
- Set up a MongoDB database (local or hosted like MongoDB Atlas).

### Steps

1. **Clone the Repository**
   ```
   git clone <repo-url>
   cd <repo-name>
   ```
2. **Frontend Setup**
   ```
   cd client/book-library/
   npm install
   cp .env.example .env
   # Configure environment variables in the `.env` file
   npm run dev
  
3. **Backend Setup**
  ```
  cd server
  npm install
  cp .env.example .env
  # Add your MongoDB connection string (MONOGO_URL) in the `.env` file
  npm start
  ```
4. **Access the Application**
   - Open the browser and navigate to
     http://localhost:5173/

## Technologies 🛠

- ReactJS[Hooks]
- NodeJs
- ExpressJs
- MongoDB

## Screenshots

![1](https://user-images.githubusercontent.com/73348574/205623377-999c0de5-6796-4100-85e6-96e3e7d4fb77.png)
![2](https://user-images.githubusercontent.com/73348574/205632416-bfcc2c19-3f70-4688-bb7e-0ccd83be3038.png)
![3](https://user-images.githubusercontent.com/73348574/205632598-6b009820-20ec-4e9f-92bf-00af92d4f1a4.png)
![4](https://user-images.githubusercontent.com/73348574/205632198-d99fcc8d-903d-4b60-9cec-56f8e0716290.png)
![5](https://user-images.githubusercontent.com/73348574/205631397-2793e97e-3cc6-4b60-8ee1-ec81716b9d6d.png)
![6](https://user-images.githubusercontent.com/73348574/205631670-5dcb6437-afb1-4aaf-87d7-b47c3b01d7b1.png)
![7](https://user-images.githubusercontent.com/73348574/205631804-6c631b5e-8bcd-41c4-bb73-bab6ea8b78f7.png)
![8](https://user-images.githubusercontent.com/73348574/205631977-f393ca09-aa24-42a5-9bd7-d92d471c514c.png)
