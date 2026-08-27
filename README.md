# 🦁 Animal Haven Zoo Database

A relational database system designed to manage the operations and data of Animal Haven Zoo, including animals, employees, departments, visitors, events, tickets, bills, and payment methods.

## 📌 Project Overview

This project was developed for  Database I. The main goal is to design and implement a well-structured relational database that helps the zoo efficiently store, manage, and retrieve its data.

The database supports:

Animal and area management
Employee and department management
Visitor information
Events and animal participation
Tickets and ticket types
Bills and payment methods
Employee–visitor guidance
Database queries and data retrieval

## 👥 Team Members

Revan  Abdulsamad	
Taif  Alkatheumi	
Shatha  Alshaikh	
Sara  Algarni	
Lujain  Alqarni	

Group: 5
Course: Database I
Semester: Fall 2023

## 🗄️ Database Design

The database was designed using the following stages:

Problem Analysis and Data Requirements
Business Rules Definition
Entity-Relationship (ER) Diagram
ER-to-Logical Schema Mapping
Database Normalization
Final Database Schema
SQL Implementation
Queries and Data Retrieval

The database was normalized up to Third Normal Form (3NF) to reduce redundancy and improve data integrity.

## 🧩 Main Entities

The system contains the following main tables:

DEPARTMENT
EVENT
AREA
ANIMAL
EMPLOYEE
EMPLOYEE_AGE
EMPLOYEE_SALARY
VISITOR
PAYMENT_METHOD
BILL
TICKET
EVENT_TICKET
AREA_TICKET
GUIDES
PARTICIPATES
HAS

## 🔗 Main Relationships

The database represents several relationships, including:

Employees work for departments.
Employees work in areas.
Employees guide visitors.
Animals belong to areas.
Departments control events.
Animals participate in events.
Visitors pay bills.
Bills use payment methods.
Bills contain tickets.
Areas have area tickets.
Events have event tickets.

## 📋 Business Rules

Some of the main business rules include:

Every employee belongs to one department.
Employees must be at least 18 years old.
Each animal belongs to one area.
Each event has a location and is controlled by a department.
Visitors can be guided by multiple employees.
Animals can participate in multiple events.
Each bill is associated with a visitor and a payment method.
Bills and tickets have a many-to-many relationship.
Area and event tickets are associated with their corresponding areas and events.

## 💻 Implementation

The database was implemented using SQL with tables, primary keys, foreign keys, and constraints.

Examples of implemented constraints include:

PRIMARY KEY
FOREIGN KEY
NOT NULL
CHECK
ON DELETE CASCADE


These constraints help maintain data integrity and enforce the defined business rules.

## 🔎 Queries

The project includes SQL queries for retrieving useful information from the database, such as:

Finding employees who work in the same area.
Retrieving the number of visitors for events.
Finding employees working in the same area as a specific animal.
Retrieving animals participating in events controlled by a specific department.
Counting male employees in departments with multiple employees.


## 📚 Documentation

The complete project report contains:

Full problem definition
Data requirements
Business rules
ER diagram
ER-to-logical schema mapping
Normalization (1NF, 2NF, 3NF)
Final database schema
Complete table creation scripts
Constraint scripts
SQL queries
Query outputs
Database table screenshots

## 🎓 Academic Project

Note: This is a university academic project developed as part of the Database I course during the Fall 2023 semester.

