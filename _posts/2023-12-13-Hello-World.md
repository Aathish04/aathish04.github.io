---
title: Hello World
published: True
---

I've decided to start writing about my projects and ideas, both the ones that I open source and the ones that I keep locked away in some deep dark git remote because of blood contracts and pinky promises. Call me a little strange, but I think it's just as important to document _why_ your projects exist as it is to document _how_ they work. Sure, maybe not everything you make has to have a story beyond "I had a school/college project", but for those that do, I think writing the story down is worthwhile. Who knows, maybe it'll give someone else a great idea and they'll go on to build something awesome.

## [](#expectations)Cool, What can I expect here?

It's a personal blog. Like I said, I'll probably talk about stuff I'm working on.

## [](#specifics)Okay, but what specifically?

Well aren't you curious? I'll write about a little bit of this, a little bit of that, and almost definitely about the █████ and the █████.

In all seriousness, I work with Technology and Computers, and I'm interested in Cybersecurity, AI, IoT and lest this become _too_ generic, I dabble in Automation as well, so expect some words on those.

I have a few projects on [my GitHub page](https://github.com/Aathish04) that I think I could talk about beyond the stuff I've written in each of their README files.

I suppose you could think of this site as both a combination of a blog and a portfolio website. I'll try to make each of my posts link to a particular project.

In that vein, I guess this post is related to the site as a whole, so I'll talk in specific about how it works.

## Jekyll + GitHub Pages + Docker = Awesome

I used to write (well, I had two articles) over at [Repperium](https://repperiumsci.blogspot.com) and I guess I could have kept posting there, but I wanted something even simpler than the WYSIWYG editor that BlogSpot offered. I was already comfortable working with GitHub, Markdown and GitHub Pages, so moving the blog to GitHub pages seemed like a rather appealing idea.

I mean, most if not all of my projects have pretty detailed README files that I could _borrow_ text from and the Git based workflow really appealed to me, so I decided that I'd figure out how to set up this blogfolio.

Some basic research online informed me that GitHub pages uses Jekyll by default, so I figured the path of least resistance would be to use that and build a blog around it. Thankfully, GitHub had [a guide](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-a-theme-to-your-github-pages-site-using-jekyll) ready for that so I could set it up in a flash.

The thing is, pushing every little change to GitHub without knowing what it looked like first _didn't_ seem very appealing to me, so I had to set up a system to I can preview my changes locally.

GitHub's official recommendation is to install Jekyll locally and build+serve the site using it. Now, I don't plan on writing several blogs using Jekyll, so I didn't see much value in installing Ruby, installing Jekyll and its dependencies and spending all of that time when I could be using it to y'know, actually write stuff.

I instead chose the easier route and let someone else do all the hard work for me.

Whenever I have to install a piece of software for a one-off thing like this, I try to make it a habit to check if someone's published a `Docker Image` for it first. Fortunately, [this Docker Image](https://github.com/BretFisher/jekyll-serve) by Bret Fisher seemed to be exactly what I was looking for. Thanks, Bret!

The theme is a slightly modified version of [this theme](https://github.com/tocttou/hacker-blog) by [Ashish Chaudhary](https://github.com/tocttou/). I really like the minimalist style and monospace fonts, and I switched around the colours to be a little more reminiscent of my colour theme over at Repperium.

So yeah, those are some generic specifics (an oxymoron if there ever was one) on my workflow with respect to this site.


I'm currently writing this when I should be preparing for Finals, so I better get back to that.

# _Fin_