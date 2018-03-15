#### expression & statement
- expression :表达式。一个表达式会产生一个值。

- statement: 语句。由一个或多个表达式组成的句子。

#### output & input
调试必备的console.log(),之前一直没有想过到底是什么含义，今天才知道，console是一个对象，而log只是其中的一个函数，在控制台直接输入console会发现还有很多方法。例如:console.info()，console.error()。上次还学到一个，可以用console.table(object),这样可以很直观的看到对象里的内容。
e.g
![](http://ww1.sinaimg.cn/large/9bd18299gy1fpdr5k83y3j20hh04w3yp)

#### Operators
- Object Property Access: . as in console.log()
- obj.a means an object value called obj with a property of the name a. Properties can alternatively be accessed as obj["a"]

#### Values & Types
- 基础类型
  - number
  - string
  - bool
- 高级类型
  - arrays
  - objects
  - function
  - null
  - undifined

null表示“没有对象”，即此处不应该有值

undefined表示“缺少值”，即此处应该有一个值，但是还没有定义

Converting Between Types

coercion 强制多态是编译程序程序的一种。通过语义操作，把操作对象的类型强行加以变换，以符合函数或操作符的要求。

说到类型这里就必须要说一下上文中的操作符，其中有==，===那这两个有什么区别呢，举个例子：

'99.99'99.99，这种情况下，js会把左边的字符串转为数字的99.99,因此这样作比对，结果肯定是true。

Note: For more information on coercion, see Chapter 2 of this title and Chapter 4 of the Types & Grammar title of this series.

#### Code Comments

//single line comment

/* */multiline comment