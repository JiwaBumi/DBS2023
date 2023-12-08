#Week IV   
AGGREGATION  
- SUM: Add values
- AVG: Average the values
- MIN: Smallest number on the table
- MAX: Largest number on the table
- COUNT: Shows how many rows your table has  
- SELECT DISTINCT: Shows only unique values from the column

CONDITIONAL CLAUSES  
- WHERE: Used to filter a value  
- AND: Include another condition  
- OR: Include 'this' condition, or 'that' condition
- IN: Multiple inclusions
- DELETE: Remove an entire row

EXAMPLES  

Example 1: Delete Apple from Vegetables Table  
DELETE FROM Vegetables WHERE Name = 'Apple';  

Example 2: Find courses offered in Fall 2017 and Spring 2018  
SELECT DISTINCT course_id  
FROM section  
WHERE semester = 'Fall' AND year = 2017  
AND course_id IN (SELECT course_id  
                  FROM section  
                  WHERE semester = 'Spring' AND year = 2018);  

References  
W3Schools  
UPH Sistem Basis Data Materi Week/Sesi 4
