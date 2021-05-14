---
layout: post
title: "Un-commit last un-pushed commit keeping changes"
date: "2021-05-14 12:28"
categories: git
---

When a commit has been done with changes that we do not want to commit, undo the commit keeping the changes with:

{% highlight bash %}
git reset HEAD~1 --soft
{% endhighlight %}
