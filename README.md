This is a simple and easy to understanmd tutorial on CRUD operations using spring boot and postgresSQL.

Steps:
1. Create a database in postgresSQL with the name = emp and leave everything as it is.
2. Change the application.properties file settings like your username and password.
3. Open postman for API testing , you can use below data for testing.

   POST   loalhost:8080/employee
     BODY   {
      "employeeName": "emp1",
      "employeeSalary": 100
      }

   GET   loalhost:8080/employee/1
 
   DELETE loalhost:8080/employee/1
