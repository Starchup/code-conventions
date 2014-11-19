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


### [AngularJS](https://github.com/mgechev/angularjs-style-guide)

* Follow MVVM structure
	* Angular Controllers act as the ViewModel
	* Angular Services act as the Model
* For directory structure. Split high level by functionality, and low level by component type
* Over around 5 items in a single folder probably requires sub-folders. Use your own discretion to maximize readability
* Every Angular component should be in its own file
* File should be named after angular component
* Use inline array annotation for all dependenacy injection inside angular
* Use $on over $watch where possible
* Use $broadcast over $emit where possible
* Use Angular 1.3.x over 1.2.x
* Take advantage of [one-time binding](https://code.angularjs.org/1.3.3/docs/guide/expression) when possible
* When there's a lot of http calls, create separate service that handles the $http calls and specific urls. Inject service where needed

### Frontend JS

* Generally follow [Google's style guide](https://google-styleguide.googlecode.com/svn/trunk/javascriptguide.xml) important aspects will be highlighted
* Code width: 100 characters
* Tab size: 4 spaces
* Always use var to declare variables
* Semicolons needed
* Follow [Google's naming convention](https://google-styleguide.googlecode.com/svn/trunk/javascriptguide.xml?showone=Naming#Naming)
* Follow [Google's specific code formation](https://google-styleguide.googlecode.com/svn/trunk/javascriptguide.xml?showone=Code_formatting#Code_formatting)
* For all strings, prefer ' over " 
	* e.g. 'this' over "this"
* Sections of code should have line breaks between them for readability
* use 'use strict' for all JavaScript, [what it does](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Strict_mode)


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
