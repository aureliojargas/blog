title: Blog Redesign: Focusing on Microdata
date: 2012-12-06 18:36
categories: blog blug python

If you're a regular reader of this blog and visited in the past few days, you
likely noticed a dramatic difference in the blog's look and feel. The HTML for this 
blog has been generated by [Blug](http://www.github.com/jeffknupp/blug), the
static site generator I wrote, since about July. Previously, I was using
Octopress and was generally happy with it. 

So was every other technical blogger on the planet. 
<!--more-->
I didn't want to have a blog that looked identical to a hundred others. More
importantly, I wanted more control over the metadata associated with the blog.
Google introduced Authorship, content aggregators are becoming more sophisticated. 
I wanted my blog to keep up with the times. So Blug, and this blog by extension,
is now chock-full of microdata from [schema.org](http://www.schema.org).

The designed changed as well. Octopress relied on tools and technologies that I
didn't use in any other context, so I started from scratch with what I knew:
 [Bootstrap](http://twitter.github.com/bootstrap/), [less](http://www.lesscss.org), and simple Markdown. I'm no UI expert so everything is pretty
spartan, but it get's the job done. If anyone designer out there is looking for
some free publicity, feel free to re-theme the blog and I'll link to it from
here.

Lastly, this is the first change in a much larger vision I have for Blug. If you
check out the code from GitHub, you'll notice there's a web server in there with
in memory caching of generated pages. Blug will eventually generate *and serve*
blogs, with plugin services that are able to regenerate the static page in
response to some external event. Stuff like adding links to other sites discussing your
post in real-time, without any intervention. And gathering analytics locally
rather than relying on third party services. But those changes are still in the
works. Stay tuned.
