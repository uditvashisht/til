#Indexing

##Indexing using .loc()

Select all the rows for a column:
`df.loc[:,'column_name']`
Select all the rows for more than on column:
`df.loc[:,['column_name_1', 'column_name_2']]`
Select specific rows and columns:
`df.loc[[1,3,4],['column_name_1', 'column_name_2']]`

##Indexing using .iloc()

