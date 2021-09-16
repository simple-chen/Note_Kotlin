**字符串模板**

```
1.字符串字面值中引用局部变量，在变量名称前加$   println("Hi,$name")
2.引用更复杂的表达式，将表达式用花括号括起来    println("Hello,${if (list.size < 0) user.name else "null"}")
3.如果要在字符串中使用$,需要在$前加转义符号/    println("\$x")
```

```kotlin
    println("Hello,${if (list.size < 0) user.name else "null"}")
    println("Hi,$name")
    println("\$x")
    println("你好，${person.name}")
```

