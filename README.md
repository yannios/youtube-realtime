# YouTube Realtime

This is a simple experiment which shows the current live subscriber count on YouTube for a user. The count displayed on YouTube is often incorrect because it doesn't update in realtime. The count used on this experiment is taken directly from the API and hence is guaranteed to be accurate.

The design follows Material Guidelines by Google, although could be mildly displaced since no libraries were used for the same. The page is only 20KB in size, including all resources used. This page is super light and the follow up network requests are as minimal as possible.

You can directly bookmark the relevant page to directly jump to a specific user, and while sharing you can also use youtuberealtime.ga/<username or channel ID>

![YouTube Realtime Screenshot](http://i.imgur.com/B317Q5e.png)

Feel free to submit issues/pull request if you'd like to contribute. No javascript or theming libraries were used (except Odometer for smooth digit animations) and I prefer not to, please keep this in mind while submitting a pull request.

I've been seeing a lot of copies of this project on the internet, please consider adding an attribution link if you are planning to deploy this project on your website. If you are a YouTuber, consider using a direct link for your channel instead of creating a new clone website. Thanks!

# Try it yourself!

* [Sky Does Minecraft](https://akshatmittal.github.io/youtube-realtime/#!/SkyDoesMinecraft "Sky Does Minecraft's YouTube Subscriber Count")
* [PewDiePie](https://akshatmittal.github.io/youtube-realtime/#!/PewDiePie "PewDiePie's YouTube Subscriber Count")
* [Smosh](https://akshatmittal.github.io/youtube-realtime/#!/Smosh "Smosh's YouTube Subscriber Count")
* [Marques Brownlee](https://akshatmittal.github.io/youtube-realtime/#!/MarquesBrownlee "Marques Brownlee's YouTube Subscriber Count")

# Todo

1. Mobile View (Kinda implemented)
2. Embeds
3. ~~Support for Channels~~
4. *Anything else?*

# License

YouTube Realtime Copyright (C) 2015 [Akshat Mittal](http://akshatmittal.com/)

Please see LICENSE.md file in the same directory.
