# Fakedata
When teaching, there is often a need for data, it can be for databases or files (CSV, Excel) to be imported in e.g. Python to work with those there.

Sometimes it is an advantage if the data has a large "size" other times it is an advantage with "small" amounts of data - Speed.

I have created a Jupyter Lab file that generate "sales data" for a total fictitious business.
If you prefer the code as a Python (py) file, you can export it from Jupyter Lab.

## Tables
Data consists of 4 "*tables*":
- Customers
- Employees
- Orders
- Products - *20 products predefined*

### Relations

![](data_er_diagram.jpg)

## Number of entries
It is possible to control the number of entries in the various tables. 
However, you should be aware that a large number of records will mean that it takes a long time to generate the data.

```
  no_customeres = 20
  no_sales = 5000
  no_employee = 10
```

Product is predefined to 20 products.

## Export
Data is exported to CSV and Excel.
In Excel, it is one Excel file that contains 4 sheets.

### CSV
- customers.csv
- order.csv
- employees.csv
- products.csv

### Excel
- sales_data.xlsx
