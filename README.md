# AgateCompany

AgateCompany is an all-in-one advertising agency management system developed using Go and React. It offers a complete platform to efficiently oversee advertising campaigns, clients, staff, and advertisements.

## Features

- **Client Management**
  - Add, update, and remove clients
  - Track client details and contact information
  - View client-specific campaigns

- **Campaign Management**
  - Create and track advertising campaigns
  - Monitor campaign budgets and costs
  - Assign campaign managers
  - Track campaign status and progress

- **Advertisement Tracking**
  - Schedule and manage individual advertisements
  - Track advertisement progress and run dates
  - Link advertisements to specific campaigns

- **Staff Management**
  - Manage agency staff members
  - Handle staff grades and pay rates
  - Track staff assignments and roles

- **Campaign Manager System**
  - Assign managers to campaigns
  - Track manager responsibilities
  - Monitor campaign performance

## Technology Stack

- **Backend**
  - Go (Golang)
  - Gin Web Framework
  - PostgreSQL
  - SQLx for database operations

- **Frontend**
  - React
  - TailwindCSS
  - Lucide Icons
  - Context API for state management

## Prerequisites

- Go 1.19 or higher
- Node.js 16.x or higher
- PostgreSQL 12 or higher
- Git

### Clients
* `GET /clients` - Get all clients
* `GET /clients/:id` - Get specific client
* `POST /clients` - Create new client
* `PUT /clients/:id` - Update client
* `DELETE /clients/:id` - Delete client

### Campaigns
* `GET /campaigns` - Get all campaigns  
* `POST /campaigns` - Create new campaign
* `GET /campaigns/:id` - Get specific campaign
* `PUT /campaigns/:id` - Update campaign
* `DELETE /campaigns/:id` - Delete campaign
* `PUT /campaigns/:id/manager/:managerID` - Assign manager to campaign

### Advertisements
* `GET /adverts` - Get all advertisements
* `POST /adverts` - Create new advertisement
* `GET /adverts/:id` - Get specific advertisement
* `PUT /adverts/:id` - Update advertisement
* `DELETE /adverts/:id` - Delete advertisement

### Staff
* `GET /staff` - Get all staff members
* `POST /staff` - Add new staff member
* `PUT /staff/:id` - Update staff member
* `DELETE /staff/:id` - Remove staff member
