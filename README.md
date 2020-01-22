# learn_html


Chapter 1.

<body> </body>

<p><span> </span> <em> </em> <strong> </strong> <br> </p> : use span to separate inline content, use em to make it italic, use strong to make it bold, use br to break line (no closing tag,NCT), 

<div id="intro"> </div> :

<h1> </h1> : main headings

<h2> </h2> : gets smaller

<h3> </h3>

<h4> </h4>

<h5> </h5>

<h6> </h6>

<ul> : unordered list
  <li> </li> : list item
</ul>

<ol> : ordered list
  <li> </li>
</ol>

<img src="BTS.jpg" alt="BTS" /> : image (self closing tag,SCT), use alternative text to explain image

<video src="BTS.mp4" width="300" height="300" controls> : use controls for basic video controler like play, pause, skip...
  Video not supported. : diplayed when video is not found
</video>


Chaper 2.

<!DOCTYPE html>

<html>
  <head> </head> : metadata of the page (not displayed, information about the page)
  <body> </body> : displayed
</html>

<title> </title> : title of the page (between head tags)

<a href="https://naver.com" target="_blank"> </a> : anchor element, use href(hyperlink reference), use target="_blank" to open new tab, inside the ahchor tags, you can put image elements as well as text elements

<p id="top"> </p>

<a href="#top">go to top</a> : can put "#id" to go to specific section of the same page, 

<!-- --> : comment


Chapter 3.

<table>
  <thead> : table head : mainly table headings
    <tr> : table row
      <th scope="column"> </th> : table heading, use scope to state what the title is for, 
      <td colspan="2" rowspan="2"> </td> : table data, use colspan to make it occupy many columns, use rowspan to make it occupy many rows
    </tr>
  </thead>
  <tbody> : table body : mainly data
  </tbody>
  <tfoot> : table foot : mainly tatal
  </tfoot>
</table>

use CSS...


Chapter 4.

<form action="destination.html" method="POST"> : data of form will be sent to destination.html, POST is html verb
  
  <label for="userid">ID : </label> : use label with for attribute to state purpose of data
  <input id="userid" name="userid" type="text"> : text type input, use id to connect with label, name - value pair
  
  <label for="userpswd">PW : </label>
  <input id="userpswd" name="userpswd" type="password"> : password type input (e.g. ****s)
  
  <label for="userage">AGE : </label>
  <input id="userage" name="userage" type="number" step="1"> : number type input, unit : 1
  
  <label for="useryear">SCHOOL YEAR : </label>
  <span>1</span>
  <input id="useryear" name="useryear" type="range" min="1" max="12" step="1"> : range type input
  <span>12</span><br>
  
  <p>Choose your pizza toppings:</p>
  <label for="cheese">Extra cheese</label>
  <input id="cheese" name="topping" type="checkbox" value="cheese">
  <br>
  <label for="pepperoni">Pepperoni</label>
  <input id="pepperoni" name="topping" type="checkbox" value="pepperoni">
  <br>
  <label for="anchovy">Anchovy</label>
  <input id="anchovy" name="topping" type="checkbox" value="anchovy"> : checkbox type input, name should be same, value should be defined already, 
  
  <form>
  <p>What is sum of 1 + 1?</p>
  <input type="radio" id="two" name="answer" value="2">
  <label for="two">2</label>
  <br>
  <input type="radio" id="eleven" name="answer" value="11"> : radio button type input, same with checkbox type
  <label for="eleven">11</label>
  
  <label for="lunch">What's for lunch?</label>
  <select id="lunch" name="lunch"> : dropdown list type input, use select&option, option should have pre-defined value
    <option value="pizza">Pizza</option>
    <option value="curry">Curry</option>
    <option value="salad">Salad</option>
    <option value="ramen">Ramen</option>
    <option value="tacos">Tacos</option>
  </select>
  
  <label for="city">Ideal city to visit?</label>
  <input type="text" list="cities" id="city" name="city"> : datalist type input, use datalist&option&attribute list, same with dropdown list

  <datalist id="cities">
    <option value="New York City"></option>
    <option value="Tokyo"></option>
    <option value="Barcelona"></option>
    <option value="Mexico City"></option>
    <option value="Melbourne"></option>
    <option value="Other"></option>  
  </datalist>
  
  <label for="blog">New Blog Post: </label>
  <br>
  <textarea id="blog" name="blog" rows="5" cols="30">Adding default text</textarea> : textarea type input, same with java texbox
  
  <input type="submit" value="Send"> : submit type input, value determines text on the button for submission
</form>


Chapter 5.

attribute required : input is required
attribute min, max : number input which is in the bounds is required
attribute minlength, maxlength : text input which has length in the bounds is required
attribute pattern : input which is in correct form is required using regular expression like /^[a-zA-Z0-9]{14,16}$/, /^[0-9]{3}[-]+[0-9]{4}[-]+[0-9]{4}$/


Chapter 6.

not yet
