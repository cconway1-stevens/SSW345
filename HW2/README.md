Use-Case Diagram: I was unsure whether to include the stack in this diagram. However, the user navigates the page to interact with everything. 
      You don't want any private keys on the frontend server, which is why you need to connect to a backend server (the API), which connects to the payment server and database
       server. The backend server will retrieve information from these servers and return it to the user.

Class Diagram: The customer class is linked to three additional classes: storeFront (bookStore), their cart, and payment processing/information. 
       According to the illustration, payment processing includes a credit card class and a shipping/billing class. This allows the user to insert 
       numerous addresses and credit card numbers. The cart is subsequently linked to the payment processor, allowing the user to complete the checkout procedure.

This is a sequence diagram depicting a user browsing for a book, adding it to their cart, entering payment information, 
      and checking out. I omitted the login step here. The two for loops are used to add numerous payment methods as well as to 
      add/search for multiple books.
