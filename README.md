# WorSt - Fail To Outguess The Web

## Introduction:
Everybody is amazed over how diverse the interweb has become. It seems that anything worth mentioning has already been mentioned somewhere. Not to forget the few things not worth mentioning. The big spider Google crawls through the entire muddy mess again and again, and only looong words consisting entirely of consonants are unfamiliar to it.
**Your goal** in my challenge is to think of words that the google webcrawler has rarely encountered so far. You enter three words, e.g. 

*dog*, *cat*, *mouse*

and the app asks google for the number of matches for ANY PAIR among them.

1st pair: *dog+cat*

2nd pair: *cat+mouse*

3rd pair: *dog+mouse*.

If google's answer for a pair is sufficiently **LOW** you'll make the *LO-SCORES-LIST*. Read on for details.

## Usage:
1. Enter a new word.  You must never have used this word before. The app keeps a growing list of your trial words.
1. Repeat Step 1 for the next two words.  Three entry fields for your words are provided.
1. Touch on Go! to get your results.  

You may also view the *LO-SCORE-LIST* by touching the respective button (labelled *LO-SCORES*) for that.

Or try again by touching the other button (labelled *Try Again!*).

## Scoring:
The app takes your three words *a*, *b* and *c* and forms three pairs:  
*a+b*  
*b+c*  
*a+c*  
and for each pair  
1. performs a google search and
1. gets the (approximate) number of results.

Note that the app assumes that every pair of words imaginable exist somewhere on at least one web page. **A search result of "zero" for any pair is not permitted and will restart the game (as if you'd touched the "Try Again!" button)**.

If you've reached a score low enough for the *LO-SCORE-LIST* for one, two or all three pairs the app will  
1. notify you and  
1. enter the winning pair(s) together with the approx. count(s) into the *LO-SCORE-LIST*.

Now your three results are added and divided by three to get your average score. In case your average makes the LOWEST-AVERAGES-LIST your word triple is entered into that list and you get another notification.

You are also notified if your words didn't succeed.  Touch the "*Try Again!*" button to start over.

Regardless of whether you win or lose the app will remember your three entries.

## Title:
Words that google seldom finds together are not related, they are "Word Strangers".
