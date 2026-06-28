OBJECOBJETICVE
It sounds like you want to explore how objects in a list of orders connect to order details and ultimately to sales. 
📥 Data Import
Import list order.csv into power bi
open the List of order the power querry  Editor using the transformaction  option 
Steps to open the list of transformations
Load data into Power Query
Open Power Query Editor
View the Applied Steps list
Modify or reorder steps

Right-click the column header → choose Change Type → Date
Alternatively, select the column, then on the ribbon go to Transform → Data Type → Date
Table.TransformColumnTypes(Source, {{"OrderDate", type date}}).

change the amount and target column to fixed decimal number
On the ribbon, go to Transform → Data Type → Fixed Decimal Number.
On the ribbon, go to Transform → Format → Capitalize Each Word.

 Transform add custom column  combain city and state named has Location
  profit and Amount combaine into percentage colum
  
  condition column
  profit<0 "Loss"
  Profit=0"break even"
  else if profit > 0 Profit
  
  Mergedate
  Merge List orde and orde details in orde id
  = Table.NestedJoin( List Orders, {"OrderID"}, OrderDetails, {"OrderID"}, "OrderDetails", J

  
  cost and filtering data
  
  order date right click  seclect desecending order
  put card to dotder date
  Put table for list order in city
  put slicer in table and select in Tamil Nadu
  
  Grouping and aggeregration 
  
  COUNTN(or[Order Id])
  Average(or[Aount])
  Total amount=sum(list of order[Amount])
  
  

  
