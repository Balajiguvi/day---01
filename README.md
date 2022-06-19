1.**Write a blog on Difference between HTTP1.1 vs HTTP2**
   ANS:  
   HTTP/1.1
      Ithe usest works on the textual format.
      There is head of line blocking that blocks all the requests behind it until it doesn’t get its all resources.
      It uses requests resource Inlining for use getting multiple pages
      It compresses data by itself.
      
  HTTP/2
     It works on the binary protocol.
     It allows multiplexing so one TCP connection is required for multiple requests.
  	 It uses PUSH frame by server that collects all multiple pages 
     It uses HPACK for data compression.
     
2.**Write a blog about objects and its internal representation in Javascript**
   ANS:  
    Objects.
     Objects in JavaScript may be defined as an unordered collection of related data, of primitive or reference types, in the form of “key: value” pairs. These keys can      be variables or functions and are called properties and methods, respectively, in the context of an object.
     
  Internal properties in JavaScript.
     Internal properties define the behavior of code as it executes but are not accessible via code. ECMAScript defines many internal properties for objects in                JavaScript. Internal properties are indicated by double-square-bracket notation. For example, JavaScript function is an object and it has [[call]] property.
