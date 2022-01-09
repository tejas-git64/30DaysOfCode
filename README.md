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

_In this project we are trying to implement a search bar capable of sorting results(cities/states) based on our inputs as it searches from the json for the key value pairs based on our search query_

<p align="center"> 
 <img src="https://user-images.githubusercontent.com/67954224/145234442-a00243f5-b2b9-4730-8fcd-f2a3c4426aae.gif">
</p>

⚠ Functions used in this project:

- `fetch()`: used to fetch data from the server/api
- `filter()`: used to filter results based on the key value pairs
- `push()`: used to push results to the declared array
- `json()`: returns a promise which resolves with the result of parsing the body text as JSON.
- `replace()`: searches for the required string/regular expression/key to be replaced, once found it replaces it with a new value and return a new string with the replaced value
- `match()`: searches a string for a match against a regular expression, then returns an array consisting of the matched values, returns _null_ if no match is found

Uses both EventListeners **change** and **keyup** to display matches on key press<br /><br />

### Day 7: **Array Methods-2**

#### Some more array methods to gouge your eyes and mind on

**DNMA - does not mutate the array**<br>
**MA - mutates the array**

Here are the rest of the methods:

- `some()` checks if atleast one of the array elements pass a test and returns a boolean as a result //DNMA
- `every()` checks if all the array elements pass a test and returns a boolean as a result //DNMA
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

### Day 9: **Developer Tools**

#### Insights into handy dev tools and beyond `console.log` 👨‍💻

`Attribute Modification` this dev tool helps in understanding/pinpointing which attribute is modified by javascript

`%c` => `console.log` enables application of css properties in console for debuggable trial<br /> Example: `console.log('%c I am some great text', 'font-size:50px');`

# I am some great text

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

- `console.groupCollapsed()` method creates a new inline collapsed group in the Web Console

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

### Day 10: **JS Checkbox**

#### **Today were gonna build the classic checkbox but with a catch!**

<p align="center"> 
 <img src="https://user-images.githubusercontent.com/67954224/145674620-dfa10b00-f438-425c-9c54-7ac6e691cf9b.gif">
</p>

We're gonna create a checkbox in which we check one checkbox as the starting point and another as the endpoint, once we click the endpoint/last checkbox while holding the `shift` key, we check all the boxes right from the start to the endpoint much like **select all** function in file managers/Gmail

**We've used methods like `forEach()` and `e` along with an eventListener in this project to make IT work** <br />
Don't worry if you did'nt get it, i did'nt get the first time either and there are more ways to do this too!! 👨‍💻 <br /><br />

### Day 11: **Custom HTML5 Video Player**

#### **We're gonna create a custom video player in html5!!**

⚠ We've used a seperate video file here but you can add your own file or from YouTube ▶

This is a basic video player whose properties are tweaked slightly, we use `-webkit-` functions to work cross platform, although every browser gives a slightly different video player

<p align="center"> 
 <img src="https://user-images.githubusercontent.com/67954224/146237346-971a5208-4d07-4d38-a93d-e458826e7763.gif">
</p>

- `-webkit-slider-runnable-track` this default function is used to modify the track/progress line of a video, we can change its width, height and also its color much like how we've done in ours

- `-webkit-slider-thumb` This is the thumb or the circle on the runnable track, using which we can drag the progress of our video, to that specific timestamp
  <br /> <br />

We also use `input` as range sliders to change the volume and playback rate of the video
That's it for today! add your own video file/yt link to it and tweak css your own way!!
<br /><br />

### Day 12: **Key Sequence Detection**

#### Here we'll take a short break and work on some simple array manipulation but we'll use a secret keyword to give a secret message once the array contains all the characters of the keyword!!

PS: The secret keyword used in this project is **Treasure**

we use the `splice()` method to constrict the array length to the length of the secret keyword, just in order to give the secret message on passing the characters of the secret keyword in order......which we do

we also use other methods like:

- `join()` helps to stich individual characters in an array into a single string
- `includes()` gives a boolean value indicating the presence or absence of the word/character passed to validate its presence in a string
- `push()` helps to push/add characters into an array from the right end of the array

Lastly we've used the `keyup` EventListener with the event `e` parameter to pass as a function to return the key pressed on the window, also there's nothing in the window silly 😆, the window is just the body in this case if not declared!!
Cheers ☕☕<br /><br />

### Day 13: **Image on scroll**

#### Here we'll do some on scroll image movement with JS

We use eventListeners to track the scroll on the window to trigger the functions necessary to horizontally make the images appear on the empty padding
We also use CSS's `active` pseudo class to translate it in the X direction and `classList` to add and remove classes from CSS via javascript

<p align="center"> 
 <img src="https://user-images.githubusercontent.com/67954224/146948477-32f3a91e-586b-468d-99f1-b917851d4d8c.gif">
</p>

Methods used:

- `forEach()` calls a function for each element in the array

**Window** properties used:

- `scrollY` property returns the no of pixels for the document that is scrolled vertically
- `innerHeight` property returns the height of a window's content area
- `offsetTop` returns the top position (in pixels) relative to the top of the offsetParent element

### Day 14: **Referencing vs Copying**

#### Here we'll understand how we can create new arrays and objects by reference

By **Referencing** we can directly manipulate the original array/object by index/object-key

For Example let's take the array used in the stater file:

`const players = ['Wes', 'Sarah', 'Ryan', 'Poppy'];`<br />

Now lets say we want to manipulate this array => we manipulate the array using its index!

`players[2] = 'Jake';`

this on `console.log(players)` gives `['Wes', 'Sarah', 'Jake', 'Poppy'];`<br />

but uh oh we've manipulated the original array ┌(。Д。)┐! instead we can reference it to another new variable and **copy** its array elements to the new variable, thereby not changing the original array q(≧▽≦q)

ie let's create a new variable first:

`const newPlayers = players;` // new variable created which points to the original array, but doing this copies the array elements to the new variable

and on `console.log(newPlayers)` we get `['Wes', 'Sarah', 'Jake', 'Poppy'];` <br />
Since previously manipulated the original array therefore the new array also carries the manipulated array

⚠ This is pretty useful especially if we want to use the array multiple times without messing with the original array, this is somewhat like an _undo button_ equivalent to ensure you dont accidentally mess up along the lines while writing long lines of code.<br /><br />

### Day 15: **Local Storage and Event Delegation**

#### Here we are going to create a menu/todo list to representing saving of new information/text submitted by the user to local storage

<p align="center"> 
 <img src="https://user-images.githubusercontent.com/67954224/147834618-8ebe8a6c-0187-493e-bb53-b28c9f9ccd9e.gif">
</p>

**What does it do?**
lemme break it down for you stepwise before jumping in js because there's too many things going behind the scenes🤯

- You type in any food(just basic text) in the form in the box => click the "+add item" button => it creates a list of it

- It stores it in your browser's local storage to reflect it in the browser window even after refreshing it

#### **Stuff that makes it work**

**Functions and other stuff used here:**

- `preventDefault()` prevents the default refreshing state of the browser window ie it let's the values stay which is then populated into local storage
- `addItem()` function adds the food that you type into the local storage using `JSON.stringify()` whenever the event listener hears a 'click' event
- `setItem()` method sets the value of the specified Storage Object item ie in a localStorage
- `populateList()` function uses an empty array names `plates` to stored the entered values, on clicking the `+add item` button this function is called to return the food string value as content to be displayed using the `innerHTML` method

**This completes the entering, storing and displaying of entered value**

**Creating a creative checkbox**
Instead of using the standard checkbox which enables a tick, we've used emojis to do it and on checking it it uses a taco🌮 emoji

- `toggleDone()` Using this function we manipulate the value of **done** which is a **Boolean** from `false` to `true` to change the emoji<br /><br />

### Day 16: **CSS Hover Effects**

#### Let's do some crazy stuff with text by manipulating css `text-shadow` properties using JS

<p align="center"> 
 <img src="https://user-images.githubusercontent.com/67954224/147847489-3a5ce818-12bb-4812-8664-4e74d0624b72.gif">
</p>

Here we've used **walk** as a standard width range, meaning it is used to map the values obtained from the hovered area to a max of **100** ie from a low of **-50** to a high of **50**

Using the following `offset` functions we can manipulate the textShadow of our h1 text to output multiple trippy shadows 😵

- `offsetWidth` property returns the viewable width of an element in pixels, including padding, border and scrollbar, but not the margin
- `offsetHeight` property returns the viewable height of an element in pixels, including padding, border and scrollbar, but not the margin
- `offsetLeft` property returns the left position (in pixels) relative to the left side the offsetParent element
- `offsetTop` property returns the top position (in pixels) relative to the top of the offsetParent element

**mousemove** eventListener is used to output values on mouse hover on the div and h1

### Day 17: **Sorting without articles**

#### Here we are trying to sort an array of **bandnames** without considering the articles **a** , **an** or **the**

<p align="center"> 
 <img src="https://user-images.githubusercontent.com/67954224/147855594-d3faaa92-1e58-4e82-8173-19900334214a.png">
</p>

Here's how we've done it here:

1. Create a function to replace the article
   We do it by using the following method and regular expression:

- `replace()` method searches a string for a value or a regular expression, and returns a new string with the value(s) replaced
- `trim()` method is used to remove any unwanted spaces in the string
  **Regular Expression stuff(enclosed within the replace() method)**
- `/` indicates the beginning of a regular expression
- `^` is an assertion used in regular expressions, it matches the beginning of the input
- `/i` is a flag used to search by ignoring case-sensitiveness
  This completes removing the articles, now onto sorting them =D

2. Sort the **bandnames** alphabetically
   As it says **sort**, we use the array method `sort` which sorts the entire array of **bandnames**
   We pass in an arrow `=>` function to compare the first one to the second and sort them accordingly, where **1** sorts them in ascending order while **-1** does the reverse

- `map()` method creates a map of the sorted **bandnames** and pushes them onto the window as string keys
- `join()` combines them as a whole set of strings, while removing any commas in-between them
  Finally, we display them on the window using the `innerHTML` attribute<br /><br />

### Day 18: **Array Reduce**

#### Here we're going to understand reduce with another example, ie by using video time lengths

First let's know what it does

- `reduce()` method executes a reducer function for array element, and return a single value ie accumulated result, it does not change the original array

Now that we know what it does let's jump right in

We've firstly added all the time-list elements to a new array **timenodes** using the `...` spread operator

Next we're trying to convert all the time lengths into seconds and condense them into a single value to hold the total time in seconds using the `reduce()` method

- `map()` method creates a map of the list as key-value pairs
- `node` function returns the time given in the list
- `timeCode` function uses destructing and splits the time into minutes and seconds by using the `split` method
  Now we multiply the `mins` value times 60 to get the value in seconds, then we add it to the `secs`,then `reduce` condenses all the values gained from mapping into one single value to get the total no of seconds

Now we convert this huge value to hours, minutes and the rest to seconds 🕓

1. We divide the seconds by 3600 to get the value in `hours`
2. We use mod of the `secondsLeft` value to get the rest of the seconds
3. Next we further divide the rest of the seconds by 60 to get the value in minutes
4. Finally we mod the rest of the seconds by 60 to get the rest of last value in seconds

Now that's some good `reduce()` brushup, ain't it? ☜(ﾟヮﾟ ☜)

### Day 19: **Webcam fun with getUserMedia()**

#### Today we are going to work with live audio and video using JS built-in functions

⚠ First let's get familiar with the important stuff that helps us bring out our video feed into our browser📷, the `getVideo()` function which we've used does exactly this

- `navigator` or `window.navigator` object contains information about the visitor's browser
- `mediaDevices` is a read-only property returns a MediaDevices object, which provides access to connected media input devices like cameras and microphones, as well as screen sharing
- `then()` method returns a Promise. It takes up to two arguments: callback functions for the success and failure cases of the Promise
- `play()` method plays the video ie the feed coming from the webcam
  This gives us a small window of our live video feed

#### Now onto our next task ie making the video appear big and allow it to use different filters/effects

This is done using the `paintToCanvas()` function which uses the following JS methods

- `drawImage()` method draws an image, canvas, or video onto the canvas, it can also draw parts of an image, and/or increase/reduce the image size
- `getImageData()` returns an ImageData object representing the pixel data for a specified portion of the canvas
- `putImageData()` method that copies the pixel data for a specified rectangle on a canvas

The **takePhoto()** function is used to play the snapping audio for everytime you want to take a snap of yourself

#### The rest of the functions create the rgb effect on your video

- `redEffect()` function manipulates the pixels to create a red filter to the image
- `rgbSplit()` function extracts the pixels out of the video into individual rgb color schemes to use it for creating custom filters by yourself by messing with the egb sliders
- `greenScreen()` function creates a another filter effect

Playing with filters on JS am i right🤯
That's it with this one, OOOF that was a big one indeed, even if you don't get it now,take your own time and make sure to take note of what each function does in the first place!, remember that this is a functional programming language(～￣ ▽ ￣)～<br /><br />

### Day 20: **Speech Recognition**

#### In this exercise we're going to dabble with speech recognition via JS using Speech recognition APIs

- `SpeechRecognition` interface of the Web Speech API is the controller interface for the recognition service; this also handles the SpeechRecognitionEvent sent from the recognition service(as given in MDNs speech recognition reference

- `new SpeechRecognition()` Creates a new SpeechRecognition object
- `start()` Starts the recognition interface
- `interimResults` property of the SpeechRecognition interface controls whether interim results should be returned (true) or not (false)
- `lang` property of the SpeechRecognition interface returns and sets the language of the current SpeechRecognition. If not specified, this defaults to the HTML lang attribute value, or the user agent's language setting if that isn't set either
  We then add event listeners to the SpeechRecognition interface to then store it into an array of words
- `transcript` read-only property of the SpeechRecognitionResult interface returns a string containing the transcript of the speech recognition session
- `map()` maps the results of the speech recognition
- `join` join the results of the speech recognition into a single string/complete sentence

If the speech recognition API successfully recognizes the speech, it transcribes the result and is appended into a `p` element onto the browser window

There you go!!, now you can create your own voice recognition app, integrate this code into a weather app/ add it as your own little addition to your search related projects!<br /><br />

### Day 21: **Geolocation based Speedometer and Compass**

#### In this project we're gonna look at the compass and speedometer data coming off from our phone into out browser

⚠ Unfortunately it only works well with iOS devices since safari browser has a good integration with iOS devices and also pulling data out from phone/emulator to display into our live server window
ie **speed** and **compass** data

<p align="center"> 
 <img src="https://user-images.githubusercontent.com/67954224/148100409-80f725df-49b0-444c-9fcb-7f964c840b57.png">
</p>

Functions used in this project:

- `navigator` object contains information about the visitor's browser
- `geolocation` property returns a [Geolocation](https://developer.mozilla.org/en-US/docs/Web/API/Geolocation_API) object that can be used to locate the user's position, this property is read-only and is only available in secure contexts - https and only available on user's approval
- `watchPosition()` method is used to register a handler function that will be called automatically each time the position of the device changes(as give in MDNs reference)
  It takes a [GeolocationPosition](https://developer.mozilla.org/en-US/docs/Web/API/GeolocationPosition) object as an input parameter, and can pass additional/optional parameters to the handler like:
  - `success` a callback function that takes a [GeolocationPosition](https://developer.mozilla.org/en-US/docs/Web/API/GeolocationPosition) object as an input parameter
  - `error` parameter gives an optional callback function that takes a [GeolocationPositionError](https://developer.mozilla.org/en-US/docs/Web/API/GeolocationPositionError) object as an input parameter
  - `options` parameter gives an optional object that provides configuration options for the location watch
    [GeolocationCoordinates](https://developer.mozilla.org/en-US/docs/Web/API/GeolocationCoordinates) interface represents the position and altitude of the device on Earth, as well as the accuracy with which these properties are calculated, the following properties of this interface are used:
- `coords` ie **GeolocationCoordinates** for short
- `speed` read-only property is a `double` representing the velocity of the device in meters per second. This value is null if the implementation is not able to measure it.
- `heading` read-only property is a double representing the direction in which the device is traveling. This value, specified in degrees, indicates how far off from heading due north the device is. Zero represents true **North**

Using the above API we gather the compass data from our phone/emulator which we then use it via template literals in our JS to manipulate the svg used with CSS `rotate` function to depict it as a real-time compass<br /><br />

### Day 22: Follow along links

#### Here we're gonna try and get links to be highlighted by on hover with their highlights being the exact size of them

<p align="center"> 
 <img src="https://user-images.githubusercontent.com/67954224/148350946-7c86af1d-87b9-46b3-ba10-c1d680daab15.gif">
</p>

⚠ How it works: <br />
We're gonna add a create a span element on every link we hover to create a hover/active link effect but of exact width while creating a follow through effect instead of just fading away when we move away from the link

**Functions used in this project**:

- `getBoundingClientRect()` method returns a [DOMRect](https://developer.mozilla.org/en-US/docs/Web/API/DOMRect) object providing information about the size of an element and its position relative to the viewport(as given in MDNs reference)
- `linkCoords` variable stores the size of the hovered link, you can view the details of the hovered element in the `console` to understand better
- `coords` is an object that stores the width and height along with the top and left values to determine the position of the links to highlight
- `scrollX` property of the Window interface returns the number of pixels that the document is currently scrolled horizontally, which is used in our `coords.top` object
- `scrollY` The read-only scrollY property of the Window interface returns the number of pixels that the document is currently scrolled vertically, which is used in our `coords.left` object

Finally we add an `eventListener` for each `a` element that is given a `mouseenter` event, which inturn runs the `highlightLink()` to give us the **width** and **height** values of it

Using these values we can manipulate the width and height values of the `highlight` and then use CSSs `transform: translate()` property to follow whenever there is a click/hover on these links <br /><br />

### Day 23: **Speech-Synthesis**

#### We have yet another speech related project and this one is going to be as interesting as earlier!

**What's it about?**
We're are creating a text-to-speech recognition project using javascript, which readily reads whatever text we type and converse it back to us in different voice-overs(depending on our OS)

Let's understand how it works shall we?

⚠ Stuff used in this project:

`SpeechSynthesisUtterance` is a [WebSpeechAPI](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API) that represents a speech request/speech service, it delivers various speech parameters like language, pitch and volume <br /><br />
_For more info_

- [SpeechSynthesisUtterance from MDN docs](https://developer.mozilla.org/en-US/docs/Web/API/SpeechSynthesisUtterance)
- [Getting Started with Speech Synthesis by Matt West](https://blog.teamtreehouse.com/getting-started-speech-synthesis-api)<br /><br />

#### **Let's get into the flow of doing it !!🚀**

#### **1. Creating a box to input text**

`msg.text` as in `SpeechSynthesisUtterance.text` receives the text that will be synthesized when something is spoken
<br />

#### **2. Listing the available voices**

`populateVoices()` function is created to list out the different voices available to synthesize the text to a desired voice

- `getVoices()` method returns a list of [SpeechSynthesisVoice](https://developer.mozilla.org/en-US/docs/Web/API/SpeechSynthesisVoice) objects representing all the available voices on the current device
- `filter()` method filters the voices to English (en-US/en)
- `includes()` method checks if the list contains an `en` naming at the end of every language to categorize it as English
- `map()` method maps the voices as keys and values and returns them as options to select in the dropdown list
- `join` method joins the voices together as a whole list of voices

This is done to get the voices available in your system to be used for the synthesis, which is then added to your innerHTML **dropdown list** so you can choose a voice of your choice from the available voices
<br />

#### **3. Setting the Selected Voice**

- `setVoice()` function sets the voice of the speech output
- `toggle()` function resets the page with all its contents set to the default values
- `setOption()` function sets the selected option to override the default values
  <br />

The rest are the `eventListeners` that are linked to the buttons and sliders that trigger the above mentioned functions to make it happen!! 🦜
<br />
<br />

### Day 24: **Sticky Navigation**

<br />

<p align="center"> 
 <img src="https://user-images.githubusercontent.com/67954224/148652536-42c02995-9b93-46c0-b4a8-487629ce4c92.gif">
</p>

### Today we'll alternate back to some CSS with sticky navigation

Here we're going to make the **navbar** to fix its position to `fixed` when we almost hit the top of the **navbar** while scrolling down

⚠ Functions used in this project:

- `offsetTop` is a read-only property that returns the distance of the outermost border of the element relative to the inner border of the top of the parent element
- `scrollY` property returns the number of pixels that the document is currently scrolled vertically
- `offsetHeight` property returns the height of an element, including vertical padding and borders, as an integer

On scrolling up top the `fixNav()` function is triggered by the `eventListener` which sets the navbar to `fixed` once the top scrolled pixel value is greater than or equal to the top distance of the **nav** by adding the CSS class `fixed-nav` along with **logo** with a `transition` of 0.5s, which enlarges it's `width` to a max of 500px.
<br /><br />

### Day 25: **Event Capture, Propagation and Bubbling**

#### Here we're going to understand some intriguing concepts in JS

#### **Event Propagation** :

Event propagation determines the no of events that are fired on the browser window, this includes all the events like `Onclick` events and link `a` events

⚠ Some important things to also understand:<br />

- `capture` is a boolean value that tells the registered `listener` that events of this type should be dispatched
- `once` is a boolean value indicating that the listener should be invoked at most once after being added

**You can know more about these and many more event values down:**

- [EventTargetaddEventListener](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener)
- [A simplified explanation of event propagation in JavaScript](https://www.freecodecamp.org/news/a-simplified-explanation-of-event-propagation-in-javascript-f9de7961a06e/)
- [Capture passive and once](https://webreflection.co.uk/blog/2016/04/17/new-dom4-standards)

#### **Phases of event propagation**

<p align="center"> 
 <img src="https://user-images.githubusercontent.com/67954224/148675078-5948ba17-ba05-459c-b2d4-92c72d386fa6.png">
</p>

#### **Event Capture** :

In Event Capture, we propagate/move down the element tree, ie from the parent element to the child/target element
This also gives us the entire tree/body of the element

#### **Bubbling** :

In Bubbling, we propagate/move up the element tree, ie from the child/target element to the parent element
This is the reason why we get the entire tree/body of the element

This completes our understanding of how events do their thing, Whew!
<br /><br />

### Day 26: **Follow up menu like in Stripe** 

#### Today we're going to create an on hover menu which uses the same menu for every link but resizes and changes its contents accordingly
<br /> 

**LETS GOOOO!!**

⚠ Stuff that makes it work:

`handleEnter()` function toggles the CSS class `.trigger-enter` and `.trigger-enter-active` to display the menu on link hover

We also use the `getBoundingClientRect()` method to get the size and position of the element with respect to the viewport

We create two variables namely `dropdownCoords` and `navCoords` to hold size and position values of the **navigation** and the **dropdown**

Next we create an object having multiple methods holding the values acquired by the above two variables 
- `setProperty()` method sets a new value for a property on a CSS style declaration object 
`handleLeave()` function removes the CSS classes set by the `handleEnter()` function

Lastly `eventListeners` are used to listen `mouse` events and trigger the `handleLeave()` and `handleEnter()` functions 

This creates a cool buttery smooth transitioning on hover menu, just satisfying to watch and interact with less clicks o(*￣︶￣*)o