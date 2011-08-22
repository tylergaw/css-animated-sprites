# CSS Animated Sprites
Animating sprite sheets using CSS keyframe animations. It's kinda dumb.

Look at it: [http://lab.tylergaw.com/css-animated-sprites](http://lab.tylergaw.com/css-animated-sprites)

## What is going on?
Each example is a single image that contains "frames" of each step in the animation. CSS keyframes are then created to change the background position to advance to the next frame. By creating very fast keyframes like "5.0001" the tween from one frame to the next is not seen.
The named animations are then applied to the elements and told to repeat infinitely. The speed of the animation is controlled by the duration property. `-webkit-animation: horse 0.8s infinite;`

## Why did I do this?
I was on Reddit in bed at about 1:30am. I saw this [http://www.reddit.com/r/programming/comments/jns94/spinjs_a_pure_js_spinner/c2dojw9](comment), thought, "I think I could do that with CSS".
Hopped out of bed, found this [http://stackoverflow.com/questions/4503195/css3-sprite-animation-without-tweening](http://stackoverflow.com/questions/4503195/css3-sprite-animation-without-tweening).
Then worked till 4:30am making this goofy, goofy thing just for fun. 

## Is it practical?
No

## Could this be used in a more practical way?
I think so, I haven't thought of anything yet, but I really think so.

## Can you do some crazy effects with animating background images with CSS?
Yes, you should give it a try.