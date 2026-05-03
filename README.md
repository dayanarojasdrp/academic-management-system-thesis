# Academic Appointment Management System – Thesis Project

##  About the Project

This repository contains the full documentation of a diploma thesis focused on the design and development of a web-based academic management system.

The system was developed to support the process of appointment, ratification, and removal of:

* Year Lead Professors (PPA)
* Teaching Assistant Students (AA)

at Universidad Central “Marta Abreu” de Las Villas (UCLV).

The solution addresses real institutional challenges related to information dispersion, lack of traceability, and inefficient manual workflows.

---

##  Problem Statement

In the current institutional process:

* Information is collected in multiple formats (documents, emails, spreadsheets)
* There is no centralized system
* Data validation is inconsistent
* Historical tracking is difficult
* Document generation is manual and time-consuming

These limitations reduce efficiency, increase operational workload, and affect the reliability of academic management processes.

---

##  Proposed Solution

A web-based information system designed to:

* Centralize academic appointment data
* Standardize information input
* Automate validation processes
* Support document generation
* Enable historical tracking and traceability
* Improve administrative efficiency

---

##  System Overview

The system is based on a **client-server architecture**:

* **Frontend:** Vue.js (SPA)
* **Backend:** Laravel REST API
* **Database:** MySQL (InnoDB)

The frontend interacts with the backend through RESTful endpoints, while the backend handles business logic, validation, authentication, and data persistence.

---

##  Architecture

* REST API-based communication
* MVC pattern in backend (Laravel)
* Component-based frontend (Vue)
* Role-based access control
* Modular system design

---

##  User Roles

The system supports the following roles:

* **Department Head**

  * Manages PPA and AA assignments
* **Teaching Vice Dean**

  * Reviews and consolidates information
  * Generates official documents
* **Dean**

  * Validates and formalizes decisions

---

##  Main Features

*  Authentication and role-based access
*  Management of PPA (appointments, ratifications, removals)
*  Management of AA (appointments, ratifications, removals)
*  Automatic generation of official documents
*  Historical records and traceability
*  Search and filtering capabilities
*  Audit logging of system actions

---

##  Related Repositories

### Backend (Laravel API)

https://github.com/dayanarojasdrp/api-laravel

### Frontend (Vue Application)

https://github.com/dayanarojasdrp/vue-app-git-github

---

##  Repository Structure

```txt
thesis/
  thesis.pdf
  docs/
    architecture/
    diagrams/
    screenshots/
```

---

##  Screenshots

Screenshots of the system interface will be included here:

* Dashboard
* PPA management
* AA management
* Document generation
* Search and filtering

---

##  Validation and Testing

The system was validated using:

* Functional testing (black-box approach)
* Realistic test data generated with seeders
* Simulation of institutional workflows
* Iterative validation and correction process

The results confirmed:

* Correct execution of core functionalities
* Consistent data storage
* Successful document generation
* Reliable filtering and historical tracking

---

##  Limitations

* Full integration with institutional user systems is pending
* Some validations depend on manually entered data
* Testing was conducted in a controlled environment

---

##  Future Improvements

* Integration with institutional authentication systems
* Advanced reporting and analytics
* Improved document templates
* Performance optimization
* Automated testing coverage
* Deployment in institutional infrastructure

---

##  Academic Context

This project was developed as part of a diploma thesis in Computer Science at UCLV.

The development followed a **hybrid methodology** combining:

* Scrum (iterative development)
* RUP (structured analysis and documentation)

---

##  Author

**Dayana Rojas**
Computer Science Student

---

##  Conclusion

This project demonstrates the design and implementation of a real-world academic management system, addressing institutional inefficiencies through a structured, scalable, and maintainable software solution.
