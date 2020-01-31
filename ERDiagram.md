# ER Diagram

Based on the [Data Requirements](./DataRequirements.md), we can define the the ER Diagram to show the entities and the relationship between those entities for our desired database.

**Descriptions**:

1. Rectangle shapes represent for the entities.

2. Eclipse shapes represent for the entities' attributes.

4. Diamond shapes represent for the relationship'name between 2 entities

3. The arrow between 2 entities (cross the Diamond shape) represents for their relationship.

    * One to One:`   ` `One   <----<name of relationship>----->   One`
    
    * One to Many:`  ` `One   <-----<name of relationship>-----   Many`
   
    * Many to One:`  ` `Many   -----<name of relationship>----->   One`
    
    * Many to Many:`    ` ` Many  -----<name of relationship>------   Many`

For example: ``` Floors <----<order>---- Tables```: **One to Many** relationship

-> Each floor has multiple tables, while each table belongs to only one floor.


![Image of ER Diagram](./ER%20Diagram/Pos_system_erdiagram.png)
