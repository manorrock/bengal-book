---
description: First Steps
---

### Calling a  method

The example below calls the ```tick``` method on the ``timer`` instance.

  ```
  timer.tick();
  ```

### Assigning a result

The example below calls the ```reverse``` method on the ```myInstance``` instance and it will assign the result to ```myResult```.

  ```
  myResult = myInstance.reverse();
  ```

### Constructing a new instance

The example below creates an instance of ```MyClass```. 

  ```
  myInstance = new MyClass();
  ```

### Releasing an existing instance

The example below shows how to release an instance.

  ```
  delete myInstance;
  ```

### Defining a class

If you want to reuse your code you might consider wrapping it into a class
which can be constructed using the `new` keyword. The example below shows how
you would define the class named ```MyClass```.

  ```
  class MyClass {
  }
  ```
### Defining a class method

A class in and of itself does not do anything so you will need to define some 
class methods that can be called. The example below defines a class method for
pushing an item.

  ```
  push(item) {
  }
  ```

### Defining a class variable

A class would need to be able to store things so you can create variables that
are only visible to the class. The example below does that.

  ```
  class MyClass {
    var myVariable;
  }
  ```
