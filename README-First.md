# How to Use This Application 

### 1. Clone Repository 
  * Go to the **Local Folder** where you would prefer to save the file and 	 enter the following code : 

    	` git clone https://github.com/BlueThorn1608/Website-Optimisation.git `

  * The Application will be available on your work station. 

### 2. Direct Download 
_(Only if Method 1 doesn't work)_
  * Go to the link provided -> [click me](https://github.com/BlueThorn1608/Website-Optimisation.git). 
  * Download the Zip File and **Extract** the contents into desired directory. 

### 3. Running the Application 
  * Run `index.html` on your browser. 
  * There exist sublinks to the application, feel free to explore 


  xxxxxxxxxxxxxxxxxxxxxxxxx**ENJOY**xxxxxxxxxxxxxxxxxxxxxxxxx

## Changes Made 

### index.html
  * line 15 - inline CSS.
  * line 144 - added the print media property.  
  * line 155 - added the async property.
  * line 192 - resized the pizzeria image.
  * line 204 - using Javascript to load the fonts using the web font loader.

### Views/pizza.html
  * line 6 - inline CSS.

### Views/main.js
  * line 408 - declared variable `pizzaSize` outside the loop, using `document.getElementById()` which is faster.
  * line 457 - decimals changed to '%' and `return` statements are removed.
  * line 469 - moved variable `randomPizza` outside the loop and changed to `document.getElementsByClassName()`.
  * line 471 - variable `length` to store array length, prevents repeated calling.
  * line 473 - removed `determineDx()`.
  * line 489 - `pizzasDiv` variable declared outside the loop, so DOM call is made once.
  * line 522 - `document.getElementsByClassName()` to make it faster.
  * line 524 - variable `scrollTop` is declared outside the loop, should prevent FSL.
  * line 525 - variable `phase` , empty array to store phase calculations.
  * line 529 - variable `value` to store array length, prevents calling everytime the loop iterates. 
  * line 550 - variable `movingPizza` is declared outside the loop.
  * line 555 - reducing the number of background pizza's generated.
  * line 557 - variable `elem` declared outside the loop.