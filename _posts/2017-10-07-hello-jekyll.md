---
layout: post
title: Hello Jekyll
date: 2017-10-07 15:39
tags: [ software, code, blog, jekyll ]
---

I figured I'd share here what I've learned about [Jekyll](http://jekyllrb.com) and free hosting with [GitHub Pages](https://pages.github.com/). After looking into Jekyll and deciding to try it out, I was pleased to realize that not only will GitHub host it for free, but it includes built-in support for Jekyll too! Not sure how I missed that before.

## Why Jekyll?
So first, why did I choose Jekyll (before realizing GitHub supports it)?  

I was looking for something simple to use for a serverless website/blog, something that would make it easy to document and share projects (like this).

#### Simple and Elegant with Markdown
With Jekyll you write up blog posts and author page content using Markdown. So to make a new post you create a file that looks something like this:
```
---
title: Hello world
date: 2017-10-07
---
###### An Example  
Here's an example I'd like to share:  
```javascript  
console.log("Hello world!");  
```                             ...
```

Which will create a post with content that looks like:
> #### An Example  
> Here's an example I'd like to share:  
> ```javascript  
> console.log("Hello world!");  
> ```  

Nice, right? I think so.

#### Static and Serverless
Jekyll outputs static websites. And since GitHub is freaking awesome, it will automatically build your Jekyll site and host it for you. What does that mean?  

I don't even need a development machine/server in order to write my posts. All I need is a browser logged into my GitHub account, I can create a new markdown file in the `_posts` folder, commit the file, and GitHub will automatically re-build and host your static website.  

Now that's even nicer, right? I sure think so...

Check out the [Jekyll documentation](https://jekyllrb.com/docs/github-pages/) to learn how to configure your project to build on GitHub  Pages.

### Nice, Clean, Responsive theme with Pixyll  
I chose the [Pixyll](http://pixyll.com) theme as it is:
- A nice, clean, minimal design
- Responsive (looks good on tiny mobile devices)
- Open Source (MIT license)
- Based on [basscss](http://basscss.com/), keeping the CSS simple.
