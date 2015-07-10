### For each of the questions listed, determine what part of the MVC framework would deal with implementing the requested functionality

**Example:** Q) User's name should appear in top right of each page.   A) View

- If shipping address is Colorado, apply 6% sales tax to all orders
	
	**This should be done in the Model**
	
- Do not allow shipments to Florida

	**This should be done in the Model**
	 
- Require user to login before checking out

	**This should be done in the Controller**
	
- The background color of the webpage should be light green

	**This should be done in the View**
	
- If the user tries to add an out of stock item to their cart, they should be redirected and see an error

	**This should be done in the Controller**
	
	
- The user should have a drop down to allow them to add a quantity of an item to the cart

	**This should be done in the View**
	
	
- If the user's shopping cart is empty, redirect them to the main page

	**This should be done in the Controller**
	
	
- If the user requests quantity 5, but only three are available, that row in the shopping cart should be highlighted in red

	**This should be done in the View (will call methods on the model to check quantity beforehand though)**

