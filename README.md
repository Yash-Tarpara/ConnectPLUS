# ConnectPLUS – Professional Services DBMS Project

## Objective

**Design and implement a relational database system** for a platform that connects **clients (seekers)** with **service providers (professionals)** across diverse domains such as **housekeeping, beauty services, wedding management, travel, repairs, and more**. The system simulates **real-world workflows** for service discovery, booking, payments, and reviews while maintaining **data consistency, normalization (BCNF), and efficient querying.**

---

## Application Users

- **Seekers** (Users requesting services)
- **Providers** (Professionals offering services)
- **Administrators**

---

## Use Case 

### 1. Seekers
- **Register/Login**
- **Create and manage profiles**
- **Search professionals by service type, skills, location, and rating**
- **Submit service requests and track bookings**
- **Provide ratings and reviews upon completion**

### 2. Providers
- **Register/Login**
- **Set up professional profiles with expertise and pricing**
- **Declare availability and service packages**
- **View incoming requests and accept/reject bookings**
- **Track service history and earnings**
- **Manage reviews and ratings**

### 3. Administrators
- **Monitor platform activity and user interactions**
- **Generate reports on services, revenue, and ratings**
- **Manage low-rated professionals and resolve disputes**

---

## Database Design Highlights

- **ER Diagrams:** Designed comprehensive ER models representing all entities and relationships.
- **Normalization:** All relations normalized to **BCNF** to ensure data integrity and eliminate redundancy.
- **Tables and Keys:**
  - `Seeker`: User information with multiple candidate keys (ID, Email, Contact_No)
  - `Provider`: Professional details and service categories
  - `Hires`: Tracks service bookings and payments
  - `Reviews`: Stores user feedback
  - `Provider_Contact_No`, `Provider_Email`, `Hourly_Worker`, `Monthly_Worker`, and other specialized service tables

---

## Sample Queries

### Seekers
- Retrieve seeker profile by **ID or Contact No**
- Search professionals by **skill, locality, or service type**
- List **ongoing and completed bookings**
- View **review history**

### Providers
- List **incoming service requests**
- Update **availability and pricing**
- Track **service earnings**
- View **cumulative ratings and feedback**

### Administrators
- Generate **monthly revenue reports**
- List **top-rated providers**
- Identify **low-rated professionals**
- Display **most booked services**

---

## Tech Stack

- **Database:** PostgreSQL
- **Query Tool:** pgAdmin
- **ER Modeling:** Draw.io

---
