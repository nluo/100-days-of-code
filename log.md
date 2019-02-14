# 100 Days Of Code - Log

### Day 1: Feb 7, 2019

Implemented a javascript function to animate a given DOM element to right by the given distance smoothly. 

[Codepen](https://codepen.io/nluo/pen/WPXWNJ?editors=1111)

**Notes:**

* It's important to use setTimeout function to send the task out of the main thread i.e. send to EventLoop
* There is a very good talk about the event loop: https://www.youtube.com/watch?v=8aGhZQkoFbQ
* Use javascript to manipulate DOM element style

### Day 2: Feb 8, 2019

Today I have played around React synthetic event handling and normal DOM event handling, and it turns out the DOM event handling has more priority than the React synthetic event handling!

[Codepen](https://t.co/91DIdQUA6F)
[Twitter](https://twitter.com/nluo933/status/1093840418121216000) 

**Notes:**

* Looks like DOM event will go to native event handling first then React component event handling (Still need to find out why)


### Day 3: Feb 9, 2019

Use SVG to implement the angle edge.

[Codepen](https://t.co/x3CGMUJhXV)
[Twitter](https://twitter.com/nluo933/status/1094236078121205761)

**Notes and references:**

* [3 Ways to Create Angled Edges With SVG](https://webdesign.tutsplus.com/tutorials/quick-tip-how-to-create-angled-edges-with-sass--cms-31545)


### Day 4: Feb 10, 2019
Today I have implemented a simple carousel/slider with pure React and CSS (without any other 3rd party libraries than React). Still has some CSS and refactoring to do, will continue on Day 5!

[Codepen](https://t.co/bFMwLx2q8D)

**Notes and references:**

[Simple Swipe with Vanilla JavaScript](https://css-tricks.com/simple-swipe-with-vanilla-javascript/)


### Day 5: Feb 11, 2019
Today I continued on yesterday's simple carousel/slider with pure React and CSS.
Some refactoring, centre the left, right control, made the content of the carousel/slider to be generic, i.e. react.children. 

[Codepen](https://codepen.io/nluo/pen/XOqdjv) 

### Day 6: Feb 12, 2019

Today I continued to improve the simple carousel/slider built with pure React and CSS from day 4 and 5:  added event listener to make it slidable with mouse.

[Codepen](https://codepen.io/nluo/pen/XOqdjv )

### Day 7: Feb 13, 2019

Today I have added the touch support (for usage in mobile devices) in my  simple carousel/slider built with pure React and CSS from day 4 - 6, I have put my source code in my github [simple-react-carousel](https://github.com/nluo/simple-react-carousel)

**Notes and references:**

[Simple Swipe with Vanilla JavaScript](https://css-tricks.com/simple-swipe-with-vanilla-javascript/)

### Day 8: Feb 14, 2019

Log all my previous days into github repo: [100-days-of-code](https://github.com/nluo/100-days-of-code)
