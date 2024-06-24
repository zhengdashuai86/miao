
* js语言常见报错:
  * Uncaught ReferenceError: n is not defined(定义)
    * 引用错误,指跟变量有关的错误,这里是说n这个变量没有定义,所以不能使用
  * Uncaught SyntaxError: missing（缺失） ) after argument list(参数列表)
    * 在函数的参数列表后面没有找到对应的结束括号
    * 往往是因为缺失了括号导致的
    * 参数列表已经开始,但还没正确结束,就遇到了其它的内容
  * Uncaught SyntaxError: Unexpected identifier(标识符) 'a1'
    * 语法错误,没想到在那个位置遇到一个标识符
      * 什么是标识符？变量名，函数名
  * Uncaught SyntaxError: Unexpected(未预料到的) token 'var'
    * 语法错误,没想到在那个地方遇到这样一个token
      * 什么是token?词元,即代码中不可再拆分的连续符号组成的程序的最基本单元
        * 如一个变量名
        * 一个数值
        * 一个true/false
  * -2**3:   Uncaught SyntaxError: Unary operator(一元运算符) used immediately before(紧挨着的前面) exponentiation expression(幂运算表达式). Parenthesis(括号) must be used to disambiguate(去除歧义) operator precedence(运算符的优先级)
    * 一元运算挨着幂运算的前面使用了,这时必须使用括号以去除代码中运算符产生的优先级的模糊性/歧义
    * 应该是把前面这个一元运算与其运算数用括号包起来
  * Uncaught SyntaxError: Unexpected end of input
    * 未预料到代码在这里就结束了
    * 意思是它本来希望后面还有东西的,结果确是戛然而止了

* isNaN()函数:只要传入的不是数,就返回true
* Number.isNaN():只有传入NaN的时候返回true
* 花括号可以把多条语句合成一条语句
