# 100 Days Of Code - Log

### Day 1: February 7, 2019

Implemented a javascript function to animate a given DOM element to right by the given distance smoothly. 

[Codepen](https://codepen.io/nluo/pen/WPXWNJ?editors=1111)

Notes:

* It's important to use setTimeout function to send the task out of the main thread i.e. send to EventLoop
* There is a very good talk about the event loop: https://www.youtube.com/watch?v=8aGhZQkoFbQ
* Use javascript to manipulate DOM element style

### Day 2: February 8, 2019

Today I have played around React synthetic event handling and normal DOM event handling, and it turns out the DOM event handling has more priority than the React synthetic event handling!

[Codepen](https://t.co/91DIdQUA6F)
[Twitter](https://twitter.com/nluo933/status/1093840418121216000) 

Notes:

* Looks like DOM event will go to native event handling first then React component event handling (Still need to find out why)