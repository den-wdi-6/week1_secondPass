# Week 1 Second Pass

## Diagramming Terms

### Anatomy of a CSS Rule

![](http://dabrook.org/assets/images/uploads/Basic-Anatomy-of-a-CSS-Rule1.png)

### Anatomy of an HTML Element

![](http://dabrook.org/assets/images/uploads/Basic-Anatomy-of-XHTML-Elements.png)

### Anatomy of an HTML Page

![](http://dabrook.org/assets/images/uploads/Basic-Anatomy-of-an-XMTL-Page.png)

### Anatomy of the Box Model

![](http://dabrook.org/assets/images/uploads/Box-Model.png)

### Anatomy of the Document Tree

![](http://dabrook.org/assets/images/uploads/Simple-Document-Tree.png)

### Anatomy of a Function

![](http://2.bp.blogspot.com/-ufCRU4O4_4A/U98qa26fPkI/AAAAAAAAUTM/fd1UOLBnW44/s1600/Screen+Shot+2014-08-03+at+11.38.19+PM.png)

### A JS Object Example

http://www.w3schools.com/js/js_objects.asp

## JS Objects

Which may look like:

```javascript
var car = {
  name: "Fiat",
  start: function() {
    this.state = "On";
    console.log("And we're off!");
  }
  ...
}
```

### Definitions

A **property** is an association between a **key** and a **value**.

`name: "Fiat"`

`key: value`

A **method** is a **property** that is also a **function**.

```
  start: function() {
    this.state = "On";
    console.log("And we're off!");
  }
```

## Variable Hoisting

### A Resource

Check out [this explanation](https://www.w3schools.com/js/js_hoisting.asp) of variable hoisting.

## CSS Positioning

### A General CSS Resource

Check out [this walkthrough](http://adamschwartz.co/magic-of-css/) of major CSS concepts.

### A Floats and Clears Resource

Check out [this article](https://css-tricks.com/all-about-floats/) if you want to know more about floats and clears.

## DOM Manipulation

Try to run through as many of the steps below on your favorite website, using Chrome Developer Tools.

1. Make something disappear
2. Make it reappear
3. Change a background
4. Copy an element somewhere else
5. Add a click listener to something that logs something to the console like "div clicked!"
6. Make the click listener also add an element to the page
