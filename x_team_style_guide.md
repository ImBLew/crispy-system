# X-Team NN Style Guide

<brief description of your team's opinion or philosophy regarding Style Guides>

## Naming conventions

<brief statement describing your team's naming conventions>

### Examples
* interfaces
* classes
* exception types
* fields
* methods
* parameters
* local variables
* instance constants
* class constants

## Commenting style for public and private members of a class or interface:

<brief statement of your team's commenting style>

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
