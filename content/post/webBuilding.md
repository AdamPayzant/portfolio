---
title: Building This Site
description: The process of me developing this website.
date: "2020-12-23T22:36:47-05:00"
publishDate: "2020-12-23T22:36:47-05:00"
---

Let's go through how I built my webpage into it's initial final version.

---

To be up-front, I'm not a huge fan of doing anything front-end based. I don't have anything against the work, but I have absolutely no eye for what looks good. After putting off building this site for far longer than I should, experimenting with various web technologies trying to find something I like. I started looking into buzz-wordy frameworks like React, Vue, and the like, but I found them completely overkill and too resource intensive for what I'm trying to do. To that end I settled on Hugo.

Hugo is great for what I needed. Nice looking themes are plentiful (so I don't have to worry as much about making things look pretty) and it doesn't have significant resource overhead that bug me about a lot of other options I looked at. After going through a few themes, I decided on the [Personal Web Theme](https://themes.gohugo.io/personal-web/). Out of the ones that I looked at, this was the one I personally thought looked the best while having an easy to modify sample website (I am still new to Hugo after all). With this theme, a lot of it has been pretty plug a play, just modifying the config file, adding directories, and writing the markdown. In addition, a big reason I chose this specific theme is it pretty closely followed Hugo standards, and required very little tweaking to get working. One thing that kinda bugged me when I was looking into using Hugo was a lot of the guides recommended effectively gutting the theme into the root folders. That seems to be the most reliable way to use a theme as some seemingly don't play nice while staying in the themes folder (though once again that may be a user error not an issue with the theme itself). I don't know about you, but the way most were recommending doing felt like I was trying to hide the fact I was using someone else's theme and just didn't sit right.

That all said I do still have a couple of things I want to change once I have this finalized and what to dig in to truly make it my own. A few things of note:

* Add a high contrast option. While I'm keeping the sidebar image darker to make it easier on the eyes, the main content is still black text on a white background which is something I'm not a huge fan of.
* Improve mobile experience. Since I'm writing this before my website actually goes live, I don't know how the mobile experience is. Considering the theme doesn't mention, I'm skeptical, but this is something I need to evaluate. I'm still leaving this as something I want to do because no matter how decent a template is, there's always a few changes to make it at least more to my taste, if not outright better.
* The sidebar currently scales kinda weird. It really doesn't like short screens, so I'll probably want to add various resolution profiles for it
* This is more a limitation of static sites in general, but I have a few projects in the pipeline that don't really work without a more comprehensive backend serving them.