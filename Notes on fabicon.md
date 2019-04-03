Favicon
Victor Vandrup · Lecture 96 · 2 months ago
Hey,

Even though I'm doing the exact same as Brad does related to the favicon, nothing shows up in my title bar except for the title itself and the standard icon (the paper with the folded corner). I have cleared my cache, closed and reopened the window, but nothing shows up.

What to do?

Best regards,

Victor

Brad Traversy
Brad — Instructor · 2 months ago
Everytime this has happens I do a ctrl+f5 on windows and I believe cmd+shift+r on Mac and it refreshes and shows. You added the correct <link> to the head correct? Try it on a different machine as well

CC
Chris · 2 months ago
I had the same issue and the refresh didn't resolve it. My issue was that NewsGrid wasn't the only folder in my file explorer. I simply added it with the rest from the course to make it easier to reference work from the previous sections. This means the href needs to be news-grid/favicon.ico



Visual Studio Code should give you an option to try and follow the href link. If it can't find the file with what you provided, then that's the issue. Obviously you'll have to use whatever you named your folder instead of news-grid if it's different.

VS
Victor Vandrup · 2 months ago
How odd it may sound, this was how it worked for me. I went through the favicon creation process once again, and so I created a new favicon file named "favicon (2).ico", and when I inserted that in stead of the first created, it somehow worked, which I can't explain.

And according to the clear cache shortcut, it's not CTRL + F5, or that's at least not how it is on my machine (I'm running Windows). On mine, CTRL+SHIFT+DEL does the job. If you don't know what the shortcut for clearing the cache inside Chrome on your machine is, simply click the three dots in the top right corner of your Chrome browser, hover over the "More tools" bar, and a submenu should pop up. The third opportunity gives you the opportunity to click it to clear the cache, and there you can also see the shortcut for your machine in the right side in the same bar.

And a little tip I found by accident, but I still found very helpful:

VS Code gives you the opportunity to highlight a repetitive word and edit it by a simple keyboard shortcut. On Windows, the shortcut is CTRL+SHIFT+L, but I don't know what it is on Mac (maybe CMD in stead of CTRL).

Just thought I would share it with you.

I do not hope that you mind me sharing tips and tricks throughout you course, Brad. If so, let me know and I'll stop doing it immediately.

Regards,

Victor

VS
Victor Vandrup · 2 months ago
Chris, if I understand you correctly, Visual Studio Code does give you the opportunity to follow a link. Just like in Word, hover over the link, press CTRL and your cursor will change to a pointer. Then simply left click the link, and it'll take you whereever the link goes :)

MB
Add an answer
Add an answer
