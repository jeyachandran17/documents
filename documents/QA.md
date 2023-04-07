## Qustion & answer

### 1. Difference between http 1.1 & http 2.0 ?

|`http 1.1`|`http 2.0`|
|----------|----------|
|In http 1.1 flow control on `the underlying TCP connection`.|In http 2 multiplexes streams of `data within a single TCP connection`.|
|It usest works on the `textual format`|It usest works on `the binary protocol`.|
|There is head of line blocks all the requests behind it until doesn'tget it's all resources.|It allows multiplexing so one TCP connection is required for multiple requests|
|It uses requests resource inlining for use getting multiple pages |It uses `push` frame by server that collects all multiple pages|
|It compresses data by itself|It uses `HPACK ( HPACK is a compression format for efficiently representing http header fields )` for data compression.|
|Introduces a warning header field to carry additional information about the status of a message. Can define 24 status codes, error reporting is quicker and more efficient.|Underlying semantics of HTTP such as headers, status codes remains the same|
|Its load time is take a few seconds|Its fastest than http 1.1 ( Load time ).|


### 2. About objects and its internal representation in Javascript.

### `Definition` :

- The object type represents one of javascript’s data types. Its used to store various keyed collections and more complex entities
    - The values are written as `"key:value"` pairs

### `Syntex` :

- `var object = { key_1: ”value_1” , key_2: “value_2”, key_3: value_n }`

- Property and value are separated by `colon ( : )` .

### `Example` :

- `var student = { name: ”abc” , class: “fourth”, roll_no: 22 }`  ( `name` is key & `"abc"` is a value )  `( or )`

- 
        var student = {  name: ”abc” ,

        class: “fourth”, 
   
        roll_no: 22 

        }

    - Student is a variable names are objects too and name, class, roll_no is keys,then abc, fourth , 22 is values.
    - Spaces and line breaks are not important. An object definition can span multiple lines


