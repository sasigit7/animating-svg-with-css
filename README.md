# animating-svg-with-css
TeamTreehouse/Tracks/Web Design


::::::::::::::::::::::About this Course:::::::::::::::::::::::
SVG (Scalable Vector Graphics) also supports interactivity and animation, so you can animate and interact with SVG like you're able to do with HTML. This short course covers the most common methods for animating SVG: CSS transitions, transforms, and keyframe animations.
What you'll learn:
1. Transitioning & Transforming SVG
2. Animating SVG with keyframes
3. Animated Line Drawings in SVG

->>>>>>>>>>>>>>>>>>Transitions and Transforms:
Learn how to animate SVG icons, using CSS transitions and transforms.

->Course Overview:
You can animate and interact with SVG just like you're able to do with HTML. SVG supports different methods for animation, but you're going to learn one of the most common methods: using CSS transitions, transforms, and keyframe animations.

->Intro to SVG Animation:
SVG support for interactivity and animation has been around for some time. Long before CSS transitions, transforms and keyframe animations, SVG had other animation capabilities native to the browser that are still supported and used today.
Quick Reference:
1. https://developer.mozilla.org/en-US/docs/Web/SVG/SVG_animation_with_SMIL

JavaScript Animation Libraries:
1. https://greensock.com/gsap
2. http://snapsvg.io/
3. http://velocityjs.org/

Current Browser Support:
While CSS transitions, transforms and animations are supported in IE10 & up, SVG animations are not.
1. https://theblog.adobe.com/the-state-of-svg-animation

->Transitioning SVG Properties:
Icons are a great way to get started with SVG animation because they're perfect for simple interactions like hover states. We'll start by creating a CSS transition that animates icon fill colors on :hover.

Quick Reference:
1. https://developer.mozilla.org/en-US/docs/Web/SVG/Attribute/fill
2. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions
3. https://www.w3.org/TR/SVG/propidx.html

->Fill and Stroke Transitions:
In this video, we'll continue transitioning SVG properties for fills and strokes

->Grouping and Transforming SVG:
Transforming SVG elements with CSS is similar to transforming HTML elements with CSS. You can rotate, scale, skew and translate SVGs using the transform property. In this video, you'll learn how to group SVG shapes and rotate them from a center origin.

Resources:
1. https://developer.mozilla.org/en-US/docs/Web/SVG/Element/g
2. https://developer.mozilla.org/en-US/docs/Web/SVG/Element
3. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Transforms/Using_CSS_transforms
4. https://developer.mozilla.org/en-US/docs/Web/CSS/transform-origin

->Rotating and Scaling SVG:
In this video, you'll create the rotation and scale transforms for the hammer and heart SVG icons.

Resources:
1. https://codepen.io/sasigit7/pen/XqzNOr

->Transform Origin in Firefox:
Browser support is generally excellent for SVG animations with CSS. However, there is an issue in Firefox with transform-origin and percentage values. You'll commonly see this referred to as the "transform origin bug" in Firefox.

Resources:
1. https://bugzilla.mozilla.org/show_bug.cgi?id=891074
2. https://developer.mozilla.org/en-US/docs/Web/SVG/Attribute/cx
3. https://developer.mozilla.org/en-US/docs/Web/SVG/Attribute/cy
4. https://developer.mozilla.org/en-US/docs/Web/CSS/transform-origin

->>>>>>>>>>>>>>>>>>>>Keyframe and Line Drawing Animations:
Learn how to create an SVG animation sequence, using CSS @keyframes rules and animation properties. You will also learn the concept behind SVG line animation.

->Creating an SVG Animation Sequence:
You can create fun and engaging animation sequences with SVG and CSS keyframe animations. In this video, you will create a simple badge animation using SVG, CSS keyframe rules, and animation properties.

Resources:
1. https://developer.mozilla.org/en-US/docs/Web/CSS/@keyframes
2. https://developer.mozilla.org/en-US/docs/Web/CSS/animation
3. https://developer.mozilla.org/en-US/docs/Web/CSS/animation-fill-mode
4. https://developer.mozilla.org/en-US/docs/Web/CSS/animation-timing-function

->Finishing the Animation Sequence:
In this video, you will complete the badge animation by creating the star animation keyframes.

->Creating an Animated Line Drawing:
Using SVG stroke properties and CSS, you can create an animation that moves a stroke along its path. The animation makes it look like the stroke is drawing itself. Once you understand how SVG line animation works, creating your own animated line drawing will be simple.

Resources:
1. https://developer.mozilla.org/en-US/docs/Web/SVG/Attribute/stroke-dasharray
2. https://developer.mozilla.org/en-US/docs/Web/SVG/Attribute/stroke-dashoffset

Animated Line Drawing Examples:
1. https://codepen.io/sasigit7/pen/erevVy
2. https://codepen.io/sasigit7/pen/XqzMZE
3. https://www.polygon.com/a/ps4-review

->Animating stroke-dasharray and stroke-dashoffset:
In this video, you will learn how to use the stroke-dasharray and stroke-dashoffset properties to create line animations.

Getting a path's total length using JavaScript:

For example:

var path = document.querySelector('.logo');
var length = path.getTotalLength();

Resources:
1. https://jakearchibald.com/2013/animated-line-drawing-svg/

->The Animation Challenge:
We've covered a lot of material so far, and you're ready to start creating SVG animations with CSS on your own. In this animation challenge, you will create an SVG animation sequence using CSS transforms, keyframes, and animation properties.

->The Animation Challenge Solution:
This animation challenge is a great way to practice what you've learned so far. In this video, I'm going to show you my solution to the challenge.

Resources: 
1. http://blog.teamtreehouse.com/increase-your-sites-performance-with-hardware-accelerated-css
2. https://davidwalsh.name/translate3d

































