# Read: 14a - CSS Transforms, Transitions, and Animations

**I learned from these Articles:**

* With CSS3 came new ways to position and alter elements. Now general layout techniques can be revisited with
alternative ways to size, position, and change elements. All of these new techniques are made possible by the transform property.

* The actual syntax for the transform property is quite simple, including the transform property followed by the value.
The value specifies the transform type followed by a specific amount inside parentheses.

* Elements may be distorted, or transformed, on both a two-dimensional plane or a three-dimensional plane.

* When working with three-dimensional transforms, elements will occasionally be transformed in a way that causes 
them to face away from the screen. This may be caused by setting the rotateY(180deg) value for example

* It is important to note, as with transitions only individual properties may be animated. Consider how you might
move an element from top to bottom for example. Trying to animate from top: 0; to bottom: 0; will not work, because 
animations can only apply a transition within a single property, not from one property to another. In this case, the 
element will need to be animated from top: 0; to top: 100

* The animation-play-state property allows an animation to be played or paused using the running and paused keyword values
respectively. When you play a paused animation, it will resume running from its current state rather than starting from the
very beginning again.


