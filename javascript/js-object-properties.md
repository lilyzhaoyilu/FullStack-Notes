# JS Object Properties

为转化

```text
> o = {}
{}
> let d = 'dynamic'
undefined
> o.d = 'notdynamic'
'notdynamic'
> o['d2'] = 'notdynamic'
'notdynamic'
> o[d] = 'trydynamic'
'trydynamic'
> o
{ d: 'notdynamic', d2: 'notdynamic', dynamic: 'trydynamic' }



```

|  | Obj.新的内容 | obj\['新的内容'\] | obj\[内容\] |
| :--- | :--- | :--- | :--- |
|  | 会把\`新的内容\`自动转化为string | key可以是有空格的string | 内容是个variable，可以dynamically define |



