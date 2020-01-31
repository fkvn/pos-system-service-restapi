# Data Requirements

##### The system must manage the following data and constrains: 

1. The business will store and manage **Items** where everything is associated with it.  

1. The store will have several floors and tables.

1. Each floor contains the floor number and will have multiple tables.

1. Each table will contains its id and name. In addition, each table will relate to multiple orders.

1. Each order stores order's number, timestamp, total price, and its record. Orders'record will have all order's information, list of items (with items' information, plus quantity and price) for each order, staff's id and name, and payment type. There are 3 type of payments: Cash, Debit, and Credit card.

1. There are multiple types of category. For example, a category could be beverage, meal, desert, etc. Each category will contain multiple items. 

1. Each item will contain its name, total quantity, unit, price per unit, discount (%), and images. Each item can have multiple images which will be uploaded by admins (only). In addition, each item belongs to only one category.

1. There are 3 types of users: **Admin, staff, and customer**. Except for the customers, both Admin and Staff are required to have basic information, such as username (required), password (required), title, contact information (phone, address). 

1. The system also include more information of the staff. Each staff will have their staff id, name (full name), date of hired, email, phone, emergency contacts (name, address, phone), date of birth, address, SSN, and records which include notes or comments from admins (optional). Each record should list admin's name, timestamp, notes/comments. 

1. Multiple staff/admins can have the same address (including street, city, state, and zipcode), but they cannot have the same phone number. 

1. The system also supports inventory's management. Each inventory's information should include id, name, type, and status. There are four main inventory types in the store: raw material, finished goods, warehouse, and others. For status, there are 2 kinds of status: in-stock (green color) or out-of-stock (red color). Each created inventory will be out-of-stock status as default until there are some iItems (described below) added to the inventory

1. Each inventory will contain information of its items (inventory_items or iItems). Each iItems store its id, name, quantity and unit. For example, we create an inventory called "meat" which can be listed as raw material. In "meat" inventory, we can create an iItems called "beef" with its quantity equal to 10 and lbs. as its unit.

> Note: If an inventory doesn't have any iItems or all its iItems' quantities reach to "0", the inventory's status would be marked as out-of-stock. Otherwise, the status would be in-stock. 



