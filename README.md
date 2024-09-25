JDK - Java development Kit


JDK comes with a compiler and JRE (Java Run time environment). JRE comes with JVM and a set of API libraries to use.JVM uses JIT (Just in time ) to work efficiently. Compiler converts source code into byte code (machine code (App.exe in windows i.e. understandable by the machine). JRE provides the environment to run the java byte code. API ( Application Programming interface) provides many predefined functions ( example:- For reading and writing in files we use Java IO library), The compiled byte code can be interpreted by the Windows JVM JIT (for the windows operating system) and Linux JVM JIT ( for the Linux operating system). Hence, java is independent of operating system.



Object Oriented Programming

For example let us consider a real life scenario there is 2 persons John and Mary. Each object (i.e Mary and John) has identity (here, name), property/Variables (here, age, weight , qualification) and functions/behvaior (like speak(), laugh(), duty()). Two objects (i.e. Mary and John) communication with each other with functions and pass properties between them by communication ( i.e age, weight, qualification).



Object oriented principles


Object orieneted principles include Encapsulation, abstraction, inheritance and polymorphism (these object oriented principles can be implemented using objects and classes). 
Encapsulation protects the properties and functionalities of one object from other objects. (Class consist of the properties and methods/functions, functions can access the properties of the same class). For example there are 2 classes classA has its properties and functions and classB has also its properties and functions. If classB want to access properties of classA by encapsulation then classB has to call mthods/Functions of classA to access data/properties of classA. Encapsulation can be achieved by writing a class to hold its properties/data and functions by protecting them.
Inheritance is defining a new object by using a existing object. In inheritance we use the keyword 'extends' to inherit. For example iphone7 extends iphone6 (i.e iphone7 will have all necessary features that iphone6 possess) which means iphone7 accessing existing object functionality of iphone6. Additionally iphone7 can update the existing features of iphone6 in iphone7 through inheritance. Inheritance has two terms Re-usability and is-a relation. For example BMW and Audi has common features that as a car has which is reusability. Thus, BMW and Audi inherit from car class. BMW is-a car, similarly Audi also is-a car.
Abstraction is the principle of hiding all unnecessary details (i.e there is 2 objects objectA and objectB here objectA will show up only  essential features that ObjectB wants to communicate with ObjectA. Abstraction is used with the keyword interface. ( let us consider a real life  example for abstraction :- TV has been formed by using lot of chips and technology but the TV viewer need not have to consider the technology or chips used in the TV to watch the Tv)
In Polymorphism ply means multi and morphism means shapes or behavior. ( example Bini interacts differently to different persons ,(for example to parents Bini shows respect, to husband shows love, to children care and to colleagues professionally. )


Procedure Oriented - is used to complete a sequence of tasks. Procedure oriented emphasis on procedures. In procedure oriented large program are divided into functions. In procedure oriented data are from function to function. In procedure oriented they share global data since there are no access specifiers. 
Object oriented - it modularizes the data and methods by allocating data and methods to place them in memory to store. Object oriented emphasis on data. In object oriented a large program are divided into objects. In object oriented data are hidden by the concept like encapsulation. In object oriented data are passed depending on access specifiers.


Building blocks of Java application are class, variables, methods and blocks. In object oriented each objects are represented by a class. Each class has variables, methods/functions and blocks. Each class has a unique identity/name. the variables and methods in class can be static and non-static. Variables are identities that are given to memory location where data are stored. (Syntax of variable  data-type variable-name,  example:- int a;). Real life example of non-static and static, In a banking application the variables  account number and balance for each person are having different values these are examples of non-static. bankname is unique among all the accounts this an example of static variable. Methods are given an input and transforms into an output. ( (syntax return-type identity/name (argument-list) { //body of method } ) that is argument-list is the input given and the return-type is the type of what output returns).
Example
int sum(int a , int b){
int sumValue = a+b;
retun sumValue;
} 






package com.bini.babu.helloworld;

public class HelloWorldProject1 {

	public static void main(String[] args) {
		System.out.println("HelloWorld");
	}

}


public is the access specifier, class is the keyword used for class, HelloWorldProject1 is the identifier of class, main is where jvm invokes the main method when we run a java program. main is the starting point every java program. static is provided because then that method (here main function) is invoked by the class name (here HelloWorldProject1, i.e HelloWorldProject1.main this can be used to invoke te main method instead of creating object for HelloWorldProject1 class). String[] args here java allows to pass some arguments when we run java program from command line.
