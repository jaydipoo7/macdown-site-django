---
title: Introducing the MacDown Blog
author: Tzu-ping Chung
published_at: 2014-07-31
---

Mic test one two. Eh-hem.

This has been on my mind for some time. Back when I released MacDown 0.2 I felt that we have too much to fit inside the release note, so I wrote a [blog post](https://uranusjr.com/blog/post/59/macdown-0.2/) for it. But it seems a bit queer, to say at least, to use my personal blog for that purpose. And the post doesn’t really fit well with other posts there either, as my personal blog targets more toward Chinese audience. So I figured that it’d be better to find somewhere else in the future.

I have also received a lot of emails/tweets/DMs recently for MacDown. I love them, and have tried (and will continue to try) answering them the best I could. But I am by no means an expert on Markdown, let alone many other topics people ask me about, and I’m sorry I can’t answer many of your questions. For those I can answer (not a lot, really), many are common enough that I got asked multiple times. Some of them have been added as [FAQ](/faq/), but there are more that don’t fit, and they need a good place to the public.

One particular instance is when I got asked whether I can recommend a blogging platform that supports extensions MacDown has. And I honestly have no idea. I [host my own personal site/blog](https://github.com/uranusjr/uranusjr.com), and it uses a custom renderer to process Markdown. While the configuration does somehow resemble MacDown’s, they are still different, and at times incompatible with each other. I haven’t tried many other online services, but as far as I know there’s nothing that fits the asker’s requirement (which is not saying those platforms are bad—they are just incompatible).

So, I decided that MacDown should have a blog. This way I can talk about topics on MacDown and Markdown-related things in general, in English, at a dedicated space. I also decided to [build the functionality myself](https://github.com/MacDownApp/macdown-site/tree/master/blog) instead of using an existing service/library, hoping to provide some ideas if somebody wish to make his/her own blogging/CMS platform compatible with MacDown. I am fairly satisfied with the current result, and might talk more about it in detail in the future, given the time.

That’s about it. I’ve attached MacDown’s `help.md` file as a post so that you can get an idea how compatible this thing is currently. You can see there are still issues, some of them require additional implementation at this side, and others are caused by bugs in MacDown and Hoedown. I will continue to improve it in the future.

Until then!
