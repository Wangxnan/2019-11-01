   # this 
    this: 他是js中的关键字，有特殊的特殊的意义  
    this：他就是函数的执行主体，谁执行函数this就是谁



     1、在全局作用域下，this就是window
     2、函数执行时，看执行函数前有没有 ".",如果有点，那点前面是谁，this就是谁，如有没有点，那this就是window
     3、自执行函数里的this是window
     4、给元素事件行为绑定方法，方法里的this指向被绑定的元素本u1

- console .log (this)  // window
- console .log (this === window)  // true 

自执行函数里的this都是 whindow