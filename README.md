# TextMate
TextMate is a full-stack web application designed for personal book and note management. It allows users to securely authenticate, create, read, update, and delete (CRUD) their books and notes. The application provides a seamless and responsive user interface for easy navigation and efficient management.


## 🚀 Features

User Authentication: Secure login and registration system. <br/>
Book Management: Add, update, delete, and organize personal books. <br/>
Note Management: Create, edit, and delete notes. <br/>
Responsive UI: Optimized for various screen sizes, including mobile and tablet devices. <br/>
CRUD Operations: Complete functionality to manage books and notes efficiently. <br/>

## 🛠️ Tech Stack
Node.js: Backend runtime environment. <br/>
Express.js: Web framework for building the backend API. <br/>
React.js: Frontend library for creating dynamic user interfaces. <br/>
MongoDB: NoSQL database for storing user data, books, and notes. <br/>

```bash
npm install && npm start
```

#### Database Connection

1. Import connect.js
2. Invoke in start()
3. Setup .env in the root
4. add MONGO_URI(database connection), JWT_SECRET(key used to create the token) in .env

#### Routers

- auth.js
- book.js
- note.js
