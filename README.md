# SQL336
A sql file and 3 queries of a mock database involving printing; managed through here


There are three tables:
1. userInfo - contains information on the students first/last name and their pace email address which is needed to print.
2. printedInfoQueue - contains confirmation of successful printing through errorMsg column. Also the student number, current 
   account balance and pages printed are stored. 
3. toBePrintedQueue - documents to be printed that should be sent off to the printer. The type of document, size of document, 
   number of pages and whether the document is in color or should be double-sided is stored. 

There are three Queries:
1. SELECT: searches through the printedInfoQueue to look for error messages that are other than successfull.
2. DELETE: documents of type msexcel that are larger than 13MB are deleted. All documents of type ms-excel are deleted 
   regaradless of size.
3. UPDATE: A user wishes to update their paceEmail on record. The first and last names of the student are used to search and
   update that email.
 
