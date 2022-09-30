# Club Fair Attention Monopoly

I built this app (inspired by [@lachlanjc](https://github.com/lachlanjc)'s own [schacks-demo](https://glitch.com/edit/#!/schacks-demo)) to advertise my [Hack Club](https://hackclub.com) at our schools' club fair, where all the incoming freshman come to sign up for clubs. My goal was simple: attract as much attention as humanly possible. That is what I did.

It's a website that has a phone number on the screen, and when someone texts that phone number a color,song combination, such as Red,Hotel California, the screen changes to that color and plays that song. It has a queueing system to make sure that every color/song texted gets shown on the screen & there's a live feed in the top left hand corner.

If you'd like to use this yourself, here are the steps:

- Make a Twilio account
- Load it with credit and purchase a phone number
- Host this code somewhere (heroku, Glitch, repl.it, your own server)
- Add enviormental secret called key with YouTube Data API key
- Setup a webhook with Twilio to /twcolor
- Open the site
- PROFIT!

![Image of students at our booth at the club fair](club-fair-1.png)

![Another image of students at our booth at the club fair](club-fair-2.png)