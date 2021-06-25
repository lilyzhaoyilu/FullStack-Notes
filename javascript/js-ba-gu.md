# JS八股

### ​JS - datatypes

* Number \(primitive type\)
* String \(primitive type\)
* Boolean  \(primitive type\)
* Undefined  \(primitive type\)
* Null ****\(primitive type\)
* Objects  A **primitive type** is data that is not an object and cannot have methods. This is different from Ruby where everything is an object and we could do things `-5.abs     js can do` Math.abs\(-5\)

Falsey Values: 0. undefined, null, NaN

JS Obejects - can store both **state** \(variables\) and **behavior** \(methods\)

JS global:  If you leave off a declaration when initializing a variable, it will become a global. Never do this.

闭包closure: 内层作用域需要引用它上层作用域里的变量/参数，就是闭包。（函数就是闭包?\)

### 深拷贝 & 浅拷贝

 **深拷贝是指源对象与拷贝对象互相独立，其中任何一个对象的改动都不会对另外一个对象造成影响**。举个例子，一个人名叫张三，后来用他拷贝出（假设法律允许）另外一个人叫李四，不管是张三缺胳膊少腿还是李四缺胳膊少腿都不会影响另外一个人，这就是深拷贝了。比较典型的深拷贝就是JavaScript的“值类型”\(7种数据类型），如 [string](https://developer.mozilla.org/en-US/docs/Glossary/string)，[number](https://developer.mozilla.org/en-US/docs/Glossary/number)，[bigint](https://developer.mozilla.org/en-US/docs/Glossary/bigint)，[boolean](https://developer.mozilla.org/en-US/docs/Glossary/boolean)，[null](https://developer.mozilla.org/en-US/docs/Glossary/null)，[undefined](https://developer.mozilla.org/en-US/docs/Glossary/undefined)，[symbol](https://developer.mozilla.org/en-US/docs/Glossary/symbol) 。

