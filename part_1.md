Frontend Assessment Part 1
HTML

What does "semantic markup" mean?
- Semantic markup refers to html tags that are explicit about their content.

What does a doctype do?
- Doctype says which version of HTML your page is using.

Explain what standards and standards bodies are and why they are important.
- Standards are the technical rules of the internetz.

What are CSS3 and HTML5? How are they different from previous standards? Why is this important?
- CSS3 and HTML5 are the latest versions. They differ in that they will be the last version numbered versions. The idea is just to iterate them up.

CSS

What does a CSS reset do and why is it useful?
What is the box model? Draw a picture and label the portions here.

What is the difference between a relative, fixed, absolute, and statically positioned element? Feel free to draw pictures to explain your answer.
- Relative position is when the elements are boxes....

What is SASS and why do people use it?
- Sass is a way to add programming logic to CSS.

Name one feature of SASS and explain why it is helpful.
- Mixins allow you to abstract certain repeatable portions, like setting property values, of the css into a method. Then you can call that method with parameters to customize it. This keeps the code DRY and helps things act a bit more dynamic.

JS

Explain prototypal inheritance.
- Prototypal inheritance is when a child class inherits from a parent class by setting it's prototype property equal to the parent class. 

Ex: var Child = Object.create(Parent) || Child.prototype = new Parent()

Parent object will now be in the prototype chain of the child object. Child inherits all the properties and characteristics of the Parent class. You can define attributes on an object higher in the prototype chain that will automatically get inherited to all objects that inherit from it. You can add and remove attributes as you go along. You can also override different attributes on inherited objects. 

What is a closure and how/why would you use one?
- A closure is function that has access to variables defined within it's context. Can be used to keep variables private in a class with getter/setter closure functions for access. 

Function Cat(){
  var name = "Anyong";
  this.getName = function() { return name;}
}
What is an anonymous function? Give a typical usecase for one.
- Anonymous functions are functions without names. They can be used as callback functions in functions that take them as arguments.

Describe the difference between
function Person(){}
var person = Person()
var person = new Person()
- First thing is defining a function named Person. The next is initializing a variable named person to the function Person. The third is setting a variable person to the value of a new Person object.

Explain hoisting.
- Hoisting is when javascript automatically sends variable instantiations to the top of the program. 

What is the difference between === and ==?
- == is a test for the an object being the same value, === is a test for the object being the same value and type