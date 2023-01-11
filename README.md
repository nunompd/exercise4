# exercise4

## create an app following the specifications below:

- The app needs to be protected from unauthorized access:
  - Add a login a page that has the following inputs
    - Username
    - Password
    - Button to submit the data
      - TIP: Valid users available [https://dummyjson.com/users](https://dummyjson.com/users)
      - TIP:: Post endpoint [https://dummyjson.com/auth/login](https://dummyjson.com/auth/login)
  - Add a home page that the user can only navigate to if it is authenticated (store token in the app memory)
  - Create a service to get all of the products from the following url ([https://dummyjson.com/auth/products](https://dummyjson.com/products)) and list them on the page by title, price, first image on each product. The service needs to pass the user token in the headers of the request
    - TIP: Authorization: Bearer TOKEN
