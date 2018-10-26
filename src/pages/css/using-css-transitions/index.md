---
title: Using CSS Transitions
---
## Using CSS Transitions

CSS transitions provide a way to control animation speed when changing CSS properties. Instead of having property changes take effect immediately, you can cause the changes in a property to take place over a period of time. For example, if you change the color of an element from white to black, usually the change is instantaneous. With CSS transitions enabled, changes occur at time intervals that follow an acceleration curve, all of which can be customized..

### How to use transitions

Here is an example of how a transition would be used to change the values. 

```.example {
    transition: [transition-property] [transition-duration] [transition-timing-function] [transition-delay];
}
```
In the example below, the div is being given the background color of red which is the transition property, the duration of the transition `.05s` and the timing function which is `ease`

Also we've made it so each time we hover over the div it will transition to green.

```
div {
  transition: background-color 0.5s ease;
  background-color: red;
}
div:hover {
  background-color: green;
}
```

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->

#### More Information:
<!-- Please add any articles you think might be helpful to read before writing the article -->
[w3schools](https://www.w3schools.com/css/css3_transitions.asp)

[css-tricks](https://css-tricks.com/almanac/properties/t/transition/)

[MDN | CSS transitions](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions)


