---
title: Creating My First Website Using R
author: Jojo Abalos
date: '2020-04-10'
slug: creating-my-first-website-using-r
categories:
  - R
tags:
  - R
  - R Studio
  - Blogdown
  - Netlify
  - Github
  - Namecheap
subtitle: ''
summary: ''
authors: []
lastmod: '2020-04-10T14:37:08+08:00'
featured: no
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
---


I came across this twitter post from [@dsquintana](https://twitter.com/dsquintana?s=20) and this encouraged me to make this personal static website.  



<blockquote class="twitter-tweet"><p lang="en" dir="ltr">📝🖥 &quot;How to make a free personal website in R&quot;<br><br>👤 Dan Quintana <a href="https://twitter.com/dsquintana?ref_src=twsrc%5Etfw">@dsquintana</a><a href="https://t.co/YfWLI0RLvj">https://t.co/YfWLI0RLvj</a><a href="https://twitter.com/hashtag/rstats?src=hash&amp;ref_src=twsrc%5Etfw">#rstats</a> <a href="https://t.co/x8uNbXaGEr">pic.twitter.com/x8uNbXaGEr</a></p>&mdash; R posts you might have missed! (@icymi_r) <a href="https://twitter.com/icymi_r/status/1246295506495700996?ref_src=twsrc%5Etfw">April 4, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script> 


I have tinkered quite a bit on ` blogdown ` r package authored by [@xieyihui](https://twitter.com/xieyihui?s=20) awhile back when I watched his webinar vid. I got reunited to this recently, and now was able to have a complete setup using R Studio, Blogdown, Github, Netlify and Namecheap.  

After some few struggles, I am quite happy to have successfully configured the continuous deployment from Github in Netlify. 


Here are the key steps that I took to help me bring this site up.

1)  Using R Studio, install the blogdown package ` install.packages('blogdown') `

2)  Create a new project, select "website using blogdown" and type in *gcushen/hugo-academic* in the Hugo Theme field.

3)  Set-up the relevant files accordingly.  Refer to this [link](https://www.dsquintana.blog/free-website-in-r-easy/) for the specifics in setting up the files.

4)  To view the website, you can use ` blogdown::serve_site() `.

5)  Setup an account in [Netlify](https://www.netlify.com/) where you can host your website.

6)  In case you are a student in an accredited university, you can apply for a free academic domain ` yourname.me ` in [Namecheap](https://www.namecheap.com/).

7)  Link your Netlify hosted website to your domain in Namecheap.

8)  Create a Github account and upload your blogdown project files to a new repository.  

9)  Setup continuous deployment setting from git repository in Netlify.

*Note: I intend to update this post with the specifics on each of the steps for reference. Meantime, let me know if you need some more details in any of the above steps*

