**Exercise on adding elements via java script**

This repository contains an example of how to add an elements like h1,h2...tags,<p>,<div> ,<img> tags to webpage dynamically using java script.

**EXAMPLE**

1. TO CREATE H1 ELEMENT AND ADD CONTENT NEED TO ADD FOLLOWING CODE


   var a=document.createElement("div");
   var b=document.createElement("h2");//THIS CODE TO CREATE h2 ELEMENT

   b.textContent="my heading goes here"; //this to add content to your element.
   a.appendChild(b)

  document.body.appendChild(a); //here we are appeding element to div  

  2.  TO CREATE IMAGE ELEMENT

        var a=document.createElement("div");
        var d=document.createElement("img");
        d.src="cat.jpeg";
        a.appendChild(d);

