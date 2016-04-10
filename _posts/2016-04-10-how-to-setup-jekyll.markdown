---
layout: post
title:  "How to setup Jekyll"
date:   2016-04-10 20:47:26 +0200
categories: jekyll
---

see [Jekyll](http://jekyllrb.com/) for more detailed notes

{% highlight shell %}
gem install jekyll
jekyll serve
{% endhighlight %}

And open browser on [http://localhost:4000](http://localhost:4000)

[Directory structure](https://jekyllrb.com/docs/structure/) (more or less in order of first edit)

- config.yml
    - site configuration
- layouts
    - default.html: the other layouts inherit from this, so look at it first
    - general html layouts for types of pages
- posts
    - `YYYY-MM-DD-name.markdown` named files for posts
- includes
    - files that can be included using `include header.html`
- sass, site, css
