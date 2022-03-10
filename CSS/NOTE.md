基本类型值：数字、字符串、布尔、undefined、null
var a = b; ———— 内存中产生新的副本（改变b时不改变a）

let a = 100;
let b = a;
a = 200;
console.log(b); // 100


引用类型值：对象、数组...
var a = b; ———— 内存中不产生新的副本，而是让新变量指向同一个对象（改变b时改变a）

let a = { age: 20 };
let b = a;
b.age = 30;
console.log(a.age); // 30

todo：说清楚数据类型


浅拷贝: 以赋值的形式拷贝引用对象，仍指向同一个地址，修改时原对象也会受到影响
深拷贝: 完全拷贝一个新对象，修改时原对象不再受到任何影响

todo：看明白，自己实现
https://juejin.cn/post/6844903929705136141#heading-6

