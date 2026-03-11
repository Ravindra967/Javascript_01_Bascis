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
        
        
        6. What is Event Handling?
        
                Event handling means:
                
                Detect an event and run some code
        
        7. Ways to Add Events
        
        There are 3 methods.
        
        Method 1 Inline Events (Old Method)
        
        HTML:
        
        <button onclick="showMessage()">Click</button>
        
        JavaScript:
        
        function showMessage(){
           alert("Hello");
        }
        
        Problems:
        
        Hard to maintain
        
        Mixes HTML and JavaScript
        
        Developers avoid this.
        
        Method 2 DOM Property
        
        JavaScript:
        
        const button = document.querySelector("button");
        
        button.onclick = function(){
           console.log("Clicked");
        };
        
        Problem:
        
        Only one event allowed.
        
        Method 3 addEventListener (Best Method)
        
        This is the modern standard.
        
        Example:
        
        const button = document.querySelector("button");
        
        button.addEventListener("click", function(){
           console.log("Button clicked");
        });
        8. Syntax of addEventListener
        
        General syntax:
        
        element.addEventListener(event, function, options);
        
        Explanation:
        
        Part	Meaning
        element	HTML element
        event	action like click
        function	code to run
        options	capturing or bubbling
        
        Example:
        
        button.addEventListener("click", showMessage);
        9. How Code is Declared and Initialized
        
        Full example.
        
        HTML:
        
        <button id="btn">Click</button>
        
        JavaScript:
        
        // Step 1 select element
        const button = document.getElementById("btn");
        
        // Step 2 define function
        function showMessage(){
           console.log("Button clicked");
        }
        
        // Step 3 attach event
        button.addEventListener("click", showMessage);
        
        Flow:
        
        Select element
        ↓
        Create function
        ↓
        Attach event listener
        ↓
        User triggers event
        ↓
        Function executes
        10. Event Object
        
        Whenever an event happens, the browser creates an event object.
        
        Example:
        
        button.addEventListener("click", function(event){
           console.log(event);
        });
        
        The event object contains:
        
        mouse position
        keyboard key
        target element
        timestamp
        
        Example:
        
        document.addEventListener("keydown", function(event){
           console.log(event.key);
        });
        
        Output:
        
        a
        b
        c
        Enter
        11. Event Target
        
        The element that triggered the event.
        
        Example:
        
        button.addEventListener("click", function(event){
           console.log(event.target);
        });
        
        Used in:
        
        dynamic lists
        
        event delegation
        
        12. Types of DOM Events
        
        There are many categories.
        
        1 Mouse Events
        
        Used when interacting with mouse.
        
        Examples:
        
        click
        dblclick
        mouseover
        mouseout
        mousedown
        mouseup
        mousemove

        
  

  
