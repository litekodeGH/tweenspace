# TweenSpace.js

TweenSpace is a Javascript library that tweens object properties producing smooth animations. It is an optimized tweening engine written from square one in pure Javascript with no dependencies. Easily handles multiple properties such as hexadecimal, rgb and rgba colors, numeric css properties, 2d/3d transform as well as affecting one or more objects in a single call.  An efficient implementation of data structures features makes this engine able to manipulate tons of simultaneous tweens, preserving high performance and fluid animations. Suited with powerful algorithms capable of managing tweening conflicts, redundant properties and complex animations among other features.

TweenSpace counts on two core classes, Tween and Timeline. Both responsible of the tween creation, management and sequencing. Tweenspace is an static 'class' that controls global playback, provides methods to create Tweens and Timelines, numerous easing functions and contains the engine loop which handles iterations over Tween and Timeline instances.
