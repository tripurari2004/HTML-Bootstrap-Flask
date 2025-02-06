# Modern Application Development V1 Project
# House Hold Service

Welcome to **Household Management System**, a comprehensive web application designed to help users efficiently organize and manage their daily household tasks.

## Functionalities

- **Admin login, professional and user login (RBAC)**
  - A login/register form with fields like username, password etc. for professional, user and admin login
  - The application should have only one admin identified by his role.
  - You can either use Flask security (session or token) or JWT based Token based authentication to implement role-based access control
  - The app must have a suitable model to store and differentiate all the types of users of the app.

- **Admin Dashboard - for the Admin**
  - Admin login redirects to admin dashboard
  - Admin will manage all the users (customers/service professional)
  - Admin will approve a service professional after verification of profile docs
  - Admin will block customer/service professional based on fraudulent activity/poor reviews

- **Service Management - for the Admin**
  - Create a new service with a base price.
  - Update an existing service - e.g. name, price, time_required and/or other fields
  - Delete an existing service

- **Service Request - for the customers**
  - Create a new service request based on the services available
  - Edit an existing service request - e.g. date_of_request, completion status, remarks etc
  - Close an existing service request.

- **Search for available services**
  - The customers should be able to search for available services based on their location, name, pin code etc.
  - The admin should be able to search for a professional to block/unblock/review them.

- **Take action on a particular service request - for the service professional**
  - Ability to view all the service requests from all the customers
  - Ability to accept/reject a particular service request
  - Ability to close the service request once completed*

## Tech Stack

- **Frontend:** HTML, CSS, Bootstrap
- **Backend:** Python, Flask
- **Database:** SQLite

