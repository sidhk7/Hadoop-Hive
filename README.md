# Hadoop-Hive

In this, we are going to look at basic implementation of complex data types in Hive.

3 primary complex Datatypes in Hive :

Array : It is used to store list of attributes of same datatype. For example, a list of friends names, list of phone numbers etc. Array should not be confused with the list datatype in python which have subtle differences.

Map : It is used to store key value pairs like contact details which can be mobile , landline etc. Each pair will have one key and 1 value associated with that key.

Struct : Can be used to store different attributes of different datatypes , its similar to Structures in C/C++. It looks very similar to map, but it can hold multiple cols with different datatypes unlike map which can hold only one datatype.

Let us create a hive table with a sample dataset and perform simple queries on it to understand array, map and struct.
