---
description: 'https://www.freecodecamp.org/news/how-to-manipulate-the-dom-beginners-guide/'
---

# DOM Manipulation: Event Handling

## What are HTML events? 

HTML events are "things" that happen to HTML elements like the click of a button, input in a text area... etc. When an event occurs like the ones above, you can write JS code which we call an event handler that will be executed.



> You can add many event handlers to one element.

> You can also add many event handlers of the same type to one element, like two "click" events.

```text
target.addEventListener(type, listener, options);


buttonEl.addEventListener('click', addFunction)

 function addFunction(){
     buttonEl.classList.add('button')
  }
```

