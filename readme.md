**for data-rest app arch will be**

Before
EmployeeRestController->EmployeeService->Employee Repository(Spring data jpa)->DB

after
Spring Data Rest /employees->Employee Repository(Spring data jpa)->DB


http://localhost:8080/employees



**change base url on application.properties**
#
# Spring Data REST properties
#
spring.data.rest.base-path=/magic-api

http://localhost:8080/magic-api/employees