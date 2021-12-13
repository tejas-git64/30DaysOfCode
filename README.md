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
- Uses CSS's EventListeners like `change` & `mousemove` to update new values<br /><br />

### **Day 4: Array Methods-1**

### Brushing up some basic yet intriguing array methods
Here we're going to understand the usage of the following methods:
- `sort()` sorts elements in the ascending or descending order
- `split()` spilts an array/object based on the position assigned, used mainly in destructing objects
- `filter()` creates a new array filled with elements that pass a test provided by a function
- `reduce()` executes a reducer function for each value in an array and returns a single value which is the function's accumulated result
- `map()` creates a new array from the results of a previously existing function <br /><br />



### Day 5: **Flexbox Gallery**

### its flexbox time!! one of most important topics in css, especially if you wanna play with images/div elements

### Here we use flexbox to align `p` elements to enlarge and shrink on click and also widen it

<p align="center"> 
 <img src="https://user-images.githubusercontent.com/67954224/145238332-1754a9c5-fbef-4fed-bd62-658ad3331b0a.gif">
</p>

##### These are the main functions used to work with flexbox in this project

- `display: flex` activates flexbox
- `justify-content` aligns the div horizontally
- `align-items` align the div vertically
- `transform` fuction used to create sliding animations of the top and bottom `p` element
- `toggle()` This JS method is used to add and remove the class `open` which enlarges the font size of the middle `p` element
- `includes()` This is another JS methods that returns a boolean value if a string contains a specific character/string 

Flexbox allows seamless wrapping and resizing with the changing width of the page, it can be used along with media queries to build a responsive site for devices of different width<br /><br />

### Day 6: **AJAX requests and responses**

#### In this project we finally learn about ajax(asynchronous javascript and xml requests) forget the xml part tho 😆

JS in general handles execution synchronously via callstack ie executing funtions one by one behind the scenes, each function once called is added to execution context of the call stack, but here we're understanding how asynchronous execution of functions work. For now we use the `fetch()` method to fetch data from say a server/api.

*In this project we are trying to implement a search bar capable of sorting results(cities/states) based on our inputs as it searches from the json for the key value pairs based on our search query*

<p align="center"> 
 <img src="https://user-images.githubusercontent.com/67954224/145234442-a00243f5-b2b9-4730-8fcd-f2a3c4426aae.gif">
</p>

⚠ Functions used in this project:
- `fetch()`: used to fetch data from the server/api
- `filter()`: used to filter results based on the key value pairs
- `push()`: used to push results to the declared array
- `json()`: returns a promise which resolves with the result of parsing the body text as JSON. 
- `replace()`: searches for the required string/regular expression/key to be replaced, once found it replaces it with a new value and return a new string with the replaced value
- `match()`: searches a string for a match against a regular expression, then returns an array consisting of the matched values, returns *null* if no match is found

Uses both EventListeners **change** and **keyup** to display matches on key press<br /><br />


### Day 7: **Array Methods-2**

#### Some more array methods to gouge your eyes and mind on

**DNMA - does not mutate the array**<br>
**MA - mutates the array**

Here are the rest of the methods:
- `some()` checks if atleast one of the array elements pass a test and returns a boolean as a result //DNMA
- `every()` checks if all the array elements pass a test and returns a boolean as a result  //DNMA
- `find()` returns the value of the first element that passes a test, and returns undefined if no such element is found, //DNMA
- `findIndex()` returns the index (position) of the first element that passes a test, returns -1 if no match is found. //DNMA
- `splice()` method adds and/or removes array elements. //MA <br /><br />


### Day 8: **HTML Canvas**

#### Lets dive into html's creative and artistic side 🎨🖌
Here we use HTML's `canvas` tag to draw graphics, on the fly via scripting (usually JavaScript).
<p align="center"> 
 <img src="https://user-images.githubusercontent.com/67954224/145401999-52960d80-eb37-443a-b982-2ddfe2380c97.gif">
</p>

Here the hue of the stroke gradually increases along with its width untill 100 and then resets back to 1, giving a colourful artistic stroke
Functions used in this project:

- `getContext()` method is used to enable drawing on the canvas, `2d` enables the creation of a CanvasRenderingContext2D object representing a two-dimensional rendering context 
- `strokeStyle` property sets or returns the color, gradient, or pattern used for strokes
- `lineJoin` property sets or returns the type of corner created, when two lines meet
- `lineCap` property sets or returns the style of the end caps for a line
- `lineWidth` property sets or returns the current line width, in pixels
- `beginPath()` method begins a path, or resets the current path
- `moveTo()` method moves a window's left and top edge to the specified coordinates
- `lineTo()` method adds a new point and creates a line TO that point FROM the last specified point in the canvas
- `stroke()` method draws the lines and border around the text and shapes, the color object can be set in terms of RGB or HSB depending on the color mode

This project uses all of the **mouse** EventListeners ie `mousemove`, `mousedown`, `mouseup`, `mouseout`<br /><br />


### Day 9: Developer Tools

#### Insights into handy dev tools and beyond `console.log` 👨‍💻

`Attribute Modification` this dev tool helps in understanding/pinpointing which attribute is modified by javascript

`%c` => `console.log` enables application of css properties in console for debuggable trial<br /> Example: `console.log('%c I am some great text', 'font-size:50px');` 
#  I am some great text

`%s` => `console.log` enables passing characters/strings much like in **C** language 😃<br />
Example: `console.log('I am sleepy %s typing all of this code...zZzZZ', '😪');` 
#### I am sleepy 😪 typing all of this code...zZzZZ <br /><br />

**console** functions ⚠:
- `console.warn()` used to give warnings in the console 
  
   ![Screenshot 2021-12-10 190222](https://user-images.githubusercontent.com/67954224/145582732-5513c742-4638-43d1-aa8e-5ca6fa943582.png)

- `console.error()` used to pass errors in the console 

   ![Screenshot 2021-12-10 190956](https://user-images.githubusercontent.com/67954224/145582844-20834d01-e766-477b-a659-95cef7cab1cc.png)

- `console.info()` used to pass statements as an insight/information in the console 

   ![Screenshot 2021-12-10 191434](https://user-images.githubusercontent.com/67954224/145583502-90d617db-facf-4c5c-b22d-01a57dfbc047.png)

- `console.assert()` method tests if a given expression is true or not. If the expression evaluates to 0/false, an assertion failure is being caused, and the program is terminated.

   ![Screenshot 2021-12-10 191657](https://user-images.githubusercontent.com/67954224/145583770-6a20acf6-9093-462d-b924-fd927886f43f.png)

- `console.clear()` used to clear the console 

- `console.log()` can be used give output in the console  
 
  ![Screenshot 2021-12-10 185335](https://user-images.githubusercontent.com/67954224/145580974-c56c9c77-623c-4703-95be-989a793e4e52.png) 
- `console.dir()` displays an interactive list of the properties of the specified javaScript object //element p is clicked on

   ![Screenshot 2021-12-10 192018](https://user-images.githubusercontent.com/67954224/145584139-e87d704c-710d-4937-a64f-095f526942dd.png)

- `console.groupCollapsed()`  method creates a new inline collapsed group in the Web Console

   ![Screenshot 2021-12-10 192400](https://user-images.githubusercontent.com/67954224/145584753-72b3936b-b807-4662-b279-ad79ede2562d.png)
   ![Screenshot 2021-12-10 192429](https://user-images.githubusercontent.com/67954224/145584759-ad6cc087-b659-4be7-8f8b-9cbb48a10b76.png)

- `console.groupEnd()` method indicates the end of a message group
- `console.count()` method keeps the count of words in a message  

   ![Screenshot 2021-12-10 192626](https://user-images.githubusercontent.com/67954224/145585068-bb1bbda6-4796-441d-a82f-1e9202535576.png)

- `console.time()` method starts a timer that you can use to track how long an operation takes

- `console.timeEnd()` stops a timer that was previously started by calling `console.time()`

    ![Screenshot 2021-12-10 192855](https://user-images.githubusercontent.com/67954224/145585389-a2660fd5-555a-465d-8260-283d8c26f423.png)
    
- `console.table()` method displays tabular data as a table, this function takes one mandatory argument data, which must be an array or an object, and one additional optional parameter columns

   ![Screenshot 2021-12-10 193056](https://user-images.githubusercontent.com/67954224/145585643-abb10976-f9de-4ae4-870c-df412946a35e.png)
   
   
### Day 10: JS Checkbox 

#### **Today were gonna build the classic checkbox but with a catch!**

<p align="center"> 
 <img src="https://user-images.githubusercontent.com/67954224/145674620-dfa10b00-f438-425c-9c54-7ac6e691cf9b.gif">
</p>

We're gonna create a checkbox in which we check one checkbox as the starting point and another as the endpoint, once we click the endpoint/last checkbox while holding the `shift` key, we check all the boxes right from the start to the endpoint much like **select all** function in file managers/Gmail

**We've used methods like `forEach()` and `e` along with an eventListener in this project to make IT work** <br />
Don't worry if you don't get it, i did'nt get it the first time either and there are more ways to do this too!! 👨‍💻 
