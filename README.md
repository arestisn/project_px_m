# pxm

The main objective of this project is to create a WEB GUI Interface which connects to a specific DB. The DB will have unlimited number of schemas (different clients). Through the WEB GUI you will be able to create/view/edit/delete DB schemas or/and specific components within a schema. 

Programming Languages: Scala (PLAY FRAMEWORK) and Bootstrap

Each schema has an X number of tables. Therefore, we will have to create functions that will perform a specific actions (add/remove/edit/copy from) on a single table and on multiple tables. 

E.g
1. "account_table" / "account_setting_table" are linked together with a primary key. Any change that you make on "account_table" table, a relevant change must be applied on "account_setting_table" table as well. 
2. "routing_table" is a standalone table and therefore any changes must be applied only to it. 




