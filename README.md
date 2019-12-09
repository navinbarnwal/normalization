# normalization
This library takes the filename and column as a parameter and return the  min_max normalization, zscore normalization, decimal normalization.. Set multiple column as parameter as the requirement.  

Example:-  

normalization.required_method('__filename__, column_name1, column_name2,....') 
normalization.min_max_nor('iris.csv', 'sepalwidth', 'sepallength') 
normalization.zscore_nor('iris.csv', 'sepalwidth') 
normalization.decimal_nor('iris.csv', 'sepalwidth')
