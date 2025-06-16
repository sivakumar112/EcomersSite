**E-Commerce-Application**


The E-Commerce Application is built using Java and Spring Boot, with security, scalability, and ease of maintenance. The backend uses Spring Data JPA to interact with a MySQL database, making it easy to manage and store important entities such as users, products, categories, orders, and more. User authentication is handled by Auth0, providing secure and reliable means of REST APIs.

The APIs are well-documented and easily accessible through Swagger UI, making it simple for developers to test and understand the various endpoints. Overall, this project provides secure Rest APIs to create a scalable platform for businesses to sell their products to customers.

Features
Admin:-
* Login
* Users
* Address
* Categories
* Products
* Price & discount
* Orders
User:-
* Registration & Login
* Fetch categories and products based on category
* Adding & deleting products to cart
* Managing address and products quantity
* Ordering products and fetching order status
* Security
The API is secured using JSON Web Tokens (JWT) handled by Auth0. To access the API, you will need to obtain a JWT by authenticating with the /login endpoint. The JWT should then be passed in the Authorize option available in the Swagger-ui.

Example:
Authorization: <your_jwt>
Technologies:
Java 17 or above
Spring Boot 3.0
Maven
MySQL
Spring Data JPA
Spring Security
JSON Web Tokens (JWT)
Auth0
Swagger UI
Running the app
Run the app: Right-click the project in the Package Explorer and click Run As > Spring Boot App.
API documentation
API documentation is available via Swagger UI at http://localhost:8080/swagger-ui/index.html

**ER-Diagram**
![image](https://github.com/user-attachments/assets/099465e2-5090-4939-8dad-233b18f0737c)

ER-Diagram

Swagger-ui
![image](https://github.com/user-attachments/assets/51dac6d9-631c-4424-a41a-78fbaf9655f2)


API Controllers**
Auth_Controller**
![image](https://github.com/user-attachments/assets/cd0790c4-d430-4f3c-a441-93b4d3d7d6d8)
**User_Controller**
![image](https://github.com/user-attachments/assets/d5a39d60-c89e-41bb-952a-730a8a499e06)
**Address_Controller**
![image](https://github.com/user-attachments/assets/1951cb2c-f52d-4390-bb33-708e20591cde)
**Cart_Controller**
![image](https://github.com/user-attachments/assets/e25c5a0b-994b-4acd-94d7-5cdff04014d3)
**Category_Controller**
![image](https://github.com/user-attachments/assets/bf916a77-ca7e-4ce4-9bfc-58f8527652f2)
**Product_Controller**
![image](https://github.com/user-attachments/assets/011775ad-e969-4163-afbb-ac626f9082b1)
**Order_Controller**
![image](https://github.com/user-attachments/assets/2965906f-34ed-4912-9043-655b03556a1a)
