# Database Design and Development - Car Repair Business Use Case
A project for my Master's Degree to develop a proposal for creating a database system for a Car Repair business. 

- Credit: Bellevue University 

# Process: 
- Determining System Requirements
- Object Orientated Analysis and Design - Use Cases, Activity Diagrams, and Business Process Modeling
- Structuring System Data Requirements
- Database Conceptual Design
- Logical and Physical Database Design
- Testing and Quality Assurance
- Secure Software Development - Software Development Lifecycle 
- Incorporating DevOps into the SDLC


# Assignment Introduction
Tim Smith owns a small car repair shop called Down Town Car Repair. Tim does small and large car repair jobs for individual customers only. Tim doesn’t do commercial work. Tim manages all his accounts using pen and paper. Tim has contracted you to automate his small business.

# Business Use Case
Customers will call or drop in and ask Tim to bid on a repair. If the repair is small, such as an oil change, Tim will give them a fixed bid. However, if the repair is complex and needs some time for Tim to investigate the problem, he charges a fixed amount for the initial investigation and then provides a bid on the work. Either way, Tim creates a bid for all his work. Customers can either accept the bid or reject the bid. If the customer accepts the bid, then Tim starts the work.
The bid contains the start date, estimated end date, estimated materials, estimated labor cost, and total estimated cost of the repairs.
Tim buys material and supplies from various suppliers. Tim has an inventory of common material, such as belts, oil, tiers, and so forth. However, when a job requires special material, such as engines or transmissions, Tim orders these special materials from various suppliers.
All of Tim’s suppliers allow him to make monthly payments on the materials he purchases. It is important that Tim understands what material he is purchasing for each supplier, the total amount due to each supplier, and the monthly amount due to each supplier.
Once Tim completes the work, Tim create a bill for the work done. The bill contains the same information as the bid, but the amounts are adjusted based on the work Tim has done. Tim will not charge over the bid amount unless he calls the customer and gets their approval.
If the total amount due is less than a certain dollar amount, the customer has to pay when they pick up their vehicle. If the amount due is over a certain amount Tim allows for monthly payments. However, each payment needs to be 10% of the outstanding amount due or a minimum of 100 dollars.
If a customer fails to make a payment for one month, he charges a 10% late fee. If the customer fails to make a payment for a second month, he turns the account over to a collection agency. The collection agency then tries to collect payment. If the collection agency fails to collect payment after three months, Tim doesn’t have to pay the collection agency. If the collection agents collects partial payment or full payment, the collection agency takes 30% of the amount collected.
