# Description
Boilerplate Api Golang

# Features
- CRUD Operations: Create, Read, Update, and Delete functionality for managing data.
- Excel Import/Export: Ability to import and export data in Excel format.
- Image Upload: Support for uploading images, specifically with OBS Huawei.
- PostgresSQL Database: Integration with PostgresSQL as the database management system.
- Swagger Documentation: Auto-generated API documentation using Swagger.
- 
# Tech Used
![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)![Swagger](https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white) ![Gin Badge](https://img.shields.io/badge/Gin-008ECF?logo=gin&logoColor=fff&style=for-the-badge)

# Getting Start:

### Clone the Repository:
```bash
 git clone https://github.com/byuang/gin-boilerplate.git
 cd gin-boilerplate
```

### Install Dependencies:
```bash
 make install
```

### Configure Environment:
```bash
 cp .env.example .env
```

### Run the program
```bash
 make dev
```

### Init Docs Swagger
```bash
 make doc
```

### Create Table Sql
```bash
 make migration command={create_table_name or alter_table_name_add_email}
```

### Migrate Up
```bash
  make migrateUp
```

### Migrate Down
```bash
  make migrateDown
```

### Migrate Fix
```bash
  make migrateForce command={version}
```

### Migrate Drop
```bash
  make migrateDrop
```

### Swagger Documentation
```bash
 http://localhost:8000/docs/index.html#/
```

The program will run on http://localhost:8000
<!-- </> with 💛 by readMD (https://readmd.itsvg.in) -->
