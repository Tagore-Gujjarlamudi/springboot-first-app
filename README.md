# Task Management System

## Project Overview
A Task Management System developed using Spring Boot, Spring Security, MySQL, JPA, and REST APIs. This application allows users to create and manage tasks through REST endpoints.

## Features
- Create Tasks
- View Tasks
- Update Tasks
- Delete Tasks
- MySQL Database Integration
- Spring Security Authentication
- REST API Architecture

## Technologies Used
- Java
- Spring Boot
- Spring Security
- Spring Data JPA
- MySQL
- Maven
- Postman

## Database
Database Name: fullstack_project_db

## API Example

### Create Task
POST /tasks

```json
{
  "title": "Internship Task",
  "description": "Spring Boot Project",
  "status": "Pending"
}
