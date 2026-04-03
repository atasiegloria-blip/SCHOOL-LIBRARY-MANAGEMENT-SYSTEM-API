# School Library Management API

## 📌 Project Description
This is a RESTful API built using Node.js, Express.js, and MongoDB.  
It manages a school library system including Authors, Books, Students, and Library Attendants.


## ⚙️ Tech Stack
- Node.js
- Express.js
- MongoDB (Mongoose)


## 🚀 Features
- Create, read, update, delete Authors
- Manage Books with multiple authors
- Register Students and Library Attendants
- Borrow and Return Books
- Populate related data (authors, student, attendant)



## 🔁 API Endpoints

### Authors
- POST /authors
- GET /authors

### Students
- POST /students
- GET /students

### Books
- POST /books
- GET /books
- POST /books/:id/borrow
- POST /books/:id/return



## 🧪 Testing
All endpoints were tested using Postman.



## 📸 Screenshots

### Borrow Book
![Borrow](./borrow.png)

### Get Book (Populated Data)
![Get Book](./get-book.png)

### Return Book
![Return](./return.png)


## 🛠️ How to Run

1. Clone the repo
2. Run `npm install`
3. Run `npm run dev`
4. Use Postman to test endpoints


## 🙏 Acknowledgement
Special thanks to my tutor for the guidance and support throughout this project.
