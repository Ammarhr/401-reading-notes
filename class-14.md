### Access Controls
- **Access Controls** are the selective restriction of resources. **Access Controls** are implemented everywhere in computer systems.
- UNIX files have read, write, and execute permissions assigned to owners, groups, and everyone else.
- Websites have limited access to pages based on the credentials of a user. APIs restrict access to internal and external developers differently.
- In our RESTful APIs, it is important to limit access to clients based on credentials, Limiting what actions a user can preform on a given resource is called Access Control.
- A user can be given a token at signup and login, and that user can pass that token back to the server on requests with limited access controls.
- Once the server parses the token, it can determine if the user is authorized to preform the request.

### Application Flow and Access Control
**A CMS might Allow:**

1. admin users to create categories, content, manage user accounts, and run reports
2. editor users to create, edit and delete existing content, but not see or manage user accounts
3. guest users to access (read) content
4. user users (logged in users) to access (read) content and apply a thumbs-up/down to content, but not change the actual content.

### Role-Based Access Control (RBAC)
 **Role-Based Access Control (RBAC)** is an approach to restricting system access to authorized users. It is used by the majority of enterprises with more than 500 employees, and can implement mandatory **access control (MAC)** or discretionary access control (DAC).