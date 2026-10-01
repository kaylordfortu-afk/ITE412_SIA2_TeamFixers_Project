# FIXIFY Project Overview

## Project Title

**FIXIFY: A Mobile Application for Mobile and Gadget Repair Shops**

---

# 1. System Objectives

FIXIFY aims to provide a convenient platform for customers who need mobile phone and gadget repair services.

Customers may experience difficulty finding reliable repair shops or technicians. They may also need to visit different repair shops to ask about available services, prices, and repair schedules.

FIXIFY aims to provide a centralized platform where customers can search for repair providers, view their services, submit repair requests, communicate with technicians, and monitor the progress of their repair requests.

The system will also help repair shops and technicians manage their services and customer requests through a digital platform.

### Specific Objectives

The system aims to:

1. Provide customers with a platform for finding mobile and gadget repair services.
2. Allow customers to view available repair shops and technicians.
3. Allow customers to view available repair services.
4. Allow customers to submit repair requests.
5. Provide communication between customers and repair providers.
6. Allow repair providers to manage customer requests.
7. Allow repair providers to update repair request status.
8. Provide ratings and feedback for completed services.
9. Integrate different system components into one platform.

---

# 2. Proposed Scope

The proposed FIXIFY system will focus on connecting customers with mobile and gadget repair shops and technicians.

## Customer Module

Customers will be able to:

- Register and log in.
- Manage their account.
- Search for repair shops.
- Search for repair technicians.
- View repair shop profiles.
- View available repair services.
- Submit repair requests.
- Communicate with repair providers.
- Monitor repair request status.
- Rate and review repair providers.

## Repair Shop/Technician Module

Repair shops and technicians will be able to:

- Register and log in.
- Manage their profile.
- Add repair services.
- Update service information.
- Receive repair requests.
- Accept or reject repair requests.
- Update repair status.
- Communicate with customers.
- View customer feedback.

## Administrator Module

The administrator may be able to:

- Manage users.
- Manage repair shops.
- Manage technicians.
- Monitor repair requests.
- Manage reported accounts.
- Monitor system activities.

## Integration Module

The project may integrate:

- User authentication
- Database
- Repair shop information
- Repair services
- Repair requests
- Messaging
- Notifications
- Ratings and feedback
- Location services

---

# 3. Stakeholders

## Customers

Customers are individuals who need mobile phone and gadget repair services.

They will use FIXIFY to find repair providers, view services, submit repair requests, communicate with technicians, and provide feedback.

## Repair Shop Owners and Technicians

Repair shop owners and technicians will use FIXIFY to advertise their services, receive repair requests, communicate with customers, and manage repair activities.

## System Administrator

The system administrator will manage users, repair providers, and system activities.

## Project Team

The project team will design, develop, test, document, and maintain the FIXIFY system.

---

# 4. Tools and Technologies

| Tool/Technology | Purpose |
|---|---|
| Vue.js | Front-end development |
| JavaScript | Application programming |
| HTML | Application structure |
| CSS | Application styling |
| Firebase | Backend services |
| Firebase Authentication | User authentication |
| Firestore | Database |
| Git | Version control |
| GitHub | Repository and collaboration |
| Visual Studio Code | Development environment |
| Postman | API testing |
| Figma | UI/UX design |
| JavaScript APIs | System integration |

---

# 5. Project Limitations

The initial version of FIXIFY will focus on connecting customers with mobile and gadget repair providers.

Advanced features such as online payment, automated gadget diagnosis, delivery services, and advanced analytics may be considered for future development depending on project requirements and available resources.

---

# 6. Conclusion

FIXIFY is a proposed mobile application that aims to connect customers with mobile and gadget repair shops and technicians.

The system will integrate different components including authentication, database services, repair requests, communication, service information, and user feedback.

The GitHub repository will serve as the team's central workspace for documentation, source code, testing files, and integration configurations throughout the semester.

---

## Integration Pattern & Rationale

### Integration Pattern

FIXIFY will use a **REST-based integration pattern** for communication between the mobile application and backend services. The REST API will provide HTTP endpoints for the Customer and Repair Shop modules.

The API will use standard HTTP methods:

* **GET** – retrieve customer and repair shop records
* **POST** – create new customer and repair shop records
* **PUT** – update existing records
* **DELETE** – remove existing records

For the initial implementation, the REST API will use dummy in-memory data. A database may be integrated in a future development phase.

### Rationale

REST was selected because it is simple, lightweight, and suitable for communication between mobile applications and backend services. It uses standard HTTP methods and JSON data, making the API easy to test using Postman and easy to integrate with the planned FIXIFY mobile application.

The REST approach also allows the Customer and Repair Shop modules to remain separate while communicating through well-defined API endpoints. This supports modular development and makes it easier to expand FIXIFY with additional modules such as Repair Requests, Notifications, Messaging, and Ratings in future iterations.
