# HTML AND CSS

## Images

the width and hight properties in CSS can be used to adjust the size of an image.since the html and
css code always loads before the files , specifying image size makes pages load faster .telling the
 browser how much room to leave for an image causes the remainder of the website to render without
having to wait for the image to download.

### practical information

any website should be created with the target user in mind,rather than just for you or the site
creator. its a good idea to ask any questions about the types of users who may be involoved in your
pages. in fact ,it is unlikely to be of interest to anyone.and if the platform has a broad appeal,the
 demographics should be considered.

make a list of the reasons why people will visit your website.the imaginary guests you created in the
 previous phase can now be assigned tasks.

note:all this helps in attracting users to the site because of the presence of the media,but you need
to coordinate them well depending on UI/UX design rols .

## video and audio APIs

the content below is an excerpt from the article (reference at the end )

I think we've taught you enough in this article. The HTMLMediaElement API makes a wealth of functionality
 available for creating simple video and audio players.

Here are some suggestions for ways you could enhance the existing example we've built up:

* The time display currently breaks if the video is an hour long or more (well, it won't display
hours; just minutes and seconds). Can you figure out how to change the example to make it display hours?

* Because ```<audio>``` elements have the same HTMLMediaElement functionality available to them, you could
easily get this player to work for an ```<audio>``` element too. Try doing so.

* Can you work out a way to turn the timer inner ```<div>``` element into a true seek bar/scrobbler — i.e., when
 you click somewhere on the bar, it jumps to that relative position in the video playback? As a hint, you
can find out the X and Y values of the element's left/right and top/bottom sides
 via the getBoundingClientRect() method, and you can find the coordinates of a mouse click via the event
object of the click event, called on the Document object.

references:
mozilla.org. (2021).video an audio APIs -learn web development .<https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Video_and_audio_APIs>
(access on 23/04/2021)
