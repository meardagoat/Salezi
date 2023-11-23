# Cloudly - FNAC API Backend

Cloudly is a company dedicated to providing professional services, including software development and IT solutions. We have recently won a contract with FNAC to build an MVP for a new API. This backend application provides a means to manage stocks and sales of products for each of the partner sellers. 

## Application Overview

This application is built using Strapi, with a connection to a SQLite database. It implements a role-based access control with three roles: Super Admin, Fnac Manager, and Seller. 

- **Super Admin**: Has full control over the application.
- **Fnac Manager**: Can view and edit all data, and validate seller transactions.
- **Seller**: Can view and edit their own products and request new transactions.

Note that only Super Admin and Fnac Manager have access to the Admin Panel. Sellers do not have access to it. This application only concerns the back office interface of Strapi.

## Setup

To get the server running, follow these steps:

1. Clone the repository: `git clone https://github.com/your-github-username/cloudly-FNAC-API.git`
2. Navigate to the project directory: `cd cloudly-FNAC-API`
3. Install the dependencies: `npm install`
4. Start the server: `npm run start`

## Usage

Once the server is running, you can interact with the API using Postman. We have provided a Postman collection in JSON format that tests and covers all relevant routes for the Seller role.


