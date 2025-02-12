# Opening the site
- Using the preview option on VSCode, you can copy the link from the preview into a browser to view the site at full size


# answers
- The Color contrast was originally 4.08:1. This is too low. Changing it to a light green or white fixes the issue

- Keyboard navigation works correctly for me on Opera and edge with most aspects to start off with. After some edits, it automatically jumped to the audio player which isnt ideal however.

- The HTML was updated to remove all ```<br>``` tags and replace them with ```<p>``` tags. The Font tags were also replaced with different header sizes

- The nav needs updated to the ```<nav>``` element, which means the css also needs updated. I replaced the div
element css with the "nav" element to keep the appearance

- Images can be made accessible via the "alt" descriptor

- For the audio, a alternate link is given for old browsers, and a transcript is given for hearing impaired users. 

- The comment show/hide box was harder to figure out (namely because I kept messing up the JS and it wouldnt open at all). But changing up the JS a tiny bit to read the use of a button tag worked.

- A table caption and col/row labels

- The font was originally quite hard to read (its thin lettering lowered contrast even on black and white). Swapping to a thicker font helped

- Forcing the tab controls to start at the first button of the nav with ```tabindex="0"``` so the site doesnt default to the audio player as the tab priority.