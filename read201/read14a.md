# CSS Transforms, Transtions, and Animations

## Transforms

new ways to position and alter elements, the transform property comes in two different settings,
2D and 3D.

### 2D transforms

* 2D rotate (provides the apility to rotate an element from 0 to 360 degrees).
* 2D scale (allow you to change the appeared size of an element. the default scale value is 1,
therefore any value between 0.99 and 0.01 makes an element appear smaller while any value greater
than or equal to 1.01 makes an element appear larger).
**scale x
**scale y

*2D traslate (works a bit like that of relative positioning , pushing and pulling an element in
different directions without interrupting the normal flow of the document).
**translate x
**translate y

* 2D skew(used to distort elements on the horizontal axis,vertical axis, or both).
**skew x
** skew y

* combining transforms ( for multi transforms to be used at once).
* transorms origin (to change the default origin position,can accept one or two values).

* perspective (can be set in two different ways . one way includes using the perspective value
within the transform property on individual elements, while the other includes using the prspective
property on the parent element residing over child elements being transformed).

* perspective origin ( the same values used for the transform-origin property may also be used with
the perspective-origin property, and maintain the same relationship to the element.the large difference
between the two falls where the origin of a transform, while the origin of a prespective identifies the
coordinates of the vanishing point of a transform).

***

### 3D transforms

* 3D rotate (x,y,z)
* 3D scale (x,y,z)
* 3D translate (x,y,z)
* 3D skew (x,y,z)

***

## Transtitions

to take place, an element must have a change in state , and different styles must be identified for
each state. th easiest way for determining styles for different states is by using the :hoover,
:focus, :active , and :target pseudo-classes.

### there are 4 transtion related properties in total

1. transtion-property
2. transtion-duration
3. transtion-timing-function
4. transtion-delay

***

## Animations

building out visual interactions from one state to another.

* animations keyframes.
* animations name.
* animations duration, timing function, and delay.

## Customizing animations

* animations iteration
* animations direction includes:

1. normal.
2. reverse.
3. alternate
4. alternate-reverse.

* animations play state.
* animations fill mode:

1. none.
2. forwards.
3. backwards.
4. both.
