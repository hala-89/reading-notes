
# HTML Tables

+  The (table) element is used to add tables to a web
page.

+  A table is drawn out row by row. Each row is created
with the (tr) element.

+  Inside each row there are a number of cells
represented by the (td) element (or (th) if it is a
header).

+  You can make cells of a table span more than one row
or column using the rowspan and colspan attributes.

 +  For long tables you can split the table into a "thead",
"tbody", and "tfoot".




![htmltable]( https://i.imgur.com/uIwzEfS.png )










# Domain Modeling
Domain modeling is the process of creating a conceptual model in code for a specific problem.
 A model describes the various entities, their attributes and behaviors, 
 as well as the constraints that govern the problem domain


##  some tips to follow when building your own domain models.

+  When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.

+ Model its attributes with a constructor function that defines and initializes properties.

+ 3Model its behaviors with small methods that focus on doing one job well.

+ Create instances using the new keyword followed by a call to a constructor function.

+ Store the newly created object in a variable so you can access its properties and methods from outside.

+ Use the this variable within methods so you can access the object's properties and methods from inside. 





## referanc


 [DuckettHTMLbook](http://www.htmlandcssbook.com/code)


[DomainModeling](https://github.com/codefellows/domain_modeling#domain-modeling)

