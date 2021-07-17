# JS & DOM Manipulation

### Select elements in the DOM

#### \`getElementById\`  \(id -&gt; caseSenstive\)

getElementById returns one element 

```javascript
<p id="master">i love javascript</p>

 <script>
const masterEl = document.getElementById('master')
console.log(masterEl) //<p id="master">i love javascript</p> 
 </script>
```

#### \`getElementsByClassName\(\)\`

returns a collection\(array like\) of all elements in the document with the specified class name 

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



[https://www.freecodecamp.org/news/how-to-manipulate-the-dom-beginners-guide/](https://www.freecodecamp.org/news/how-to-manipulate-the-dom-beginners-guide/)

