<h1 align="center">Loli Sharp Language     <img align="center" img width="40" height="40"  hspace="20"  src="/Pictures/LoliSharp.png"></h1>

<br>
<br>

## Table of Contents

<details>
<summary>Variable</summary>

- [String](#variable-string)
- [Integer](#variable-integer)
- [Double](#variable-double)
- [Boolean](#variable-boolean)

</details>

<details>
<summary>List</summary>

- [String](#)
- [Integer](#)
- [Double](#)
- [Boolean](#)

</details>

<details>
<summary>Function</summary>

- [String](#)
- [Integer](#)
- [Double](#)
- [Boolean](#)
- [Void](#)
- [List](#)

</details>

<details>
<summary>Condition</summary>

- [If](#)
- [Else](#)
- 
</details>

<details>
<summary>Ring</summary>

- [While](#)
- [For](#)
- [Foreach](#)

</details>

<br>

# Variable

### Variable-String

OverView:
  ```
  Var [VariableName] as String = '[Value]'
  ```
Example:
  ```
  Var LanguageName as String = 'Loli Sharp Language'
  ```

<br>

### Variable-Integer

OverView:
  ```
  Var [VariableName] as Integer = [Value]
  ```
Example:
  ```
  Var LatestVersion as Integer = 1
  ```

<br>

### Variable-Double

OverView:
  ```
  Var [VariableName] as Double = [Value]
  ```
Example:
  ```
  Var FullLatestVersion as Double = 1.0.0
  ```

<br>

### Variable-Boolean

OverView:
  ```
  Var [VariableName] as Boolean = True/False
  ```
Example:
  ```
  Var WithConpileCSharp as Boolean = True
  ```

<br>

# Function

### Function-String

OverView:
  ```
  Function [FunctionName]([Parameters]) as String
  [
    Return [StringValue]
  ]
  ```
Example:
  ```
  Function HeyHello(FirstName as String,LastName as String) as String
  [
    Return $'Hello {FirstName} {LastName}'
  ]
  ```

<br>

### Function-Integer

OverView:
  ```
  Function [FunctionName]([Parameters]) as Integer
  [
    Return [IntegerValue]
  ]
  ```
Example:
  ```
  Function Calculator(NumberOne as Integer,NumberTwo as Integer) as Integer
  [
    Return NumberOne + NumberTwo
  ]
  ```

<br>

### Function-Double

OverView:
  ```
  Function [FunctionName]([Parameters]) as Double
  [
    Return [DoubleValue]
  ]
  ```
Example:
  ```
  Function Calculator(NumberOne as Double,NumberTwo as Double) as Double
  [
    Return NumberOne + NumberTwo
  ]
  ```

<br>

### Function-Boolean

OverView:
  ```
  Function [FunctionName]([Parameters]) as Boolean
  [
    Return [BooleanValue]
  ]
  ```
Example:
  ```
  Function RrturnTrue() as Boolean
  [
    Return True
  ]
  ```

### Function-Void

OverView:
  ```
  Function [FunctionName]([Parameters]) as Void
  [
    [Codes]
  ]
  ```
Example:
  ```
  Function SeyHello() as Void
  [
    Alert('Hello')
  ]
  ```
### Function-List

OverView:
  ```
  Function [FunctionName]([Parameters]) as List
  [
    Return [ListArray]
  ]
  ```
Example:
  ```
  Function [FunctionName]() as List
  [
    Var LoliVs as List<String> = {'LoliScript','LoliSharp'}

    Return LoliVs
  ]
  ```
