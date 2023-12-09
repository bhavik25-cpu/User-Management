Task: Create REST APIs for User Management
Develop REST APIs for:
- Register User (First Name, Last Name, Email, Phone)
- Get User by ID
- Update User (First Name, Last Name, Email, Phone)
- Delete/Disable User
- List All Users with filters (Filters: First Name, Last Name, Email, Phone)
Deliverables:
1. NodeJS Code GitHub Link
2. Postman Collection Link
Test Expectations:
1. All coding standards should be followed for NodeJS, REST API
2. Code should be optimised for performance
3. All tables should be created using database migrations

===============================================================================================================

1. NodeJS Code GitHub Link

https://github.com/bhavik25-cpu/User-Management/tree/master


2. Postman Collection Link


>> Register User  -  POST REQUEST - http://localhost:3000/api/users/register
>>
Body
{
  "firstName": "bhavik",
  "lastName": "doshi",
  "email": "bhavikdoshi@example.com",
  "phone": "9167254066"
}


>> Get User by ID  -  GET REQUEST - http://localhost:3000/api/users/657469d5d86380b09e90c3a9 
-> add user id after user/

>> Update User -  PUT REQUEST -   http://localhost:3000/api/users/657469d5d86380b09e90c3a9
-> add user id after user/

>> Delete/Disable User -  DELETE REQUEST - http://localhost:3000/api/users/657469d5d86380b09e90c3a9
 -> add user id after user/

>> filters REQUEST - GET REQUEST-  http://localhost:3000/api/users?firstName=John 
-> add user name after /users?firstName=


