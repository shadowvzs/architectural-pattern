# architectural-pattern
*(javascript MVC, MVVM samples)*

#### Sample Code:
* [MVC - VanillaJS](https://github.com/shadowvzs/architectural-pattern/tree/master/mvc)
* [MVVM - KnockoutJS](https://github.com/shadowvzs/architectural-pattern/tree/master/mvvm/knockoutJS)

-----------------------------------
* **Note:** this repo was created to help beginners about how the js **mvc**, **mvvm** work
-----------------------------------
* Feature:
    * add/update/save/load/delete item into localStorage
    * create list and keep track click count on image and update time
    
* Test: https://shadowvzs.github.io/architectural-pattern/
-----------------------------------

### MVC

* Description: 
    * show a basic mvc structure where model, view and controller was separated.
        * controller the *bridge* between model and view (no view don't have direct relationship with model)
    * heavily commented and logged in console so you can understand it easier.
    * multiple example in js folder
        * **es5.js** - old school object literal solution
        * **es6.js** - class/OOP solution
        * **es6_performance_optimized.js** - OOP solution with performance optimization in **View**:
            * event delegation
            * inheritance
            * if you update the item then only the changed DOM will be updated (comparison: old vs new data) 


### MVVM
* Description:
   * everythi9ng like above but dynamic with knockoutJS ViewModel
