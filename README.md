# Task Management Backend

This is a Spring Boot backend for managing tasks.

## Overview

This project provides the server side for a task management application. It is built with Spring Boot and is currently in the early stages of development.

### Intended Features

- CRUD operations for tasks
- Assigning tasks to users
- Tracking status and due dates
- Commenting on tasks

Any design documentation will be linked here once available.

## Prerequisites

- **JDK 21** (or newer)
- Maven is provided via the wrapper (`./mvnw`) so a local Maven install is optional.

## Running Tests

Execute the tests using the Maven wrapper:

```bash
./mvnw test
```

This command downloads dependencies and runs unit tests. If the environment restricts network access, dependency resolution may fail.
