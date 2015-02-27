Develop this SPA in Angular.  Make sure that you follow the guidelines below:

1. Have a controller called customersController
2. Use a Factory called 'customerFactory'
3. If a user types a customer name that already exists, it should display an error message.
4. When a new customer is added, it should populate the table without reloading the page.
5. The filtering feature should work
6. Order the table by the date
7. Instead of using {{ }} use ng-bind (otherwise before angular gets loaded the html is going to display bunch of {{ }} on the screen which makes it look ugly/less-user-friendly).
8. Do NOT worry about storing information in the database yet.  Hard code the data directly in the factory.