# SQL CRUD Exercises – Notes

## Overview

This is a small set of SQL exercises I did to practice the basics of working with relational databases.

The database is pretty simple and includes:

* students
* courses
* enrollments

---

## How the tables are connected

```text
students ─────┐
              ├── enrollments ─── courses
```

Basic:

* students can join multiple courses
* courses can have multiple students
* enrollments is just the link between them

---

## What I practiced

* inserting data (CREATE)
* selecting data (READ)
* updating records (UPDATE)
* deleting records (DELETE)
* working with foreign keys
* understanding many-to-many relationships
* using JOINs
* using GROUP BY and COUNT
* using LEFT JOIN to find missing data

---

## Exercises breakdown

### 1–3: Insert data

Just adding students, courses, and enrollments.

---

### 4–6: Reading data

* list all students
* list all courses
* show students with their courses using JOIN

---

### 7–8: Updates

* change student info
* change course info

---

### 9–10: Deletes

* delete a specific enrollment
* delete a student and see what happens with related data

---

## Bonus tasks

### 11. Students without courses

Find students that are not enrolled in anything using LEFT JOIN.

### 12. Count courses per student

Count how many courses each student is taking.

---

## What I learned from this

* how tables actually connect in real databases
* how JOINs work in practice
* why foreign keys matter
* how many-to-many relationships are handled
* how important constraints are for data consistency

---

## Final thought

It’s a simple setup, but it helps a lot to understand how real systems like school platforms or online apps structure their data.
