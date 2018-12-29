🏪 Till
You've owned a corner shop for many years, but now the opportunity has come up to move into bigger premises. Your one till will no longer suffice - you need many tills.
The challenge for this week is to take this till repository, and to convert it to use the Prototype / Constructor pattern. You should attempt to do so with a test-driven approach.

Requirements
A store worker should be able to:

Create a new till with a list of products
Find a product by scanning its barcode
Add a product to the basket
Remove a product from the basket by its barcode


Hints
You will likely have two properties on a Till constructor: products and basket.
Any methods that modify these properties should sit on the Till.prototype.

Bonus Points
A store worker should be able to:

Close a sale. The basket will get tallied, stored as an object in a transactions array and emptied, ready for the next customer.
