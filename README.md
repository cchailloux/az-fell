This is a website project for the A. Z. Fell & Co bookshop from the TV show "Good Omens". This will display whether this fictional shop in Soho, London is currently opened or not (most likely not).

All the videos are clips from the TV show "Good Omens" owned by the Amazon Original & BBC Studios. I do not own those videos.

# Getting started
This is a simple HTML project so far, so simply open the `index.html` file in your favorite browser.
To see it live, go to the url defined in `CNAME`.

# Text excerpt
In the TV show, the bookshop displays a sign that reads as follow:

"I open the shop on most weekdays about 9:30 or perhaps 10am.
While occasionally I open the shop as early as 8, I have been known not to open until 1, except on Tuesday.
I tend to close about 3:30pm, or earlier if something needs tending to.
However, I might occasionally keep the shop open until 8 or 9 at night, you never know when you might need some light reading.
On days that I am not in, the shop will remain closed.
On weekends, I will open the shop during normal hours unless I am elsewhere.
Bank holidays will be treated in the usual fashion, with early closing on Wednesdays, or sometimes Fridays.
(For Sundays see Tuesdays)."


# Project advancement

## Core project is done
Most of it is already done !
Aka the Good Omens-related work:
- isolate small videos clips from the show with the bookstore
- translate the excerpt and its specific words ("occasionally", "perhaps", etc.) into probability
- code the logic determinin for today if the shop is a) open at all b) opening at what time c) closing at what time
- prepare small messages for those scenarii based on books and dialog from the show

And the web development work:
- display and resize video in the background
- book the domain name and link it through Github pages

## Ideas for improvement

### For content
- handle probabilities for bank holidays
- longer video montage with more clips from within the store
- (maybe) transform in a 2-step process : display still photo with text and button, if user clicks then play video / message

### Web-wise
Web development
- it was fun to do a simple, vanilla html, single-file project - but for future iterations, splitting the styling / logic / components would be better and ease testing
- decide the various lucks server-side so everybody has the same experience
- (unclear) how to improve accessibility ? The videos are silent so there's no transcript per se to link to, so for now I simply wrapped the video in a descriptive div 

# Tools and Licence

This work is under the licence under a [Creative Commons Attribution 4.0 International License][cc-by].

Some articles that are interesting:

- HTML: https://www.w3schools.com/howto/tryit.asp?filename=tryhow_css_fullscreen_video
- HTML: https://dev.to/peboy/how-to-create-a-responsive-video-background-in-html-and-css-1bh6

The clips were cut using ffmpeg, a powerful tool to handle video formatting:
- Video: https://ffmpeg.org/
- Video: https://mjimani.medium.com/ffmpeg-commands-for-beginners-720351ce7fb
