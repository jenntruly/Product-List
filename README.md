# Production Pivot

An independent artist who sells their designs on products in an online store has called upon you to create a table that visualizes the cost of their recent orders. Using lookups, create a pivot table for the artist.

## Instructions

* Determine the "Product Price" of each row in the "Orders" sheet by using a `VLOOKUP()` that references each row's "Product ID."

  * The "Product Price" of a row does not include shipping.

* Determine the "Shipping Price" of each row in the "Orders" sheet by using a `VLOOKUP()` that references each row's "Shipping Priority."

* Select all of the data on the "Orders" sheet, and create a new pivot table that calculates the sum of "Product Price" and "Shipping Price" for each "Order Number" and "Product ID."

