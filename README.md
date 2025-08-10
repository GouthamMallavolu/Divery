# Divery
# Warehouse & Delivery Partner Management System

A **Java Servlet Pages (JSP)**-based web application that simulates a warehouse and delivery partner system similar to Amazon’s backend operations.  
The project uses **frontend + local backend** integration, connecting to a **localhost database** for managing inventory and delivery assignments.

---

## Features

### Authentication
- **Login system** with **username & password** stored in the local database.
- Role-based dashboards:
  - **Warehouse Dashboard**
  - **Delivery Partner Dashboard**

---

### Warehouse Dashboard
- Add new items to the warehouse stock.
- Update stock quantities.
- View remaining inventory in real-time.
- Changes reflect immediately on the main website inventory.

---

### Delivery Partner Dashboard
- View assigned deliveries.
- Access full delivery details:
  - Delivery address
  - Item description
  - Customer contact
  - Expected delivery date
- Easy-to-read list format for faster processing.

---

### Tech Stack

**Frontend**
- HTML5, CSS3, JavaScript
- JSP for dynamic rendering

**Backend**
- Java Servlet Pages (JSP)
- JDBC for database connectivity

**Database**
- MySQL (running on `localhost`)
