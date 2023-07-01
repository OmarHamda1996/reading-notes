
#Role-Based Access Control (RBAC)

### What is Role-Based Access Control (RBAC) and why is it important?
RBAC is a security approach that limits system access to authorized users and implements access control policies. It is important because it helps manage user privileges, simplify administration, and enhance security by ensuring users have access only to the resources needed for their roles.

### Describe a Role/Permission hierarchy that can be implemented using RBAC.
Example Role/Permission Hierarchy:

Role: Administrator
Permissions: Create User, Delete User, Modify User, Access Admin Panel
Role: Manager
Permissions: View Reports, Edit Team Data
Role: Employee
Permissions: View Reports, View Team Data

### What approach can be taken to implement RBAC?
The approach to implement RBAC involves:
a) Identifying and defining roles based on job functions or responsibilities.
b) Determining the permissions required for each role.
c) Assigning roles to users based on their job roles.
d) Enforcing RBAC policies to control access based on assigned roles.
e) Regularly reviewing and updating role assignments as needed.

### If Authentication is "you are who you say you are," what is Authorization?
Authorization is the process of granting or denying access rights to a user based on their authenticated identity. It determines what actions or resources a user is allowed to access after successful authentication.

### Name three primary rules defined for RBAC.
The three primary rules defined for RBAC are:
a) Role assignment: Users can exercise permissions only if assigned a role.
b) Role authorization: Users' active roles must be authorized.
c) Permission authorization: Users can exercise permissions only if authorized for their active roles.

### Describe RBAC to a non-technical friend.
RBAC is a method that controls and manages access to computer systems. It ensures users have the right level of access based on their roles, allowing them to perform their tasks effectively while preventing unauthorized access to sensitive information.

### What are access rights associated with in RBAC? The user or the role? Explain.
In RBAC, access rights are associated with the role, not the individual user. Users are assigned roles, and their access rights are determined by the permissions associated with those roles.

### When is access rights or authorization activated in RBAC?
Access rights or authorization are activated after a user successfully authenticates themselves by proving their identity through a login process.

###How can RBAC benefit a business?
RBAC benefits a business by improving security, simplifying administration, ensuring compliance with access control policies, increasing productivity, and scaling to accommodate complex permission structures. It helps protect sensitive information, prevent unauthorized access, and ensures users have the necessary access rights to perform their tasks efficiently.

---

#### Learning Goals:

- Understand access control and its importance in computer systems.
- Learn how to implement permissions-based access control using Express and a Postgres Database.
- Gain knowledge of integrating back-end authorization controls and creating a roles system.
- Familiarize myself with using Express middleware and Sequelize middleware/hooks for access control.
- Understand the role of access control in both the back-end (API layer) and front-end (client layer) of an application.
