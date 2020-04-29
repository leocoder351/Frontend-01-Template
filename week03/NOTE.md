## JavaScript 哪些对象是我们无法实现的

- 基本类型
  - Boolean
  - String
  - Number
  - Symbol
  - Object
- 引用类型
  - Array
  - Date
  - RegExp
  - Promise
  - Proxy
  - Map
  - WeakMap
  - Set
  - WeakSet
  - Function
- 错误类型
  - Error
- 二进制
  - ArrayBuffer
  - SharedArrayBuffer

## 对象
- 宿主对象
  - 由宿主环境提供的对象，比如浏览器环境中window、document
- 内置对象
  - 固有对象：由标准规定，在javacript运行时创建的对象实例
  - 原生对象：通过javascript语言本身的构造器创建的对象，被称为原生对象。例如Date、RegExp等，可以通过new运算符创建，但是无法用纯JavaScript实现