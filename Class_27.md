# 4 Different ways to create MVC Forms.

## Forms - Weakly Typed (Synchronous)
 easiest and quickest way to create forms in MVC
 Advantage:
1. It is easy to create a form using Weakly Typed mechanism
2. Mostly used when you need to create a form with one or two input items.

Disadvantage:
1. Because, it is not strongly typed so IntelliSense doesn't help you.
2. Have higher chance of getting exception and runtime error messages.
3. Very difficult to manage when forms have multiple input items and controls.
4. It is very clumsy when you need to add or remove some input items.
   
## Forms - Strongly Typed (Synchronous)
In this method, we send objects (model) instead of sending each item as parameter. It is easy to maintain because you don't need to remember each input item and IntelliSense will show you automatically the each item.


## Forms - Strongly Typed AJAX (Asynchronous)
Asynchronous AJAX form is a very magical way to submit data to the controller without happening page load. Asynchronous AJAX Forms simply post back the data to the controllers and update the only that part of the page, which has to display output.

To make this happen, we will use JQuery-Unobstrusive-AJAX. This is a great feature which is launched in MVC 3. It helps you to create AJAX Form without writing bunch of javascript code. Before creating Asynchronous AJAX Form you need to add JQuery-Unobstrusive-AJAX in your project. Adding is very easy, and just follows the steps.


## Forms – HTML, AJAX and JQUERY
In this method, you can not only send data from input controls but can also use html elements like <p>…</p>, <span>…</span> to send data to controllers. This is pure JQuery and AJAX query.

