a roomscale VR scene targeting the [HTC Vive](https://en.wikipedia.org/wiki/HTC_Vive)

in 2D mode, press W to go back and bring the scene into view. for a nicer camera position, checkout [this commit](https://gist.github.com/micahstubbs/201876c23dfe243f6e9a9c0be681367e/47adcf3b99846d309bb3770a516fa917782597f7) commit hash `47adcf3b99846d309bb3770a516fa917782597f7` follow the stackoverflow question [how to reset camera position on enter VR?](http://stackoverflow.com/questions/41624558/how-to-reset-camera-position-on-enter-vr) for a possible method to show a nice custom camera position in 2D mode and a glued-to-the-hmd camera position when in VR

use the front-trigger on either Vive controller to pick up and inspect a block    

block a-boxes positions are closer to the origin than in [previous](http://bl.ocks.org/micahstubbs/a98418db846e7e5560f8b7c8b8224564) [examples](http://bl.ocks.org/micahstubbs/36e3cd39edc43330f2f999372ac7f8ad) so that they are within reach from in roomscale VR. ROADMAP: teleport locomotion ;-)

many thanks to [@bryik_ws](https://twitter.com/bryik_ws), [@utopiah](https://twitter.com/utopiah), [@donrmccurdy](https://twitter.com/donrmccurdy) over at the [A-Frame slack](https://aframevr.slack.com/messages/vive/) for help getting the interaction working.

do get a [slack invite](https://aframevr-slack.herokuapp.com/) of your own and check out the [other places](https://aframe.io/community/) the A-Frame community gathers

---

all the blocks with thumbnail images created during the 2016 [#d3unconf](https://twitter.com/search?q=%23d3unconf&src=typd)

here we use aframe's [`a-boxes`](https://aframe.io/docs/0.2.0/primitives/a-box.html), which are kind of like SVG [`rects`](https://developer.mozilla.org/en-US/docs/Web/SVG/Element/rect) 

a fork of [aframe + d3 + bl.ocks](http://bl.ocks.org/donmccurdy/2d13aa01d854ef60eac24102846a8a5f) from [@donrmccurdy](https://twitter.com/donrmccurdy)

falling blocks brought to you by the [aframe-physics-system](https://github.com/donmccurdy/aframe-physics-system), also from [@donrmccurdy](https://twitter.com/donrmccurdy)

inspired by the conversations at the [3d and VR 11am session](https://docs.google.com/document/d/1pY7OYorubF8GxryOxI6dDtKzTwfGOF8CwXEkQsef8T4/edit) in the Alcatraz Room at the [2016 d3 unconference](http://visfest.com/d3unconf-2016/)