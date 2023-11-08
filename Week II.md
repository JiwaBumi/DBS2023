#Week 2️⃣  
Structure of Database

📍**Attributes**  
Attributes are columns in the table. To be more specific, it is the name or what defines the column itself.

📍**Tuples**  
Tuples are rows in the table

📍**Relation**  
Relation is another word for table. It is written as R

⤷**Example 1**
R = (A1, A2, A3...) < This is a relation schema  
A are attributes  
R is is the Table or Relation  
Lets say that a database has 2 tables named student and teacher, and they have attributes. It would look like:  
Teacher(profID, teacher_name, department),
Student(NIM, student_name, department)

📍**Schemas**  
Schemas are the logical structure of the database. An analogy of it would be like a plan or blueprint.

📍**Instance**  
Instances are the 'current state' of the database

📍**KEYS**  
Keys are identifiers of the table and database as a whole  
⤷**Primary key**  
Basically the MAIN identifier of the table  
⤷**Candidate key**  
Keys that could've been primary  
⤷**Composite Key**  
Lets assume that attribute 'name' and 'country' has 2 values each: 'Kennedy', 'Kennedy', 'America', 'Indonesia'  
Even though 'name' is a primary key, there can be people with same name, but we can still tell the difference using country. That means 'country' is a composite key. If that is no good, then perhaps something else like 'home_address'  
⤷**Foreign Key**  
Attributes marked as foreign key means they exist in another table, and to build a relationship with that attribute instead of a completely new one
