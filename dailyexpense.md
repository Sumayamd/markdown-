








### daily  Expense 
Create a table 

  1. id
  2. items_names
  3. date
  4. amount
  5. description
  6. payment_mode

| id | items_names  | date     | amount | description         | payment_mode |
| ---|     ---      |   ---    |  ---   |     ---             |  ---         |
|20  |  food        |2023-01-15| 1000   | restaurant          | online       |
|21  |  shopping    |2023-02-14| 2000   | malls,marketplace   | cash         |
|22  |  snacks      |2023_02-15| 500    | chocolates,icecreams| cash         |
|23  | mobile_bills |2023_02_10| 300    | recharge            | online       |
|24  | Groceries    |2023_02_09| 6000   | bestprice           | cash         |


## Create daily_expense table
 ```sql
 create table daily_expense
 (expense_id int,
 items_names text, 
 date date ,
 amount float, 
 description text, 
 payment_mode varchar(10));
 ```

## Insert rows in daily_expense(
    ID          int,
    items_names  text,
    date       date,
    amount     int,
    description  text,
    payment_mode varchar(50)
);

insert into daily_expense values(
   20,
  'food',
   2023,
   1000,
  'restaurant'
  'online'
  );

insert into daily_expense values(
  21, 
 'shopping',    
  2023-02-14,
  2000,   
 'malls,marketplace'
 'cash'         |
);

insert into daily_expense values(
  22,  
 'snacks',     
  2023_02-15,
  500,    
 'chocolates,icecreams'
 'cash' 
);

insert into daily_expense values(
  23,  
 'mobile_bills', 
  2023_02_10,
  300,    
  'recharge',
  'online',      
);

insert into daily_expense values(
 24, 
 'Groceries',
 2023_02_09,
 6000,  
 'bestprice', 
 'cash' 
);












