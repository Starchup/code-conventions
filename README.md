Starchup Code Conventions
=========================

### Backend JS

* Code width: 100 characters
* Tab size: 4 spaces

* Referencing other models `CurrentModel.app.models.OtherModel.method()`  
	Should always have its own line:  
  `OtherModel = CurrentModel.app.models.OtherModel`  
  `OtherModel.method();`

* Wrapping of `{}`: Any function that contains more then 1 line of code should be wrapped as such:
  ```
  myFunction()
  {
      ...
  }
  ```
  ```
  if(x == y)
  {
      ...
  }
  ```
  
* Comments: All custom functions/methods/hooks should have descriptive comments
  ```
  /**
   * This function does this great thing!
   *
   * @param {First parameter}   greatId
   *
   * @callback {Function}       callback
   *
   * @param {Error}             err
   * @param {What it returns}   greatResult
   */
   ```


### Backend JSON

* Code width: 100 characters
* Tab size: 2 spaces


### Frontend JS


### Frontend CSS
