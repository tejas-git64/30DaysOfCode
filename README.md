## **#30DaysOfCode based on Javascript30**

### **Day 1: JS Drum kit**

<p align="center">
<img src="https://user-images.githubusercontent.com/67954224/143592962-1b6abb0d-e28a-4b4c-b771-203df303b094.png" width="700px"></p>

#### This project uses **eventHandlers** and **css attributes => 'keydown' , 'keyup'**
- Each key gives outputs a sound given for that key according to its **ASCII** value
- Uses HTML's `data-` attribute to play the assigned sound for each keypress. 
 
Styled with CSS ♥️ customize it if you wish!<br /><br />

### **Day 2: JS and CSS clock**

<p align="center">
 <img src="https://user-images.githubusercontent.com/67954224/143689509-e18ed22a-fd73-4c40-a762-65e99fa9a0f5.gif">
</p>

### The 2nd project of this series!! a clock!
This project uses JS's built in methods like **getMinutes()** and **getSeconds()** to depict the correct time
- Has three needles - hour, minutes and seconds
- Used `cubic-bezier()` to give that ticking effect just like in the original project

Styled like a wall clock 🕑 at home<br /><br />

### **Day 3: CSS varibles**

<p align="center"> 
 <img src="https://user-images.githubusercontent.com/67954224/144650934-bb429a6c-785e-43a4-bf62-7960cc6ce09b.gif">
</p>

### Playing with a few artistic CSS variables
Even here we use HTML's `data-` attribute, to assign units in px
- Uses CSS's pseudo class `:root` to assign custom values from each input i.e range-sliders & color picker
- Uses CSS's EventListeners like `change` & `mousemove` to update new values

### **Day 4: Array Methods-1**

### Brushing up some basic yet intriguing array methods
Here we're going to understand the usage of the following methods:
- `sort()` sorts elements in the ascending or descending order
- `split()` spilts an array/object based on the position assigned, used mainly in destructing objects
- `filter()` creates a new array filled with elements that pass a test provided by a function
- `reduce()` executes a reducer function for each value in an array and returns a single value which is the function's accumulated result
- `map()` creates a new array from the results of a previously existing function 



### **Day 5: Flexbox Gallery**

### its flexbox time!! one of most important topics in css, especially if you wanna play with images/div elements

### Here we use flexbox to align `p` elements to enlarge and shrink on click and also widen it

<p align="center"> 
 <img src="https://user-images.githubusercontent.com/67954224/145004754-abadf6c7-a433-481d-b61d-a9dfaf92b394.gif">
</p>

##### These are the main functions used to work with flexbox in this project

- `display: flex` activates flexbox
- `justify-content` aligns the div horizontally
- `align-items` align the div vertically
- `transform` fuction used to create sliding animations of the top and bottom `p` element
- `toggle()` This JS method is used to add and remove the class `open` which enlarges the font size of the middle `p` element
- `includes()` This is another JS methods that returns a boolean value if a string contains a specific character/string 

Flexbox allows seamless wrapping and resizing with the changing width of the page, it can be used along with media queries to build a responsive site for devices of different width

### Day 6: AJAX requests and responses

#### In this project we finally learn about ajax(asynchronous javascript and xml requests) forget the xml part tho 😆

JS in general handles execution synchronously via callstack ie executing funtions one by one behind the scenes, each function once called is added to execution context of the call stack, but here we're understanding how asynchronous execution of functions work. For now we use the `fetch()` method to fetch data from say a server/api.

*In this project we are trying to implement a search bar capable of sorting results(cities/states) based on our inputs as it searches from the json for the key value pairs based on our search query*

<p align="center"> 
 <img src="https://user-images.githubusercontent.com/67954224/145084707-320c2259-6bf4-4397-9d7a-6c28bc1ec4d4.gif">
</p>

⚠ Functions used in this project:
- `fetch()`: used to fetch data from the server/api
- `filter()`: used to filter results based on the key value pairs
- `push()`: used to push results to the declared array
- `json()`: returns a promise which resolves with the result of parsing the body text as JSON. 
- `replace()`: searches for the required string/regular expression/key to be replaced, once found it replaces it with a new value and return a new string with the replaced value
- `match()`: searches a string for a match against a regular expression, then returns an array consisting of the matched values, returns *null* if no match is found

Uses both EventListeners **change** and **keyup** to display matches on key press

