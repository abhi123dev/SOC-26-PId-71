# Week 4 Assignment – Backend Foundations

Welcome to your first backend assignment.

Until now, most of what we interact with on the web lives in the browser. But every modern application also has a backend quietly doing the heavy lifting: storing data, handling requests, authenticating users, and making sure everything works behind the scenes.

This week, you’ll build a small backend project to put the concepts you learned into practice.

No complex full-stack app yet. Just solid foundations.

---

## 🎯 What You’re Building

Create a small backend project called **Student API Setup** using **Node.js**, **Express**, and **MongoDB**.

Your goal is to implement the core backend concepts covered in Week 1.

---

## 📌 Features to Implement

Your backend should include the following:

### 1. Backend Project Setup

Set up a proper Node + Express project.

Create a clean folder structure such as:

```bash id="kc6wz1"
src/
├── db/
├── models/
├── utils/
├── app.js
└── index.js
```

Your server should run successfully on a chosen port.

---

### 2. Database Connection

Connect your project to MongoDB using **Mongoose**.

Requirements:

* Use environment variables (`.env`)
* Handle connection errors properly
* Log a success message when connected

Example:

```bash id="s0m0gf"
MongoDB connected successfully
```

---

### 3. Data Modelling

Create a **Student schema** with the following fields:

* Name
* Roll Number
* Branch
* Semester
* Email

Use proper validations and timestamps.

This task is mainly about learning how to think in terms of database schemas.

---

### 4. Custom API Response & Error Handling

Create utility classes for:

* `ApiResponse`
* `ApiError`

Example response:

```json id="jq0hgn"
{
  "statusCode": 200,
  "data": {},
  "message": "Success"
}
```

Example error:

```javascript id="vjlwmr"
throw new ApiError(404, "Resource not found")
```

The goal is to understand how professional APIs maintain consistent responses.

---

### 5. HTTP Practice

Create two simple endpoints:

```bash id="nwdcrk"
GET /health
POST /student
```

Example responses:

For `GET /health`

```json id="gb31ev"
{
  "message": "Backend running successfully"
}
```

For `POST /student`

```json id="8q0hca"
{
  "message": "Student created successfully"
}
```

This task is just to practice HTTP methods and request-response flow.

---

## 💡 Learning Outcomes

By completing this assignment, you’ll practice:

* Setting up a professional backend project
* Connecting Node.js with MongoDB
* Designing schemas using Mongoose
* Writing reusable utility classes
* Understanding HTTP request-response lifecycle
* Thinking like a backend developer

---

## 📤 Submission Instructions

Submit the following:

* GitHub Repository link
* README with setup instructions
* Screenshots of terminal results in README file of week 4 

Submit your assignment here:

### 🔗 [Submission form](-)

## ⏰ Deadline

**Deadline: 28 June, 11:59 PM IST**

Late submissions may not be accepted, so plan accordingly.

---

## 🚨 Final Reminder

> Don’t worry if everything feels new or confusing. Backend development has many moving parts, and that’s completely normal.

The goal is not perfection.
The goal is to build, debug, break things, and learn.

Google errors. Read docs. Experiment.

That’s how real developers learn.

Happy coding! 🚀
