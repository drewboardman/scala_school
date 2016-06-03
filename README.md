##Values and Variables
    - Variables can be declared and re-bound
      `var name = 'drew'`
      `name = 'some other name'`

    - Values can be declared but you cannot change the binding
      `val two = 1 + 1`

##Functions
    - When you declare a function using `def` you need to provide a type signature
    
    ```scala
       def addOne(m: Int): Int = m + 1
       val three = addOne(2)
       three: Int = 3
    ```
