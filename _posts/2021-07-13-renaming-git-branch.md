---
toc: true
layout: post
description: It's simple. But it's easy to forget.
categories: [markdown]
title: Renaming Git Branches
---
## TL;DR version

```
git branch -m old-branch new-branch
```

## Long version

If you have two branches, `master` and `old-branch`, and you're on `master` branch. If you wanna replace the name of the branch `old-branch` with `new-branch`, type this in your terminal:

{% highlight Bash shell scripts %}
git branch -m old-branch new-branch
{% endhighlight %}

If you're on `old-branch` branch already, enter this:

{% highlight Bash shell scripts %}
git branch -m new-branch
{% endhighlight %}