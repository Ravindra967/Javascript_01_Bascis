DOM 
        
      When a web browser page is loaded, the browser creates a Document Object Model of the page.

      Html code in body Body contain (h1,li, ul) -> Open in side the browser -> that browser             convert     into DOM
  
  
  create object for all of the inside all elemnts in side the code.

    console.log(document.location) here document is object we can access the models and properties     like location, log, access, title,URl by using head tag.


Accessing the DOM

getELementByTagName

        console.log(document.getElementByTagName("h1));
        length:
                 console.log(document.getElementByTagName("h1).length);

        
         
getElementByID
getElementByClassName
querySelector
         document.querySelector("h1") select classname by using dot (.className)
         id selector by using => #  #idname
querySelectorAll

        document.querySelector("");


1. Why we use document.querySelector()

In JavaScript, document represents the entire HTML page loaded in the browser.

So when we write:

document.querySelector(".title")

innerText
        const p = document.querySelector("p");
        console.log(p.innerText);
, textcontent, innerHtml


attributes

 href
 value
 type
 getAttribute(attrName)
 setSttribute(attrName, value)

        
  

  
