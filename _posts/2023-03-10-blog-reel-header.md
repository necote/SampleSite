---
layout: post
title:  "A Post About Changing the Header Above the Blog Reel"
date:   2023-03-12 12:40:19 -0500
categories: workshop
---

**Note**: this blog post teaches a specific concept. Looking for a basic sample post? Try [this one]({% post_url 2023-03-10-workshop-announcement %}).

With Jekyll the theme templates make things easy! But, they can cause a bit of confusion. For example, while it's great that our files for our site are not too overwhelming, Jekyll obscures some features that make the site--as established by the theme's defaults. And, the defaults are changeable.

We cannot go over how to customize everything! But, a very simple edit you might want to make to your site is to change the name of the blog post listing on the homepage from "Posts" (the default) to something else. For the sake of this exercise, I just changed it to "Some Blog Posts"

How to change the blog reel header:
- When looking for help, the first place I look is the `README.md` file in the Minima theme [repo](https://github.com/jekyll/minima). While the general README that shows up on the front page provides some information, I would recommend you also read the `README.md` for whatever of Minima version you have.
  - To figure out what version of Minima you have: FYI I have 2.5 and so that is likely your version as well. But, you can always check by running in the Command Line: `bundle show minima`  
- Next, go the branch dropdown (it'll be set to "master"), and change it your version. 
  - So, if you have the 2.5 version of Minima like I do, choose "2.5-stable" 
  - I recommend reading the relevant `README.md` entirely--there is a lot of useful information! 
- You will see that they [explain](https://github.com/jekyll/minima/tree/2.5-stable#post-listing) that you can change the post listing (aka blog reel) header by "defining a `list_title` variable in the document's front matter." But what does that mean???
- Your homepage's page file is the `index.md`--that is our "document." The "front matter" is the section that looks like definitions located at the very top of our Markdown & HTML files. 
  - So, you will see I added `list_title: Some Blog Posts` to the top part of my `index.md` file. This overwrites the theme's defaults. 

<br>

*****
<br>

💡Hint: If you just want to remove the heading entirely, define `list_title` with a space in between a set of quotes: `list_title: " "`