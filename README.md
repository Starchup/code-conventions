Starchup Code Conventions
=========================

### Backend JS

* https://google-styleguide.googlecode.com/svn/trunk/javascriptguide.xml
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

* Code width: 100 characters
* Tab size: 4 spaces


### Frontend CSS

* Code width: 100 characters
* Tab size: 4 spaces
* Always shorthand color hash i.e. '#777777' = '#777'.
* All measurements are to be in px, not em. (1em = 16px)
* Selectors are to be in alphabetical order (within modules or not)
* Color values and opacities equal to '1' should be written as such (and NOT '1.0').
* Color fraction values e.g. '0.3' must have the '0.' before to ensure maximum compatability.
* 0px should always be written as '0'.
* CAPITALIZATION matters for font-familes! 'Proxima-Nova' ≠ 'proxima-nova'
