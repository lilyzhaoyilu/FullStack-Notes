# k-- & --k

```javascript
let u = 3

//先比较，再运算--，所以不符合规定的0
while(u-- > 0) console.log(u)
2
1
0
//这时候 u = -1

//先运算，再比较
while(--u > 0) console.log(u)
2
1
//这时候u = 0
```



