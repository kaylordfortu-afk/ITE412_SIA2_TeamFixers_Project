# ITE412_SIA2_TeamFixers_Project

# Team Fixers

## Team Members

| Name | Role |
|---|---|
| Kaylord Cabral| Team Leader |
| Jennelyn Lizardo | Documenter |
| Lourences Vargas | Presenter |
| Jordan Maxion | Diagrammer |

---

## Project Title

### FIXIFY

**A Mobile Application for Mobile and Gadget Repair Shops**

---

## Project Overview

FIXIFY is a proposed mobile application that connects customers with mobile and gadget repair shops and technicians.

The application aims to make it easier for customers to find repair services, view available repair shops and services, submit repair requests, communicate with repair providers, and monitor the status of their requests.

Repair shops and technicians can use the system to manage their services, receive customer requests, communicate with customers, and manage repair activities.

The detailed system description and integration requirements will be developed as the project progresses.

---

## Repository Structure

```text
/docs
    Project documentation

/src
    Source code

## REST API

FIXIFY includes a simple REST API implemented using Node.js and Express.

### API Location

```text
/src/api
```

### Running the API

Open a terminal inside `/src/api` and run:

```bash
npm install
node server.js
```

The API will run at:

```text
http://localhost:3000
```

### Available Endpoints

#### Customer Module

| Method | Endpoint         | Description            |
| ------ | ---------------- | ---------------------- |
| GET    | `/customers`     | Retrieve all customers |
| GET    | `/customers/:id` | Retrieve a customer    |
| POST   | `/customers`     | Create a customer      |
| PUT    | `/customers/:id` | Update a customer      |
| DELETE | `/customers/:id` | Delete a customer      |

#### Repair Shop Module

| Method | Endpoint            | Description               |
| ------ | ------------------- | ------------------------- |
| GET    | `/repair-shops`     | Retrieve all repair shops |
| GET    | `/repair-shops/:id` | Retrieve a repair shop    |
| POST   | `/repair-shops`     | Create a repair shop      |
| PUT    | `/repair-shops/:id` | Update a repair shop      |
| DELETE | `/repair-shops/:id` | Delete a repair shop      |

### Testing

The API can be tested using Postman.

The exported Postman collection is located at:

```text
/integration/PostmanCollection.json
```

The current API uses dummy in-memory data and does not require a database.


/tests
    Test cases

/integration
    Integration scripts and configurations
