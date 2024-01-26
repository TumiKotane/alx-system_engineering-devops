Postmortem - Boitumelo Kotane 

https://docs.google.com/document/d/1wkrBTWUU2c576Sa-D25JeWPUFTcDZXCR9XPJB6PtEzE/edit?usp=sharing

Postmortem - Web Stack Debugging

Boitumelo Kotane 

So, there I was, staring at the clock, and it's yelling 1:00 pm like it's the official time for a debugging fiesta. Now, I usually roll into the coding circus around 10:00 am, you know, just to ease into the chaos. Today's main act? Figuring out why the server was playing hard to get.

I've been in the code trenches for a few hours, checking out the genius moves in the Nginx config code and the HTML files. Validation game strong, or so I thought, by 2:00 pm. But nope, the server wasn't feeling the love. Lucky for me, it was just a practice project. Real users would've been stuck in the virtual waiting room forever.

Fast forward to 2:30 pm, and Google was like, "Dude, your problem is so niche, we don't even have memes for it." No love on the forums either. So, with the desperation level cranked up, I hit the Nginx documentation. Boom! In the intro section, it hits me: Start the Nginx program first, then the server does its thing. Well, duh!

This was a classic "RTFM" moment. Spent an hour and a half on a wild goose chase when the real party was in the docs. Lesson learned: Don't skip the manual; it's the secret sauce to avoid unnecessary debugging marathons.

For those sticking around, here's the kicker: My initial blunder? Thinking I was the Nginx whisperer. Newsflash: I'm not. Rule of thumb approach problems like a blind date, set up your project like you're building a pillow fort, and never assume. Servers, like people, need a little warm-up before they join the code party. Cheers to debugging adventures where laughter is the best debugging medicine. Read the docs, folks, it's not just for show! Later, debuggers!

