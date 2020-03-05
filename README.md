# Assignment-4
To demonstrate the ability to understand the purpose and role of a data model and construct ERDs that represent relationships, minimum, and maximum cardinality using Crow’s foot modeling techniques.

The Queen Anne Curiosity Shop wants to expand its database applications beyond the current recording of sales. The company still wants to maintain data on customers, employees, vendors, sales, and items, but it wants to (a) modify the way it handles inventory and (b) simplify the storage of customer and employee data. 

Currently, each item is considered unique, which means the item must be sold as a whole, and multiple units of the item in stock must be treated as separate items in the ITEM table. The Queen Anne Curiosity Shop management wants the database modified to include an inventory system that will allow multiple units of an item to be stored under one ItemID. The system should allow for a quantity on hand, a quantity on order, and an order due date. If the identical item is stocked by multiple vendors, the item should be orderable from any of these vendors. The SALE_ITEM table should then include Quantity and ExtendedPrice columns to allow for sales of multiple units of an item. 

The Queen Anne Curiosity Shop management has noticed that some of the fields in CUSTOMER and EMPLOYEE store similar data. Under the current system, when an employee buys something at the store, his or her data has to be reentered into the CUSTOMER table. The managers would like to have the CUSTOMER and EMPLOYEE tables redesigned using subtypes. 

## A.  
Draw an E-R data model for The Queen Anne Curiosity Shop database schema shown in Chapter 3’s “The Queen Anne Curiosity Shop Project Questions.” Use the IE Crow’s Foot E-R model for your E-R diagrams. Justify the decisions you make regarding minimum and maximum cardinalities.

## B.  
Extend and modify the E-R data model by adding only The Queen Anne Curiosity Shop’s inventory system requirements. Use the IE Crow’s Foot E-R model for your E-R diagrams. Create appropriate identifiers and attributes for each entity. Justify the decisions you make regarding minimum and maximum cardinalities. 
 
## C.  
Extend and modify the E-R data model by adding only The Queen Anne Curiosity Shop’s need for more efficient storage of CUSTOMER and EMPLOYEE data. Use the IE Crow’s Foot E-R model for your E-R diagrams. Create appropriate identifiers and attributes for each entity. Justify the decisions you make regarding minimum and maximum cardinalities. 

## D.  
Combine the E-R data models from parts B and C to meet all of The Queen Anne Curiosity Shop’s new requirements, making additional modifications, as needed. Use the IE Crow’s Foot E-R model for your E-R diagrams. 

## E.  
Describe how you would go about validating your data model in part D.
