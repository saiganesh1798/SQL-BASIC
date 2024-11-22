# SQL-BASIC

>>SQL Operators

The operators are symbols (and keywords) that are used to perform operations with values.
These operators are used with SQL clauses such as: SELECT, WHERE, ON etc.
The operators in SQL can be categorized as:
  1.Arithmetic operators
  2.Comparison operators
  3.Logical operators

**SQL Arithmetic Operators:**
Arithmetic operators perform simple arithmetic operations such as addition, subtraction, multiplication etc.

      Operator	Description
      +	Addition
      -	Subtraction
      *	Multiplication
      /	Divide
      %	Modulo (Remainder)

            Addition Operator:
            -- returns new column named total_amount which is 
            -- 100 added to the amount field
            SELECT item, amount, amount+100 AS total_amount
            FROM Orders;
            
            Subtraction Operator:
            -- returns new column named offer_price which is 
            -- 20 subtracted to the amount field
            SELECT item, amount, amount-20 AS offer_price
            FROM Orders;
          
            Multiplication Operator:
            -- returns new column named total_amount  which is 
            -- 4 multiplied to the amount field
            SELECT item, amount, amount*4 AS total_amount
            FROM Orders;
           
            Division Operator
            -- returns new column named half_amount which is 
            -- divided by 2 to the amount field
            SELECT item, amount, amount/2 AS half_amount
            FROM Orders;
       
            Modulo (Remainder) Operator
            -- returns 1 which is remainder
            SELECT 10 % 3 AS result;
            

**Comparison Operators**

We can compare two values using comparison operators in SQL. These operators return either 1 (means true) or 0 (means false).

    Operator	Description
    =	Equal to
    <	Less than
    >	Greater than
    <=	Less than or equal to
    >=	Greater than or equal to
    <>, !=	Not equal to

                Equal to Operator:
                -- returns records where customer_id is only 4
                SELECT order_id, item, amount
                FROM Orders
                WHERE customer_id = 4;
               
                Less Than Operator:
                -- returns records where amount is less than 400 (exclusive)
                SELECT order_id, item, amount
                FROM Orders
                WHERE amount < 400;
                
                Greater Than Operator:
                -- returns records where amount is greater than 400 (exclusive)
                SELECT order_id, item, amount
                FROM Orders
                WHERE amount > 400;
              
                Less Than or Equal to Operator:
                -- returns records where amount is less than or equal to 400
                SELECT order_id, item, amount
                FROM Orders
                WHERE amount <= 400;
               
                Greater Than or Equal to Operator:
                -- returns records where amount is greater than or equal to 400
                SELECT order_id, item, amount
                FROM Orders
                WHERE amount >= 400;
               
                Not Equal to Operator:
                -- returns records where amount is not equal to 400
                SELECT order_id, item, amount
                FROM Orders
                WHERE amount != 400;


               **Note**: Instead of !=, we can also use the <> symbol for not equal operations.

    **Logical operators** 

          ANY and ALL
          AND, OR and NOT
          BETWEEN
          EXISTS
          IN
          LIKE
          IS NULL


Examples:

1.Show first name, last name, and gender of patients whose gender is 'M'
>>select first_name,last_name from patients where gender like "m%";

2.Show first name of patients that start with the letter 'C'
>>SELECT first_name from patients where first_name like '%C';

3.Show first name and last name of patients that weight within the range of 100 to 120 (inclusive)
>>SELECT first_name,last_name from patients where weight  between 100 and 120 ;



**Count**:The COUNT() function returns the number of rows that matches a specified criterion.
    Ex:Show the total number of admissions
    >>select count(*) from admissions;

EASY LEVEL:

1.Show how many patients have a birth_date with 2010 as the birth year.
>>select count(*) from patients where year(birth_date)=2010 ;

2.Show the patient id and the total number of admissions for patient_id 579.
>>select patient_id,count(*) from admissions where patient_id =579;




