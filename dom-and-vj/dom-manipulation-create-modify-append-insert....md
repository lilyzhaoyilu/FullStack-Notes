# DOM Manipulation: Create, Modify, Append, Insert...

The text inside HTML elements are text nodes.

With the HTML DOM, you can navigate the node tree and access nodes in the tree using node relationships, such as parent, children, siblings. 

New nodes can be created, and all nodes can be modified or deleted. 

Every node has exactly one parent, except the top node which has no parent.



## How to Create Elements

```javascript
const createEl = documnet.createElement('div')
console.log(createEl) // <div></div>
```

## Set innerHTML

```javascript
const innerhtml = createEl.innerHTML = ' i am a frontend developer'
console.log(createEl) // <div> i am a front end developer </div>
```

Append an Element

```javascript

<div id="parent">
        <div id="firstchild">i am a first child</div>
        <p id="secondchild">i am the second child</p>
        <h4>i am alive</h4>
        <h1>hello world</h1>
        <p>i am the last child</p>
</div> 
    
const ele = document.createElement('div')
ele.innerHTML = 'balaba'
const parent = document.getElementbyId('parent')
parent.appendChild(ele)

    
```

