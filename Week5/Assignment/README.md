# Week 5 Assignment – Build Real Backend APIs

Welcome to your Week 5 backend assignment.

This week, you will extend your Week 5 project by implementing actual API architecture with routers, controllers, authentication flow, and advanced database queries.

---

## 🎯 What You’re Building

Upgrade your **Student API Setup** into a more functional backend.

Your goal is to implement real-world backend architecture and API logic.

---

## 📌 Features to Implement

Your backend should include the following:

### 1. Router and Controller Architecture

Refactor your project to include:

```bash id="9hf26u"
src/
├── controllers/
├── routes/
├── models/
├── db/
├── utils/
```

Create separate route and controller files.

---

### 2. Register Controller

Create a student registration API.

Endpoint:

```bash id="06csh8"
POST /api/students/register
```

Required fields:

* Name
* Roll Number
* Branch
* Semester
* Email
* Password

Requirements:

* Validate inputs
* Check duplicate email
* Save student in database

---

### 3. Authentication

Implement login using:

* Access Token
* Refresh Token

Create routes:

```bash id="58ps5u"
POST /login
POST /refresh-token
POST /logout
```

The goal is to understand token-based authentication flow.

---

### 4. Update Controller

Create an endpoint to update student profile.

Example:

```bash id="v8zd8n"
PATCH /student/:id
```

Allow updating:

* Name
* Semester
* Branch

---

### 5. Subscription Schema

Add a feature where students can follow other students.

Example:

* Senior-junior mentorship
* Study circles

Design a schema to store subscriptions.

---

### 6. Aggregation Pipeline

Create at least one aggregation query.

Examples:

* Count students branch-wise
* Count students semester-wise
* Most common branch

Use aggregation pipeline operators such as:

* `$match`
* `$group`
* `$project`

---


## 💡 Learning Outcomes

By completing this assignment, you’ll practice:

* Router-controller architecture
* Real authentication flows
* Update operations
* Relationship modelling
* Aggregation pipelines
* Writing cleaner backend code

---

## 📤 Submission Instructions

Submit the following:

* GitHub Repository link
* README with setup instructions
* Screenshots of API testing (Postman/browser)

Submit your assignment here:

### 🔗 Google Form Submission

**[Submission Form](https://forms.gle/w2pcMh5aG4aFZHCy5)**

---

## Deadline

**Deadline: July 5th, 2026 11:59 
PM**

---

## Final Reminder

> Backend development gets more interesting when data relationships and real business logic enter the picture.

Don’t panic if aggregation feels difficult at first.

Most developers struggle initially with MongoDB pipelines.

Practice, experiment, and debug patiently.

Happy coding! 🚀
