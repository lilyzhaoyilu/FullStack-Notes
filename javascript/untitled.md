# JS Sort Methods

### 按照字典序排序

或者直接排序

```text
[...dishname].sort()
```

sort叠写 +字典序排序 LC642

```javascript
    let ret = ans.sort((a,b) => {
        if(a.time == b.time){
            //这里是a.word 的字典序小于 b
            //想要的就是-1
            if(a.word < b.word) return -1
            return 1
        }
        return b.time - a.time
    })
```

