Reviewer: JustWaveThings

Project creator: Yggdrasilly Goose

Project title: Sign-up Form

Repo: https://github.com/JoshBennett793/sign-up-form
Live: https://joshbennett793.github.io/sign-up-form/

Yggdrasilly Goose's Ask: I'd like to know your opinion on understandability of my code. Is it readable? Is it reasonably clear as to what my code does? Things of the sort. As well as your opinion on the overall design. Is it user friendly? Good experience? Try resizing it and see if you can break anything.
My image overlay breaks after zooming in to 140% on firefox. I didn't do password validation. 


How I completed this feedback -- I did the design section first, looking at the page through various resolutions and testing it's functionality / usability / aesthetics, and if needed inspect a specific item, but I don't dig into the code until I'm done with the design feedback. 

## Design ##

Praises:

* I really like when the site is sized less than 760px wide how the left container jumps up top! The page looks great on mobile (chrome dev tools simulated iPhone 12 pro and iPhone SE) 
* Great use of that teal color through the page - I liked how it was used as the correct color when the form items were in focus. I see how you made a choice to alter the link color so it would be readable on both light and dark background. Also the teal color had to be sampled from the water in the image and that really ties the page together.
* Clicking on an input label selects the input. Improves usability!
* I really like your :focus psuedo-class css styling. I am stealing it. No question where that cursor is!
* Great job labeling the inputs so that Chrome could easily autofill the form for me.
* Perfect execution on the odin image / transparent div, as well as getting Roboto on the hero text. I feel the image, font, padding all are proportional. Great job!
* Wait... You used sticky positioning on the hero div? Nice! ( I got the behavior when I was in desktop 725x962 - haven't looked at the code yet)

Critiques:

* Visually, I would have liked to see a bit more use of padding / margin / box shadowing usage / different font sizes to separate and differentiate the 3 sections of the right side of the page when viewed at normal desktop resolutions. I think it would have helped in the mobile layout as well. It would have broken up the content some and given a bit more visual interest to the page.
* When the page is wider than 1200px, the phone number field unwraps to the top row. I would have wanted it to stay wrapped in either a 1x6, 2x3, or 3x2 layout
* "unsplash" link is hard to read against the rocks in the image. I would suggest making the link text white to fix that.
* Something like * in the form labels to let me know which the fields are required before I submit (or even attempt to fill out the form for those privacy focused people).


Questions:

* Did you design this page with a 'mobile-first mentality' like a previous exercise mentioned?
* How did you get that color from the image? 
* in the mobile view (less than 768px wide), was it intentional to center everything except the form element labels?

Additional comments:


## Code ##

Praises:

* Love your github repo README.md! 
* Great job using the <em> tag instead of just styling 'now' and 'know' with css.
* You wanted to know if your code was readable, easy to read, understand what is. You scored 100% on the HTML portion for these factors. Things are in the right place and you keep attributes consistent across elements.  That improves the maintainability. I reviewed the code in chrome dev tools and github. If you aren't crazy about hitting return after each attribute of the <input> element, you don't have to. Your code is readable with just a space between them.
*Extra credit for the @media queries!



Critiques:

* Not a real critique, since it's only two comments in the html, but I've read in the TOP content and from the Discord, when leaving comments; try to comment 'why' something, not 'what' something. I find I don't take the time to comment much because If I want to comment what something is, and if it's not obvious, I need to name it better or restructure it better. In this case, they might have just been placeholders you had at beginning you didn't take out. 
* Your class names are functional, and again, not a real critique because this falls more into preference, but classes like  sec-1, sec-2, sec-3 could be more descriptive. I prefer relational names like "top", "middle", and "Bottom" if I know that's how they are going to be sorted. Again, more of a personal preference, but might save others reading or maintaining your code.
* Seem to be missing <legend> element. I could be wrong about this, but I think it's standard to include that in forms as it helps screen-readers. I styled mine with display: none; css, so that a screenreader would read off the title, but I didn't have to worry about styling the ugly thing.

Questions:

* In your css, why did you choose to use standard fonts for the <form> element instead of Roboto? 
* Your css indentation is a bit wacky. What editor do you use? If VScode, you can highlight the lines that aren't in the right place  and using cmd(or win) + [ or cmd + ] will indent or remove indent of a line. I think having the indentation all lined up helps with readability.  Also if you use VScode -- there's an extension called prettier that will format the code for you. you can select the whole style sheet, right click, and format document, and it will enforce correct indentation(99% of the time).

Additional comments:

## Overall ##

Summary of review (a few sentences about your overall impression):  I believe your project displays a solid understanding of what TOP is teaching us at this level of the course. You have a stronger grasp of responsive design than I do. The project meets the requirements set out, and goes a bit above with the responsiveness. To your question of readability the only thing impacting how I feel about that is your indentation in the css attributes -- and that is an easy fix! The attention to detail in matching the image to the color elements was a nice touch as well as going back and presenting the project well on the repo's main page. Great Job! 
