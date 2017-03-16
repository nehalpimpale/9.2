# 9.2

Explain the working of below pig script commands with an example :
1.LOAD
• Loads data from the file system.
Syntax
• LOAD 'data' [using function] [AS schema];

2.STORE
• Stores or saves results to the file system.
Syntax
• STORE alias INTO 'directory' [USING function];



3.DUMP
• Dumps or displays results to screen.
• Syntax
• DUMP alias;


4.FOREACH
• Generates data transformations based on columns of data.
Syntax
• alias = FOREACH generate_operations [AS schema];



5.FILTER
• Selects tuples from a relation based on some condition.
Syntax
• alias = FILTER alias BY expression;

6.GROUP BY
• Groups the data in one or multiple relations
• alias = GROUP alias { ALL | BY expression} [, alias ALL | BY expression …] [PARALLEL n];


7.ORDER BY
• Sorts a relation based on one or more fields
Syntax
• alias = ORDER alias BY { * [ASC|DESC] | field_alias [ASC|DESC] [, field_alias [ASC|DESC] …] }
[PARALLEL n];

8.DESCRIBE
• Returns the schema of an alias.
• Syntax
• DESCRIBE alias;

