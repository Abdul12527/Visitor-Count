# Visitor Count API

## Overview

Welcome to the Visitor Count API repository! This project is a Java Spring Boot application that provides a simple API for tracking visitor counts. It allows you to perform various operations related to tracking and managing visitors.

## Language and Framework

- Java Spring Boot

## Description

Java-based application built using the Spring Boot framework. The Visitor Count API allows users to manage visitor counts and related information through a set of RESTful endpoints. It includes features such as adding new visitors, retrieving visitor counts, and more.

## Endpoints

### Get Total Hit Count

- **HTTP Method**: GET
- **Endpoint**: `/count`
- **Description**: Retrieves the total hit count for the default URL.

### Get Hit Count for a Specific User

- **HTTP Method**: GET
- **Endpoint**: `/api/v1/username/{username}/count`
- **Description**: Retrieves the hit count for a specific user identified by `{username}`.

### Increase Total Count

- **HTTP Method**: POST
- **Endpoint**: `api/v1/visitor-count-app`
- **Description**: Increase the total visitor count by 1.


### Increment Hit Count for a Specific User

- **HTTP Method**: POST
- **Endpoint**: `/api/v1/count_update/username/{username}/count`
- **Description**: Increments the hit count for a specific user identified by `{username}` also if user doesn't exist it create the user with given username and assign count 1.

## Project Structure

The project is organized into several parts:

1. **Entities**: Contains the data model for visitors and their hit counts.

2. **Controllers**: Defines the API endpoints and maps them to service methods.

3. **Services**: Implements the business logic for the API endpoints.

4. **Repository**: Implements the database(HashMap) and data Manegement logic 

## Getting Started

To get started with the Visitor Count API, follow these steps:

### Prerequisites

Make sure you have the following prerequisites installed:

- Java Development Kit (JDK)
- Maven

### Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/Abdul12527/Visitor-Count.git
2. Navigate to the project directory

    ```bash
    cd Visitor-Count

## Usage

To use the User Management System, you can make HTTP requests to the provided API endpoints using your favorite API testing tool or framework.
