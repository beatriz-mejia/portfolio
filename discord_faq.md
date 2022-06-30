Rich Presence FAQ (Frequently Asked Questions)

Here you'll find answers to some common questions about integrating Rich Presence with your game. If you don't see your question answered here, feel free to reach out to gamedevs@discord.com for more help.

Q1. Why can I see "Playing MyGame" yet no Rich Presence data?

There's a couple things that could be going on. Make sure you follow the following: 

1- If you're running two instances of the Discord client, check both!

2- Double check that your Discord_Initialize() function is correct.

3- Throughout development, make sure you have your errored() and disconnected() callbacks hooked up for debugging. You can open up the console in Discord and look for errors pertaining to SET_ACTIVITY for more information as well.

Q2. Why are the Spectate buttons not visible on my profile?

We require your integration to go through an approval process. If you have applied and have been approved and still don't see the buttons, check your Discord console for errors. If you haven't, go to ...
