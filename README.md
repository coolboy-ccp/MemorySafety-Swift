# MemorySafety-Swift([swift.org](https://docs.swift.org/swift-book/LanguageGuide/MemorySafety.html#))
swift中的内存安全

## 什么是内存安全
* 确保变量在使用前已经被初始化
* 确保变量在释放后不被访问
* 数组索引是否存在越界错误
* 修改内存中位置的的代码具有对该内存的独占访问权限。
Swift确保对同一内存区域的多次访问不会冲突，如果代码中包含内存冲突，则会出现编译或运行时错误
## 内存访问的特征
* 至少一个是写访问权限
* 访问内存中相同位置
* 持续时间重叠
