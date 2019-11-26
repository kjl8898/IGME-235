As with Project 1, include a Documentation page (put the link in the comments field of the dropbox, 
as well as an easy to find link in the project site itself) where you document your process, cite any
sources, tell me where to find anything special you want me to see, and also explain how you met the
requirements. Finally, give yourself a grade for the project that you feel fairly represents what its worth.

# Project 2 Documentation

The following is the design philosophy, process, and general workings of project 2.

## Putting Ideas Together

After learning that the Gmail API used OAuth, I had a problem. Fourty-eight hours to find a new API and prove it
could work. I knew I wanted to use a selected API for the challenge, but I didn't know which one. After scrolling through 
one of the many lists of public APIs, I found [fakeJSON](https://fakejson.com/). Designed to create fake user information to 
test a website's ability to handle users, I decided to use it to randomly create fictional characters.

I wanted the user to be able to select different pieces of information they wanted, as well as put in any information they liked. 
Say the user wanted a completely random character with all fields, they can do that. Or if they only want a few fields, and all 
generated characters to have the same name. They can do that too.

## Processing the Process

Once I had proved I could get information from the API, the next step was being able to do something with it. I studied and played 
around with the sample code provided by fakeJSON to figure out how it created and used data sent to it, then how the data was sent back.
This was a bit of a struggle that took a long time for me to figure out. Dynamically assembling an object with different values from multiple,
also dynamic inputs tooks some work. Whenever I got stuck, I shifted my attention to the other parts of the site; information inputs, 
information storage, etc. Although its a huge part of the project as is, I'm very proud of how the site assembles the JSON payload and
returns character sheets.

## Grading Work

Overall, I think I would give myself a solid B. I'm very proud of how the JavaScript came out, but I don't feel the CSS and overall style
is up to par with what I made in Project 1.
