---
author: "benbalter"
layout: post
did: "blog9"
title:  "Usage Guide"
categories: jekyll update
img: coding.png
date: 2017-03-12 8:00:00
categories: two
tags: coding
---

Use the guide to prepare good looking posts! The theme has a sidebar in the post layout which consists of post image, recent posts and facebook like box. This can be extended by editing the ``sidebar.html`` in **_includes** folder.

## Image

- Use image of ratio 400x250 (800x500).
- Keep them inside ``images`` folder.
- Mention image name in the front matter as shown below

{% highlight yml %}
---
layout: post
title:  "Some title"
categories: some category
img: image-name.jpg
---
{% endhighlight %}
