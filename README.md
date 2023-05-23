# Update Pet Sales Data using Stored Procedures in SQL

The stored procedure, RETRIEVE_ALL, retrieves the information from the PETSALE table.
The stored procedure, UPDATE_SALEPRICE, updates the sale price of the animals in the PETSALE table depending on their health conditions, BAD or WORSE. The procedure takes in the animal ID and their health codition as parameters. It uses these parameters to update the sale price of the respective animal in the PETSALE table by a certain amount.

For animal with ID XX having BAD health condition, the sale price will be reduced further by 25%.
For animal with ID YY having WORSE health condition, the sale price will be reduced further by 50%.
For animal with ID ZZ having other health condition, the sale price won't change.
