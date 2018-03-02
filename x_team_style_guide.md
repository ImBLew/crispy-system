# X-Team NN Style Guide

Code should be easy for humans to read and understand.

## Naming conventions

Standard naming conventions allow easier readability for complex code.

### Examples
* interfaces
  * IInterfaceExample
* classes
  * public ExampleClass
* exception types
  * ExampleNotFollowedException
* fields
  * int thisIsAField
* methods
  * public void thisIsAMethod()
* parameters
  * thisIsAMethod(String firstArg, int secondArg)
* local variables
  * private int \_localVariable
* instance constants
  * private final int \_LOCAL_CONSTANT
* class constants
  * public static final int CONSTANT_VARIABLE

## Commenting style for public and private members of a class or interface:

Code and commenting style should be standard across a program to allow for easier readability 

### Examples

* classes
  * Javadoc purpose of class
* fields
  * Name should be self explanatory
* constructors
  * Javadoc should explain constructor purpose and outcome
* methods
  * Name should be self explanatory, javadoc used for finer details
    * Example: Substring method name is self explanatory, javadoc explains start and end points
* coding style (brackets, horizontal, and vertical spacing) for:
  * if statements
    * ```java
      if(boolean) {
         ...
      }
      else { 
         ...
      }
      ```
  * switch statement
    * ```java
      switch(String) {
         case "a":
                  break;
         case "b":
                  break;
         default:
      }
      ```
  * while loops
    * ```java
      while(boolean) {
         ...
      }
      ```
  * for loops
    * ```java
      for (int i = 0; i < n; i++) {
         ...
      }
      for (int j = n; j > 0; j--) {
         ...
      }
      ```
  * enhanced for loops
    * ```java
      for (String s : list) {
         ...
      }
      ```
## Anthony's Edit
** I wrote this because I have to
**BOLD**
