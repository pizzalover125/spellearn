# Spellearn
## intro/inspiration
Every year at my school, there is a classroom-wide spelling bee. Personally, I 
have had problems actually practicing solo, as there isn't really any
websites or apps that provide an intergrated solution to this problem. That's
why I created Spellearn. 

## features
The app is designed to be EXTREMELY simple to use. First, head over to the main
page located at TODO. Then, click "New Set." After you enter that page, name the 
set and enter your words. Your words MUST be seperated by line breaks (1 word/line).
After your word entry is complete, click "Save Words." Below, you are able to delete
any sets you have created. Oh yeah, all sets are saved in browser storage! Next,
head back to the starting page. Once you are there, click "Practice." Then,
select the set you just created. Finally, you are able to do all the spelling practice
you may need.

The app is available on web, and is able to be run on Android and iOS, thanks to
Capacitor.js. Check it out at: https://spellearn.netlify.app/

## technical information
The app was made using vanilla HTML, CSS, and JS. The built-in speechSynthesis API
was used for the Text-to-speech aspect of the project. Another cruical API was
the built-in LocalStorage API, which was used for storing the sets inside
the browser.
