# Newsletter Reskin - Using Homebase (for Plex)
[tylerforesthauser](https://github.com/tylerforesthauser) made this homepage, I really only wanted the newsletter though. Reskinned the newsletter and added part of his stats

Just replace the Newsletter and add the new images

This is for self hosting your own newsletter (not emailing) - aka https://domain.com/newsletter or https://newsletter.domain.com 

Replace the Logo with your own Logo

![Main Image](https://i.imgur.com/cY8Ovl1.jpg)

&#42; In order to use the Recently Added template, you'll have to do a few things:
- Put the `recently_added.html` file into a folder accessible by Tautulli and then enter the path to this file under your Tautulli Settings: `Settings > Notifications & Newsletters > Custom Newsletter Templates Folder` (you'll need to click "Show Advanced" to see this setting)
- You'll then want to enter a publicly accessible folder under "Newsletter Output Directory" (personally, I am just using the /recentlyadded directory since I'm hosting these files on the same server that Tautulli is running)
- Next, add a "Newsletter Agent" and specifically make sure to click "Save HTML File Only" under "Saving & Sending" and it would be advised to enter `index.html` under "HTML File Name"

## Issues:
- The current functions to get the Top Genres and Top Content Ratings currently make as many calls to Plex as there are genres and content ratings, which can be a very large number in many cases. This could certainly be made more efficient.

## License
Licensed under The MIT License. Not affiliated with Plex Inc or Tautulli.
