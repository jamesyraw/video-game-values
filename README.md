# video-game-values
A web scraper that pulls resale values for video games and exports to CSV

This uses a few libraries which you will need to make sure are installed first
From there, it pulls data from a specific website of the top 50 most popular games
For specific consoles.

If you wish to change the consoles, you only need to adjust the directory with the py file.

This program then filters out anything with a value less than $10 USD loose,
and then organizes the list by console, then game title.

As a challenge, I added a visualization tool, that displays the average cost by console. 
This doesn't really provide much useful information, it was more proof of concept.

I'm trying to make a little side hustle by buying and reselling old video games,
So this will provide me with the information I need at a moment's notice.
I should note that this feature is included with a premium membership from the
Source website, but only at the $50/mo. tier. So a couple hours of work to 
Code this up to save $50/mo feels pretty cool.

Enjoy!
