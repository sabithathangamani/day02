# day02
Http Methods

1.Write a blog on Difference between HTTP1.1 vs HTTP2?
Answer:
HTTP1.1
 1. It works on texual format.
 2. There is head of line blocking that blocks all the requests behind it until it doesn’t get its all resources.
 3. It uses requests resource Inlining for use getting multiple pages
 4. It compresses data by itself.
HTTP2
 1.It works on the binary protocol.
 2.It allows multiplexing so one TCP connection is required for multiple requests.
 3.It uses PUSH frame by server that collects all multiple pages 
 4.It uses HPACK for data compression.




2.Write a blog about objects and its internal representation in Javascript
Answer:

Object:
In JavaScript, an object is a standalone entity, with properties and type. Compare it with a cup, for example. A cup is an object, with properties. A cup has a color, a design, weight, a material it is made of, etc. The same way, JavaScript objects can have properties, which define their characteristics.


Creating Objects in JavaScript:
  1.By object literal
  2.By creating instance of Object directly (using new keyword)


By object literal:
The syntax of creating object using object literal is
object ={property1:value1,property2:value2,....propertyN:valueN}
Property and value is separated by colon(:).
Example:
Var person={fname:"xxx",lname:"yyy",age:25};


By creating instance of Object directly (using new keyword):
The syntax of creating object directly is given below:
var objectname=new object();
Here, new keyword is used to create object.
Example:
var emp=new object();
emp.id=101;
emp.name="xxx";
emp.salary=50000;


Accessing JavaScript Objects:
The syntax for accessing the property of an object is:
objectName.property
or
objectName ["property"]

Accessing ‘fname’ from example 1 using dot operator,
          person.fname
Accessing ‘name’ form example 2 using [],
           emp["name"]

