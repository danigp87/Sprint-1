LA IMAGEN ES EL LINK
<p><a href="#"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a></p>

LINK AL FINAL DE LA PÁGINA
<a href="#footer">
<footer> //Esto está al final del html

Unordered lists start with an opening <ul> element, followed by any number of <li> elements. Finally, unordered lists close with a </ul>.
For example:
<ul>
  <li>milk</li>
  <li>cheese</li>
</ul>

Ordered lists start with an opening <ol> element, followed by any number of <li> elements. Finally, ordered lists are closed with the </ol> tag.
For example:
<ol>
  <li>Garfield</li>
  <li>Sylvester</li>
</ol>

Subes una foto a la web introduciendo el link en el input
<form action="https://www.freecatphotoapp.com/submit-cat-photo">
    <input type="text" placeholder="cat photo URL">
    <button type="submit">Submit</button>
  </form>

El REQUIRED obliga a poner algo en el input
<input type="text" placeholder="cat photo URL" required>

CHECKED hace que venga marcado por defecto
<input type="radio" name="test-name" checked>

Se pone arriba del todo del html
<!DOCTYPE html>

---

Carpetas de un proyecto: html, css, images, js

Una imagen con un pie de foto
<img src="url" alt="alternatetext">

Transiciones de elementos
https://www.w3schools.com/css/css3_transitions.asp

Animaciones
https://www.w3schools.com/css/css3_animations.asp






#background1 {
    margin: auto;
    max-width: 1200px;
    height: 120px;
    padding: 15px;
    background-color: black;
    box-sizing: border-box;
    flex-flow: row wrap;
}

#background2 {
    margin: auto;
    margin-top: 25px;
    max-width: 1200px;
    height: 150px;
    padding: 15px;
    background-color: black;
    box-sizing: border-box;
    flex-flow: column wrap;
}

#background3 {
    margin: auto;
    margin-top: 25px;
    max-width: 1200px;
    height: 40px;
    padding: 15px;
    background-color: black;
    box-sizing: border-box;
}

#firstLayer1 {
    margin: auto;
    height: 40%;
    background-color: rgb(255, 255, 255);
    border: 1px solid red;
}

#firstLayer2 {
    margin: auto;
    margin-top: 15px;
    height: 40%;
    background-color: rgb(255, 255, 255);
    border: 1px solid red;
}

#firstLayer3 {
    margin: auto;
    width: 65%;
    height: 100%;
    background-color: rgb(255, 255, 255);
    border: 1px solid red;
    float: left;
   
}

#firstLayer4 {
    margin: auto;
    width: 33%;
    height: 100%;
    float: right;
    background-color: rgb(255, 255, 255);
    border: 1px solid red;
    
}