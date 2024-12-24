# ApexVanguard

**ApexVanguard** is a web application designed for the **Club de chasse Maska** in Quebec, managing hunting competitions across three exciting categories: **underwater fishing**, **big game hunting**, and **bird hunting**.

## Features

- **Competition Management**
  - Organize competitions across three categories.
  - Automated registration closure 24 hours before competition.

- **User Roles**
  - **Administrator**: Manage competitions, users, and system configurations.
  - **Member**: Register for competitions, view rankings, and manage profiles.
  - **Jury**: Evaluate and score participants based on pre-defined criteria.

- **Score and Ranking System**
  - Scores calculated using species weight and difficulty factors.
  - Automated ranking updates for transparency and fairness.

- **Species Database**
  - Detailed characteristics and difficulty ratings for each species.

## Business Rules

1. Only one competition can occur per week.
2. Registration closes automatically 24 hours before a competition.
3. Participants must have a valid hunting license to compete.

## Technical Stack

### Backend
- **Framework**: Spring Boot
- **Security**: Spring Security
- **Database**: Liquibase for version control
- **Mapping and Utilities**: MapStruct & Lombok
- **Testing**: JUnit for unit testing

### Frontend
- **Framework**: Angular 17
- **Styling**: CSS
- **State Management**: RxJS
- **UI Library**: Angular Material

## Getting Started

### Prerequisites
- **Backend**:
  - Java 17+
  - Maven 3+
  - PostgreSQL 13+
- **Frontend**:
  - Node.js 18+
  - Angular CLI 17+

