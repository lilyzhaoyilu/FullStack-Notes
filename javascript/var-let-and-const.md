# Var, Let and Const

reference: [https://www.freecodecamp.org/news/var-let-and-const-whats-the-difference/](https://www.freecodecamp.org/news/var-let-and-const-whats-the-difference/)

| name | scope | can be redeclared | can be updated | hoisting |
| :--- | :--- | :--- | :--- | :--- |
| var | globally scoped or function/locally scoped. | yes | yes | to the top of the scope as 'undefined' |
| let | block {} \(same name in diff. scope are treated as diff. ones\) | no | yes | to the top, 'reference error' |
| const | similar to let | no | no, but its properties can be updated | to the top, but not initialized |



