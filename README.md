# JesterBox
Pure CSS image-displaying solution. No calculating to keep image's ratio (it works standalone).

You can learn some tricks from that, if you are beginner/medium in CSS.

Example: http://schizohatter.tk/stuff/jesterbox/JesterBox.html

## Basic information
* Author: Schizohatter/Soanvig (http://schizohatter.tk)
* Year: 2015

## Compatibility
* Confirmed browser compatibility:
	* IE 11,
	* Firefox,
	* Chrome.
* Compatibility additional information:
	* No vendor prefixes used;
	* To get animations work, browser has to support transitions;
	* To get vertical centering work, browser has to support flex model (with basic flex syntax as described in MDN).

(Yes. I don't care much about IE. Microsoft should follow the world, not make their own path)

## Usage
To use that "script", you have to know basic CSS usage.
CSS is in JesterBox.html file. You can find there example usage too (description in html comment).

Eventually you can add "previous/next" buttons if you know CSS. Those should be applied to `.JesterBox div` element to be displayed.
However there is a problem: every image needs its own prev/next links, because they should link to previous/next element's
id parameter. While it's not a problem for backend to generate such a links, it will be *a lot* of HTML. It can be easier to achieve with JS. Note, that because of that, I am not calling JesterBox a "gallery", because prev/next functionality is a basic concept of gallery script.
But: You can wrap JS around that, and even with JS disabled - it is going to work properly :)
