# Honey Rae Repairs

Honey Rae Repairs is a basic CRUD application designed for a hardware tech repair shop. The app allows **customers** to create service tickets for their hardware issues and **employees** to claim and manage those tickets. This project was built using **React** and **Vite**, marking my first experience transitioning from vanilla JavaScript to React.

## Project Overview

This app facilitates smooth communication between customers and employees of the repair shop by streamlining the process of creating and managing repair tickets.

### Features:
- **Customer Functionality**:
  - Create a ticket for hardware issues.
  - View status updates for created tickets.
  
- **Employee Functionality**:
  - Claim tickets submitted by customers.
  - Update the status of claimed tickets (e.g., in-progress, completed).

- **CRUD Operations**:
  - **Create**: Customers create repair tickets.
  - **Read**: Employees and customers view ticket status and details.
  - **Update**: Employees update ticket progress or claim tickets.
  - **Delete**: Option to remove tickets if needed.


## Installation

To run Honey Rae Repairs locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/honey-raes-api.git
    ````

2. Navigate to to the project directory:
    ```sh
    cd honey-raes-api
    ```

3. Start the development server:
    ```sh
    json-server database.json -p 8088 --watch
    ```
