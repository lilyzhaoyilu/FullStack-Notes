# JS quick notes

.sort\(\(a,b\) a-b\) asending



Array\(array length\) to make an array with empty stuff

Array\(10,a\) to make an array like \[10,a\]

.fill\(0\) make every element in the array 0

```javascript
.map(() => ({}))

> aa.map(()=>({}))
[
  {}, {}, {}, {},
  {}, {}, {}, {}
]
> aa.map((e)=>({e}))
[
  { e: 0 }, { e: 0 },
  { e: 0 }, { e: 0 },
  { e: 0 }, { e: 0 },
  { e: 0 }, { e: 0 }
]
```



```javascript
 let a = [ [ 6, [ 7, 4 ] ], [ 9, 8 ] ]
a.flat() = [ 6, [ 7, 4 ], 9, 8 ]
a.flat(Infinity) = [ 6, 7, 4, 9, 8 ]
a.toString() = '6,7,4,9,8'
```

```javascript
['a','a','c'].join() = 'a,a,c'
['a','a','c'].join('') = 'aac'
['a','a','c'].join('-') = 'a-a-c'
```

### slice, substr, substring

```javascript
> a = '0123456'
'0123456'

//slice [startIndex, endIndex)
> a.slice(1,4)
'123'

//substring [startIndex, endIndex)
> a.substring(1,4)
'123'

//substr [startIndex, length]
> a.substr(1,4)
'1234'

//none of them changes a
> a
'0123456'
>
```

