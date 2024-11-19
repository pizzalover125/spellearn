# Spellearn

## intro/inspiration

Every year at my school, there is a classroom-wide spelling bee. Personally, I
have had problems actually practicing solo, as there isn't really any
websites or apps that provide an intergrated solution to this problem. That's
why I created Spellearn.

## features

The app is designed to be EXTREMELY simple to use. It features a minimalist UI
with few buttons and popping colors. Here is a breakdown on how to use
each page:

### New Set

After you enter that page, name the set and enter your words. Your words MUST
be seperated by line breaks (1 word/line). After your word entry is complete,
click "Save Words." Below, you are able to delete any sets you have created.
All sets are saved in browser storage, so you don't have to worry about
losing your set!

### Practice

Once you enter the page, you are presented with a list of the sets
you have created. Simply select one set and you'll be entered into the
practice enviroment. Click "Play Word" to listen to the word. Then, enter your
spelling of the word. Next, click "Check" to submit your spelling. Finally, repeat
this a bunch and you'll eventually learn the set.

### Scoring System

Before we discuss the data, we must explore the scoring system. Getting a
spelling right results in gaining a point for that word. Getting the spelling
wrong results in losing a point for that word. If you get a word correct three
times more than you get it wrong, then the word is considered "Mastered." If you
get a word wrong twice more than you get it right, then the word is considered "
Struggling." Anything in between is considered "Learning." In summation, this
is the scoring system.

<=-2 ---> 🔴 Struggling
-1-2 ---> 🟡 Learning
<=3 ----> 🟢 Mastered

### Data

The data page provides a comprehensive report of your learning. First, you
can see your total words, mastered words, overall accuracy, and your
current streak. Then, there is a pie chart detailing mastered words versus
learning words versus struggling words. Next, there is a bar graph
displaying your mastery for each set you've practiced. Finally, there is
a "Word Status" section that displays your learning status for each word.

## technical information

The app was made using vanilla HTML, CSS, and JS. The built-in speechSynthesis API
was used for the Text-to-speech aspect of the project. Another cruical API was
the built-in LocalStorage API, which was used for storing the sets inside
the browser.
