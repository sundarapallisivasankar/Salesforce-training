# Day 3 - Data Modeling

## 1. Difference Between App, Object, Record, and Field

### App
An App in Salesforce is a collection of tools, objects, and tabs used for a specific work purpose.

Example:
College Management App

---

### Object
An Object is like a table in a database that stores similar type of data.

Example:
Student, Faculty, Course

---

### Record
A Record is a single entry inside an object.

Example:
Student Name: Rahul
Roll Number: 101

---

### Field
A Field stores individual information inside a record.

Example:
Name, Email, Phone Number

---

# 2. Standard vs Custom Objects

## Standard Objects
These are already provided by Salesforce.

Examples:
- Account
- Contact
- Opportunity

## Custom Objects
These are created by users based on business needs.

Examples:
- Student
- Faculty
- Department
- Course

---

# 3. College Management System Data Model

## Objects Created
- Student
- Faculty
- Course
- Department

## Relationships

### Department → Faculty
One Department can have many Faculty members.

### Department → Course
One Department can have many Courses.

### Course → Student
One Course can have many Students.

### Faculty → Course
One Faculty can teach many Courses.

## Relationship Type
Lookup Relationships are used because objects are connected but can work independently.

---

# Simple Data Model Diagram

Department
   |
   |---- Faculty
   |
   |---- Course
             |
             |---- Student

---

# 4. Formula Fields

## 1. Full Name
Formula combines First Name and Last Name.

### Why?
It automatically creates the complete name and reduces manual work.

---

## 2. Remaining Seats
Formula:
Total Seats - Enrolled Students

### Why?
Shows available seats automatically without manual calculation.

---

## 3. Student Percentage
Formula:
(Obtained Marks / Total Marks) * 100

### Why?
Percentage is calculated automatically and avoids mistakes.

---

# 5. Validation Rules

## 1. Email Cannot Be Empty

### Why?
Prevents saving student records without contact information.

---

## 2. Student Age Cannot Be Negative

### Why?
Stops invalid age values from being entered.

---

## 3. Course Seats Cannot Exceed Limit

### Why?
Prevents adding more students than allowed capacity.

---

# 6. Reflection – Why Structured Enterprise Data Matters

Companies need structured data because it keeps information organized, accurate, and easy to manage.

Random spreadsheets can create:
- Duplicate data
- Missing information
- Calculation mistakes
- Difficulty in tracking relationships

Structured systems like Salesforce help companies:
- Store data properly
- Connect related information
- Automate calculations
- Prevent invalid data
- Generate reports easily


