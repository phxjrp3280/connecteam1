## Presentation

Good Morning.  I'm delighted to have the first slot and we'll just jump into this by going to my portfolio page.  

I was unsure about how to overcome a number of things and the easiest way to get everything published and up on the web was to use wordpress.  I'm not as happy with this as I'd like to be which is why I started trying to code this in react yesterday.  I think that I'll be happier with the final result that way but this has the required material.

jimpetersen.jp is the site and we'll just click through the pages.  Again, not everything I might like but I'll get that squared away in the next few days.  The site does have this handy link to the heroku version of my project though so we'll use that to find our way there.  

My project is called ConnecTeam.  This is designed for coaches of youth sports to be able to text their teams about practices, games and special events.  

I used a PERN stack and overall came to a greater appreciation of all the cool stuff node is ready to do for you.

Twilio is the company that makes the api for the texts.  I suppose there are others out there but twilio is the name I knew to start with.  I found the documentation daunting - but I always do.  This is probably my weakest area. reading someone elses supposedly clear instructions about how their api works just kills me.  This was no exception.  It was only after forcing myself to build a server only for twilio that I came to the realization it was entirely unnecessary and that all I had to do was create an anonymous function that called their function.  There, I said it in one sentence... they couldn't do it in 30 pages.  I pray that I'll get used to this.  Also, because twilio charges they are super security concious.  The first time I pushed to GIT I was warned that my keys were visible and they changed them.  Everytime I forget and push up without holding back the .env file they change my credential even though the code is an old code.  I had to go and get a new code before this presentation.

controllers / sms / to show the twilio join

controllers / billing - line 5 to show the reporting table joined

app.js line 146 to show the switch / case

Things I'd add to the application - a table that saves the text sent and check boxes so that a coach could select or deselect a member would be attractive additions.  

The most important thing I learned on the project is to keep at it.  I tell my children to "try" all the time and sometimes I'm as guilty about not trying hard enough as they are. During this class I've started to develop a tolerance for trying when I don't have any clue if what I'm doing will work.
