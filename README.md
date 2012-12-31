
honey-less
==========

在你的less文件中@import "css3.less"就可以随意使用css3 mixin了，so easy！

Example
=======
less:

	@import "../css3.less";
	.test-border-radius {
	    .border-radius(5px);
	}

编译后的css:

	.test-border-radius {
	    -webkit-border-radius: 5px;
	    -moz-border-radius: 5px;
	    border-radius: 5px;
	    -webkit-background-clip: padding-box;
	    -moz-background-clip: padding;
	    background-clip: padding-box;
	}

 
Index
=====

Display:
---------------------------

 * @mixin display-box
 * @mixin box-orient
 * @mixin box-pack
 * @mixin box-align
 * @mixin box-flex
 * @mixin box-sizing
 * @mixin background-size
 * @mixin user-select
 * @mixin appearance
 
Decoration:
---------------------------

 * @mixin border-radius
 * @mixin box-shadow
 * @mixin text-shadow
 * @mixin linear-gradient
 * @mixin radial-gradient 
 
Transformation:
---------------------------

 * @mixin transform
 * @mixin transform-origin
 * @mixin transform-style
 * @mixin perspective
 * @mixin perspective-origin
 * @mixin backface-visibility
 * @mixin matrix
 * @mixin translate
 * @mixin scale
 * @mixin rotate
 * @mixin skew
 
Transition:
---------------------------

 * @mixin transition
 * @mixin transition-property
 * @mixin transition-duration
 * @mixin transition-timing-function
 * @mixin transition-delay
 
Animation
---------------------------
 
 * @mixin animation
 * @mixin animation-name
 * @mixin animation-duration 
 * @mixin animation-timing-function
 * @mixin animation-delay
 * @mixin animation-iteration-count 
 * @mixin animation-direction
 * @mixin animation-play-state
 * @mixin keyframes interface 
 * @mixin keyframes

