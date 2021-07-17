# DOM Manipulation: Select

## Select elements in the DOM

### .getElementById  \(id -&gt; caseSenstive\)

getElementById returns one element 

```javascript
<p id="master">i love javascript</p>

 <script>
const masterEl = document.getElementById('master')
console.log(masterEl) //<p id="master">i love javascript</p> 
 </script>
```

### .getElementsByClassName\(\)    \(multiple, like array can access \[0\]\)

returns **a collection\(array like\)** of all elements in the document with the specified class name 

```javascript
        <p class="master2">i love javascript</p>
        <p class="master2">i love react</p>
        <h1 class="master2">i want a job</h1>

        <button id="btn">click me</button>
 
 <script>
 
 const btn = document.getElementById('btn')
        
        btn.addEventListener('click', function master(){
            var master = document.getElementsByClassName("master2");
            master[2].innerHTML = 'i need a job';
        })

</script>

If you click the button it would select all the elements with a class name 
of "master2" and change the innerHTML of the 3rd element.
```

### .getElementsByTagName\(\)    \(multiple, like array can access \[0\]\)

returns **all the elements** of the specified tag name in the order which they appear in the document

```javascript
<p>VsCode</p>
 <p>Atom</p>
 <p>Sublime text</p>
        <button id="btn">click me</button>
       

 <script>

const btn = document.getElementById('btn')
        
        btn.addEventListener('click', function master(){
            let master = document.getElementsByTagName('p');
            let masterEl = master[1].innerHTML = 'Code editors';
            console.log(masterEl) //Code editors
        })

//<p>Atom</p> changes to <p>Code editors</p>
</script>
```

### .querySelector\(\)

This returns the first value that matches the selector it’s given. This method can accept all CSS style selectors, allowing it to select by tag, class, or ID. \(.class, \#id, input\[type = 'text'\]\)

```text
<div id=master>i am a frontend developer</div>

<script>
const master = document.querySelector("#master") 
</script>
```

### .querySelectorAll\(\)

This works similar to above which returns a node list collection of all matching elements.

```javascript
     <p class="master">React</p>
     <p class="master">Vue</p>
     <p class="master">Angular</p>

<script>
const master = document.querySelectorAll(".master") 
console.log(master[1])  //<p class="master">Vue</p>
</script>
```

### parentNode\(\)

```text
const elesParent = ele.parentNode
```

[https://www.freecodecamp.org/news/how-to-manipulate-the-dom-beginners-guide/](https://www.freecodecamp.org/news/how-to-manipulate-the-dom-beginners-guide/)

