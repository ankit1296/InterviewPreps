# InterviewPreps

OOPs Questions:

What is base class of all classes ?
java.lang.Object

What is method overloading ?
  -->  having diff. type of paramter/ more/less paramter but same method name. Compile time polymorphism. resolved based on paramters passed.

What is method overriding? 
  --> same method signature, but resolved dynamically based on which object it is getting called. 
      child class usually override parent methods.
      ex. implementing our own toString() method. If not overriden then default gets called from Object parent which print object code,    
      if overriden then gets called from our own class
      
Static method can be overriden ? 
 -->  No. because it belongs to class, not ojects.
 
How prevent method from overriding?
  --> Make them private or static.
 
What is inheritance ?
 -->  getting or inheriting property of parents (depend on access modifier). Single level, Multi level inheritance supported, Not multiple it is supported through interface
      through class it cause diamond problem. like one class can extend two class and if those two have similar property child class will have ambiguity.
      
Java is pure OOP's ?
  --> No. coz it uses primary data types.

