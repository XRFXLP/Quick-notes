Kotlin is a statically compiled languages, it compiles to byte code which gets executed by Java virtual machine.   
Files are saved with `.kt` extension.  

"Hello World" program
```kotlin
fun main()
{
  println("Hello World");
}
```
Like JavaScript, the semi-colons are not mandatory  
And like C `main()` function is mandatory in every kotlin project.    
In kotlin, one can print any statement using either `println()` or `print()`, but the primary difference between the two is that former creates a new line
character after printing but later does not.
Comments are like C-family languages  

Variable declaration:
```kotlin
var variableName: variableType = variable value;
```
or 
```kotlin
var variableName: variableType;
variableName = variableValue
```
In order to declare immutable data type, use `val` instead of `var`.  
Kotlin follows camelCase naming convention.  
Date types: `String`, `Double`, `Char`, `Int`, `Boolean`, `Float`, `Long`, `Byte`, `Short`  

In kotlin compiler can automatically infer the type of a variable, and hence `var x = 4` is valid, but subtle point is that the type of variable cannot be changed during the whole program.  

String interpolation: 
```kotlin
"Hello $myVariable"
```   
User input: 
```kotlin
var variable = readLine()
```

In order to get length, use `.length`(this is not a function, just an attribute)
