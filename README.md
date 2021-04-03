## Python Django

---

Django is a high-level Python Web framework that encourages rapid development and clean, pragmatic design. Built by experienced developers, it takes care of much of the hassle of Web development, so you can focus on writing your app without needing to reinvent the wheel. It’s free and open source.

![PythonDjango](python-django.png)

### The road map to become successful Python-Django engineer

#### I am assuming that you already have following knowladge

- Basics of Python
- Basics of OOP
- Basics of Git - commit, push, pull, clone, branch, revert
- A bit of Data structures

#### Before starting learn about followings

- How internet works generally?
  - HTTP protocol
  - Request / Response flow
- What is an API / REST API?
- HTTP Verbs
- HTTP Status Codes
- What is JSON and Serialization
- What is Linux and what are the linux distros
- How to install Ubuntu alongside Windows

### Basic Concepts

- What is Database (relational)

  - What is Table
  - What is Row
  - What is Column
  - Primary Key
  - Unique Key
  - Foreign Key

- Virtual Environment

  - Install virtualenv
  - Activate environment
  - Deactivate environment
  - Then about why do we need a virtualenv

- Start a Django Project

  - Install Django
  - Install DRF
  - Learn about Django structure
  - Learn about Settings File

- Create your First Model

  - Learn about Django ORM existing fields
  - Create simple Model
  - Migrate it
  - Register it to Admin Panel

- Create your First Serialization

  - Learn about Model Serializer
  - Learn about Serializer

- Create your First API with views

  - Visit DRF - Django Rest Framework website and look through it's getting started tutorial
  - Test your API with Postman

- Learn about code formatting
  - AutoPEP8
  - Flake8

Congratulations you are now more than just entry level developer. Now it is time to get into depth

### API in depth

- Learn about API design principles
- Learn DRF Serializers in depth (Relations (1toM, MtoM), Nested Serializers, List Serializers)
- Filtering and Paginating the results
- Documenting your Endpoints
  - [Django Rest Framework-Yet Another Swagger Generator](https://drf-yasg.readthedocs.io/en/stable/readme.html)
- Views in Depth (APIViews, GenericAPIViews, ViewSets)

### User Management System

- Authentication vs Authorization
- Learn different types of authorization
  - Session Based
  - Token Based
  - OAuth2 - just the info is enough, it is better to integrate it using Firebase
  - What is JWT and how it works
    - Django_rest_simplejwt package and basic user log in
- Authentication and Permission Classes
  - Custom Permissions
- Protect your Endoints (at least in two level: admin and user)

### Testing

- Learn Types of Testing
  - Unit
  - Integration
  - E2E
- Python Request Package
- Django/DRF test framework
- APIClient, APITestCase, RequestsClient
- Test Coverage

### Deployment

- WSGI and unix sockets
- NGINX and web servers
- Domain Name Service (DNS)
- HTTP vs HTTPS
- Docker
- Docker Compose
- CI/CD
- Pipelines

## Finishing :)

Now you are already at the level of Junior or Strong Junior (based on how you have learned above listed things).
Now I recommend you to build two or three good projects. Your project and codebase the thing that describes you as a developer that's why do it with all your attention. Below I list some easy projects to get started

1. Todo app
2. Blog
3. Simple e-commerce
4. Q&A (Question and Answer) webplatform
5. ...

Feel free to contribute

###### Side note

Please choose one field in the starting point. It can either be Back-end or Front-end or Dev-Ops or may be QA. You do not have to know all the things when starting, it just slows your learning speed. So Implementing just back-end for above projects is quite enough to get started with job or startup

#### TLDR: Just implement back-end

---

> Whenever you can please espace monolithic hell and migrate towards microservices
