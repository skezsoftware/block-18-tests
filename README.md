# block-18-tests

# A function called "multiplication" that returns the product of the two input numbers.

Unit Tests:
A function called "multiplication" that returns the product of the two input numbers.
Expect function called "multiplaction to return the product of the two input number

A function called "concatOdds" takes two arrays of integers as arguments. It should return a single array that only contains the odd numbers, in ascending order, from both of the arrays.
Example: concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1])
...should result in [-1, 1, 3, 9, 15]

Think about the following; you may need to make assumptions or decisions about the prompt and how the code should behave:

What should happen with unexpected inputs?
Expect unexpected inputs to display an error message

What kinds of unexpected inputs should we worry about?
Expect strings and any other text to be displayed as an error

What should happen when there are multiples of the same odd number in the arrays? (Hint: We gave you the answer to this one in the example above.)
Expect multiples of the same odd number to be combined into/count as just one.

Functional Tests:

A shopping cart checkout feature that allows a user to check out as a guest (without an account), or as a logged-in user. They should be allowed to do either, but should be asked if they want to create an account or log in if they check out as a guest.

Think about the following; you may need to make assumptions or decisions about the prompt and how the feature should behave:

What should happen if the cart is empty?
What needs to be shown to the user at each step of check out?
What behaviors of this feature does the prompt miss or gloss over?
Hint: Observe the shopping cart and checkout features of some popular websites to get some ideas!
Please submit as a text file or a GitHub link (make sure it is set to public)

When a user adds an item to their cart, the item is displayed in their cart.
When a user clicks on their cart, they are taken to their cart.
When a user clears their cart, the cart shows as empty.
When a user continues to checkout, they are taken to a seperate page to review their order.
When a user is directed to the next page, they are asked to review their order, add shipping address and input a payment method.
When a user enters their address, shipping and handling is calculateed into the total cost.
When a user enters their address and payment method, they are taken to another page to review their order one more time.
When a user is redirected to the final review page, they are asked to click on a purchase now button.
When a user purchases all the items from their cart, the cart is cleared and reset.
When a user purchases what is in their cart, they receieve an email with their confirmation 
When a user receives their confirmation, they are able to see when their order is set to arrive