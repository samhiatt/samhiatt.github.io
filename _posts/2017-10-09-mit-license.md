---
layout: post
title: MIT License
date: 2017-10-09 15:21
tags: [software, open source, foss, MIT license, copyleft]
---

I've been a proponent of open source software for quite some time now, but TBH, [FOSS licenses](https://choosealicense.com/licenses/) have always been a bit confusing to me. I understood that some licenses were permissive, basically letting people do whatever they want with the code, whereas others like the [GNU General Public License](https://www.gnu.org/licenses/gpl.html) not so permissive and were considered "viral", requiring any derived works to recursively be licensed under the same GNU terms. But the finer points of open source licensing have always remained a bit elusive to me.

For example, the theme I chose for this site carries a [MIT License](https://opensource.org/licenses/MIT), and since I will likely modify the theme, and any modifications I make I intend to keep open source, I wanted to make sure I do licensing properly and give proper attribution.

### Why is all this important?

Well, maybe all this isn't actually all that important. I mean, it's a bit hard for me to imagine a scenario where there's a copyright dispute over modifications I make to this blog's theme. But still, I figured it was a good exercise to help me understand open source licensing a bit better, plus I just wanted to get it right on principle.

### The One Condition of the MIT License
My understanding of the MIT License was basically that it meant, "go ahead and use, copy, modify, do whatever with it, _just give me credit_", but turns out it's a bit more specific. Here's it's one condition:

> The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

But if the code gets modified and ends up being a mix of work from many contributors? Do I change it to my name if I modify the theme? Is there some threshold of changes at which the code becomes "mine" and I should then change it?  

In researching this question I came upon this kinda funny thread (I thought so anyway) that I believe is a pretty good example of what resolving a licensing dispute should look like.

Apparently Handlebars.php had the same misunderstanding of what the MIT License meant, and [here is what the mustache.php creator had to say about it](https://github.com/XaminProject/handlebars.php/issues/57):

![screenshot: The MIT license only has one condition, and somehow you managed to violate it]({{"images/ScreenShot2017-10-09_MITLicenseOneCondition1.png" | absolute_url }})

The XaminProject was happy to comply, and they ended up with a multiple-line copyright header that looks like:
```
The MIT License (MIT)

Copyright (c) 2010 Justin Hileman
Copyright (c) 2012 ParsPooyesh Co
Copyright (c) 2013 Behrooz Shabani

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software...
```
#### My Approach
I ended up following the specific wording suggested in [another helpful thread at stackexchange](https://softwareengineering.stackexchange.com/a/158011) and ended up with a copyright header that looks like this for this site:
```
Original work Copyright (c) 2014-2015 John Otander
Modified work Copyright (c) 2017 Sam Hiatt

MIT License ...
```

So in this case it means that [John Otander](http://johnotander.com/) retains the copyright for his original work, and, by using the MIT license, gives me permission to use, modify, and even sublicense it. I retain copyright for any modifications I make, and I license my modifications under the MIT license as well.

In reality, if anyone ends up leveraging any of the modifications I make to this site's theme, or [any of my code on github](https://github.com/samhiatt) for that matter, and if I find out about it somehow, then I'll probably be quite flattered, actually. And if they've retained the copyright notice with my name and John's name, appending their own name, then I'll be even more impressed.
