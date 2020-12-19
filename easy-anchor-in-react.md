# Easy Anchor in React

Here is an easy way to have anchors in react using scrollIntoView



```text
class Demo extends React.Component {
constructor(props){
    super(props);
    this.scrollToAnchor = this.scrollToAnchor.bind(this);
}
  
scrollToAnchor (anchorId){
    if (anchorId) {   
        let anchorElement = document.getElementById(anchorId);
        
      if(anchorElement) {       
			anchorElement.scrollIntoView();}
			}
}

render(){
<div>

<button onClick={()=>(this.scrollToAnchor("target1"))}>
Scroll Down To Target1
</button>



<div className="splash-content-two" id='target1'></div>
}
```

