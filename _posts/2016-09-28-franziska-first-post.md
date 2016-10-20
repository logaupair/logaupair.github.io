---
title: Mein erster Post
date: 2016-09-28 13:09:47 Z
categories:
- posts
tags:
- Test
bg: wroclaw-rynek.jpg
layout: post
crawlertitle: Test Blog
summary: Das ist eher fürs Archive
author: jacmendt
---

To all the ladies in the place with style and grace
Allow me to lace these lyrical duches in your bushes
Who rock grooves and make moves with all the mommies?
The back of the club, sippin Moet, is where you'll find me
The back of the club, mackin hoes, my crew's behind me
Mad question askin, blunt passin, music blastin
But I just can't quit
Because one of these honies Biggie gots ta creep with
Sleep with, keep the ep a secret why not
Why blow up my spot cause we both got hot
Now check it, I got more Mack than Craig and in the bed
Believe me sweety I got enough to feed the needy
No need to be greedy I got mad friends with Benz's
C-notes by the layers, true fuckin players



[![railroad]({{ site.upload_dir }}/test-image.jpg)]({{ site.upload_dir }}/test-image.jpg)

If you've already read all those titles and you feel pretty comfortable with the topics they cover, it's time we dive into the evolution of JS to explore all the changes coming not only soon but farther over the horizon.

## `let` Declarations

## Test

However, we can now create declarations that are bound to any block, called (unsurprisingly) *block scoping*. This means all we need is a pair of `{ .. }` to create a scope. Instead of using var, which always declares variables attached to the enclosing function (or global, if top level) scope, use `let`:

{% highlight js %}
var a = 2;

{
    let a = 3;
    console.log( a );   // 3
}

console.log( a );       // 2
{% endhighlight %}
