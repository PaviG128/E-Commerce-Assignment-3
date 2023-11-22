# E-Commerce-Assignment-3

E-Commerce CLI Application is built using Spring Boot, Data JPA, and MySQL.
To develop a command-line e-commerce application where users can view products, add them to a cart, and place orders through a series of text-based prompts and responses.

1. Setup & Configuration:
•	Setup a new Spring Boot project using the Spring Initializr.
•	Include the following dependencies: Spring Data JPA and MySQL Driver.
•	Configure the application.properties or application.yml for the MySQL database connection.

2.Services:
The Services used in this application are,
•	ProductService: CRUD operations for products.
•	CartService: Operations like add product to cart, remove product from cart, and view cart.
•	OrderService: Operations like place an order and view order history.

3. CLI Interface:
•	On starting the application, we display a menu with options such as:
1.	List all products
2.	Add a product to the cart
3.	View cart
4.	Place an order
5.	View order history
6.	Exit
•	Depending on the user's choice, perform the corresponding action, and then it will return to the menu.

4. Running the app
->Clone the repository: git clone 
->Import the project into STS:
->Click File > Import...
->Select Maven > Existing Maven Projects and click Next
->Browse to the project directory and click Finish
->Update the values in application.properties with your MySQL database connection details.
->Run the app: Right-click the project in the Package Explorer and click Run As > Spring Boot App.


