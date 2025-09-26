# Module: Global Information

The **Global Information** module provides the **core administrative backbone** of the ERP.  
It centralizes all the **user, role, permission, and organizational data** required for the rest of the modules to operate securely and consistently.  

This module acts as the **foundation layer**, ensuring that every transaction, decision, or workflow in the ERP is tied to the correct identity, role, and organizational context. 

---

## Components

1. **Users**
   - Stores basic information about system users (employees, managers, administrators, etc.).  
   - Each user is the starting point for assigning roles and permissions.  

2. **Roles**
   - Defines **group responsibilities** that can be shared across multiple users.  
   - Roles help avoid redundant permission assignments by grouping permissions.  

3. **Permissions**
   - Represents the **atomic actions** or **rights** that can be granted to a role or user.  
   - Permissions are usually linked to rules and policies through logical inference.  

4. **Departments**
   - Represents the organizational structure of the company.  
   - Users belong to one or more departments, which helps control access and reporting.  

5. **Points of Sale (POS)**
   - Manages the different physical or virtual selling points of the business.  
   - Each POS can have its own set of users, roles, and permissions.  
   - Ensures that ERP processes align with real-world distribution channels.  

---

### ( ̿▀̿Ĺ̯▀̿) Math integration (▀̿Ĺ̯▀̿ ̿)
The Global Information module connects directly to **mathematical logic principles**:  

- **Propositional Logic:**  
  - *If a user has Role X, then the user inherits Permissions Y.*  

- **Predicate Logic with Quantifiers:**  
  - *For all users in Sales, assign the Vendor role.*   

- **Inference Rules:**  
  - Use *Modus Ponens* to grant permissions.  
  - Use *Contrapositive reasoning* to enforce restrictions (e.g., inactive users cannot create orders).  
