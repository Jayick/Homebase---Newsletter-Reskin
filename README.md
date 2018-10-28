# Newsletter Reskin - Using Homebase (for Plex)
If you run a Plex Media Server that you share with users outside of your home, Homebase is a simple webpage that can easily direct your users to services such as Ombi to request new content and it can present ~~useless~~ useful and ~~boring~~ fun statistics about your media server. As a bonus, there is included a matching template for the Tautulli Newsletter.

![Main Image](https://i.imgur.com/cY8Ovl1.jpg)

&#42; In order to use the Recently Added template, you'll have to do a few things:
- Put the `recently_added.html` file into a folder accessible by Tautulli and then enter the path to this file under your Tautulli Settings: `Settings > Notifications & Newsletters > Custom Newsletter Templates Folder` (you'll need to click "Show Advanced" to see this setting)
- You'll then want to enter a publicly accessible folder under "Newsletter Output Directory" (personally, I am just using the /recentlyadded directory since I'm hosting these files on the same server that Tautulli is running)
- Next, add a "Newsletter Agent" and specifically make sure to click "Save HTML File Only" under "Saving & Sending" and it would be advised to enter `index.html` under "HTML File Name"

## Issues:
- The current functions to get the Top Genres and Top Content Ratings currently make as many calls to Plex as there are genres and content ratings, which can be a very large number in many cases. This could certainly be made more efficient.

## License
Licensed under The MIT License. Not affiliated with Plex Inc or Tautulli.
