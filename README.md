# CSV Validator

CSV Validator library. You have 2 different validators types which can validate rows or columns. The library is provided with simple validators, but you can extent it by implementing your our validators. The library was during a stream.

## TODO

* [ ] What is a CSV file?
  * Comma Separated Values
  * Where can be used?
  * Is it better or not than JSON or XML?
* [ ] What design patterns are?
* [ ] Which design patterns are we going to use?
  * Strategy design pattern
  * Iterator design pattern
* [ ] Implementation
  * [ ] Create input interface and dummy input which always return the same CSV
  * [ ] Create error output interface
    * [ ] Create exception output - it will validate the file till first error
    * [ ] Create error output stream - it will print all the errors to the given output
  * [ ] Implement the validator itself
  * [ ] Create interfaces for validators (row validator, column validator)
  * [ ] Create at least one validator
