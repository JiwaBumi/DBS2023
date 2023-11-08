**Normalization**  
Normalization is the process of restructuring your database to become more tidier and reduce redundancy and anomalies. Databases can be evaluated with "forms" and those that went through the process of normalization can be called "normal forms"  
There are many types of normalization, but the most common being 1NF, 2NF, 3NF. NF stands for 'Normal Form'. We can think of NFs as 'Tiers'  
**1NF**  
To meet the requirements of 1NF, the table must have:  
- A key for identification. Like a primary key.
- Every cell holds a single value
- None of the rows are duplicates or same

Once the above is met, then we can proceed to 2NF  
**2NF**  
- Has to be in 1NF first
- Attributes that arent keys or dont have keys, are fully dependent on a primary key
- Split the table. For example, a table has CustomerID, ProductID, CustomerName, ProductName. It is clear that we need 2 separate table, one contains CustomerID and CustomerName, while the other contains ProductID and ProductName

**3NF**  
- Has to be in 2NF first
- Has no transitive dependencies. Transitive Dependency is when an attribute relies on an attribute, because the attribute it relied to in the first place, relies on that attribute. For example, lets say '>' means 'relies on', then A>B>C is same as A>C
