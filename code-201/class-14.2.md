# Transforms
#### With CSS3 came new ways to position and alter elements. Now general layout techniques can be revisited with alternative ways to size, position, and change elements. All of these new techniques are made possible by the transform property. The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.

## Transform Syntax
```  
div {
  -webkit-transform: scale(1.5);
     -moz-transform: scale(1.5);
       -o-transform: scale(1.5);
          transform: scale(1.5);
}
```
## 2D Transforms
#### Elements may be distorted, or transformed, on both a two-dimensional plane or a three-dimensional plane. Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes. Three-dimensional transforms work on both the x and y axes, as well as the z axis. These three-dimensional transforms help define not only the length and width of an element, but also the depth.

## 3D Transforms
#### Working with two-dimensional transforms we are able to alter elements on the horizontal and vertical axes, however there is another axis along which we can transform elements. Using three-dimensional transforms we can change elements on the z axis, giving us control of depth as well as length and width.

## Transform Style
#### On occasion three-dimensional transforms will be applied on an element that is nested within a parent element which is also being transformed. In this event, the nested, transformed elements will not appear in their own three-dimensional space. To allow nested elements to transform in their own three-dimensional plane use the transform-style property with the preserve-3d value. The transform-style property needs to be placed on the parent element, above any nested transforms. The preserve-3d value allows the transformed children elements to appear in their own three-dimensional plane while the flat value forces the transformed children elements to lie flat on the two-dimensional plane.
### HTML
```
<div class="rotate three-d">
  <figure class="box">Box 1</figure>
</div>
<div class="rotate">
  <figure class="box">Box 2</figure>
</div>
```
### CSS 
```
.rotate {
  transform: perspective(200px) rotateY(45deg);
}
.three-d {
  transform-style: preserve-3d;
}
.box {
  transform: rotateX(15deg) translateZ(20px);
  transform-origin: 0 0;
}
```
## Backface Visibility
#### When working with three-dimensional transforms, elements will occasionally be transformed in a way that causes them to face away from the screen. This may be caused by setting the rotateY(180deg) value for example. By default these elements are shown from the back. So if you prefer not to see these elements at all, set the backface-visibility property to hidden, and you will hide the element whenever it is facing away from the screen.

# Transitions
#### With CSS3 transitions you have the potential to alter the appearance and behavior of an element whenever a state change occurs, such as when it is hovered over, focused on, active, or targeted.
### There are four transition related properties in total
1. transition-property
2. transition-duration
3. transition-timing-function
4. transition-delay

### Example
``` 
.box {
  background: #2db34a;
  transition-property: background;
  transition-duration: 1s;
  transition-timing-function: linear;
}
.box:hover {
  background: #ff7b29;
}
```
### To learn more about transition, visit [Transitions](https://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users)

# Animations
#### Animations within CSS3 allow the appearance and behavior of an element to be altered in multiple keyframes. Transitions provide a change from one state to another, while animations can set multiple points of transition upon different keyframes.

## Animations Keyframes
```
@keyframes slide {
  0% {
    left: 0;
    top: 0;
  }
  50% {
    left: 244px;
    top: 100px;
  }
  100% {
    left: 488px;
    top: 0;
  }
}
```
#### The animation above is named slide, stated directly after the opening @keyframes rule. The different keyframe breakpoints are set using percentages, starting at 0% and working to 100% with an intermediate breakpoint at 50%. The keywords from and to could be used in place of 0% and 100% if wished. Additional breakpoints, besides 50%, may also be stated. The element properties to be animated are listed inside each of the breakpoints, left and top in the example above.

#### It is important to note, as with transitions only individual properties may be animated. Consider how you might move an element from top to bottom for example. Trying to animate from top: 0; to bottom: 0; will not work, because animations can only apply a transition within a single property, not from one property to another. In this case, the element will need to be animated from top: 0; to top: 100%;.

