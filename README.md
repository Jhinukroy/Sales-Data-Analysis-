# Sales-Data-Analysis-

**Dataset:**[https://www.kaggle.com/datasets/vivek468/superstore-dataset-final](url)

**Tool:** PowerBI

**Method:** 
 * 1.For yearly sales I use DAX **OrderYear** = YEAR('YourTable'[OrderDate])
 * 2.And for revenue **Total Cost** = SUMX( 'YourTableName', 'YourTableName'[Sales Quantity] * 'YourTableName'[Cost Per Unit] ) 
           
