# University Backend – Students API

## 1. Description

A simple REST API for the University App – Student Management.

It allows the React application to retrieve, add, edit and delete students.

All student data is fictional.

## 2. Technologies

- Node.js
- JSON Server 0.17.4
- JSON

## 3. Installation

Clone the repository:

```bash
git clone https://github.com/sirineelayeb/university-app-backend.git
cd university-backend
```

Install dependencies:

```bash
npm install
```

## 4. Start the server

```bash
npm start
```

Server address: http://localhost:3000

Students API: http://localhost:3000/students

Press `Ctrl + C` to stop the server.

## 5. Available endpoints

| Method | Endpoint        | Description      |
| ------ | --------------- | ---------------- |
| GET    | `/students`     | Get all students |
| GET    | `/students/:id` | Get one student  |
| POST   | `/students`     | Add a student    |
| PUT    | `/students/:id` | Update a student |
| DELETE | `/students/:id` | Delete a student |

## 6. Database

Student data is stored in `db.json`.

The project also contains `db.initial.json`, which keeps a backup of the original students.

### Reset the database

To restore the original students:

1. Stop the server (`Ctrl + C`).
2. Run:

```bash
npm run reset-db
```

3. Restart the server:

```bash
npm start
```

## 7. Project structure

```text
university-backend/
├── db.json
├── db.initial.json
├── package.json
├── package-lock.json
└── README.md
```
