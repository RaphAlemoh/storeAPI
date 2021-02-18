<!-- Required item must be provided and items can't be added without them -->

<!-- you can use mongoose schema for validating these required fields -->

<!-- 3. All the routes below are strictly protected and should only be accessible by auth customers(with a valid token) -->

<!-- Exppose the following routes on your API

/suggest 
::This routes allow customers make suggestion to items they would love to see on our store

There are currently three categories of item that can be suggested namely::
::Electronics, Furnitures, Grocery


Any item that is not within this category should not be accepted as a suggestion

The customer should provide the following details along with the suggested item
:: itemname(required), itemdescription(required), itemcategory(only 3 allowed), Reasonsforsuggestingitem'

Note: Required items must be provided and items can't be added without them

Hint: you can use your mongoose schema

3.1.  /suggested/category:
Auth users should be able to view the suggestion of every other users
This route should do two things depending on the route specified

a. Return suggested items for a particular category /:category
b. Return all suggested items if no category was specified


 -->
