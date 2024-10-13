---
title: "Self-hosting all the things"
date: "2022-12-01"
summary: "I've been through the cycle of writing on Blogger, Wordpress, Tumblr, Medium, Substack. No more, the cycle has to end. I'm taking back control." 
description: "I've been through the cycle of writing on Blogger, Wordpress, Tumblr, Medium, Substack. No more, the cycle has to end. I'm taking back control."  
toc: false 
readTime: true
autonumber: false 
math: true
tags: ["self-hosting"]
showTags: false
---

Last month, I thought I'd try to write on Substack. I haven't had a personal blog for some years, though I used to write very actively in the 2000s.
However, one thing didn't sit well with me, especially after the Twitter ownership change, and my previous history moving from Blogger, to Wordpress, to Tumblr, to Medium and away:

There is always going to be a new “hotness” in the content space, another Silicon Valley startup trying to monetize other people's writing, and the people who read it.

It's probably time to opt-out of the cycle, and take ownership of my content.

What does it mean in practice? I certainly won't be spinning up a cluster to host my blog, nor will I try to self-host my SMTP server for an email list. But I want the following characteristics:
* Content is mine. I have it. I own it. Preferably in Markdown.
* People visit a domain that I own. That I can move to another technology or provider at will, together with the content I've produced.
* The email list that goes with the blog is under my control. I know who is on it, and I control when anything is sent in my name. 
* Generally privacy respecting technologies. No Google Analytics.

If you read this, you are seeing the results. How have I done it?
* I created a blog with [Next.js](https://nextjs.org) & [Tailwind UI](https://tailwindui.com). First time using any of the technologies, but it was fast and painless.
* I'm hosting it on [Vercel](https://vercel.com). I might change it in the future, but it was a quick way to host a Next.js app.
* I have user analytics with [Plausible](https://plausible.io), which is cookie free and GDPR compliant.
* I use [ConvertKit](https://convertkit.com) to host the mailing list. I would rather not get into an endless loop of deliverability tweaking, so this will do. Their product seems easy enough to use, and unobtrusive compared to Mailchimp et al. Also, I can move the list later if I want to something else with ease.
* I've set up [Disqus](https://disqus.com) for comments. I'll try to keep comments on for now, as I appreciate the conversations it can spawn. But if it becomes a cesspit of spam and arguments, I might turn it off later.
* Before adding content, I edit on [StackEdit](https://stackedit.io), simply because it is browser based, which gives me access to the excellent [LanguageTool](https://languagetool.org) to correct spelling, grammar and tone. LanguageTool is a must have for me, as I write in four languages frequently.

Figuring this out and building it didn't take long, surprisingly. It's a lot of new stuff to me, but a couple of evenings, totalling maybe 3-4 hours is all it took.

## OK, but what will this site be about?
With this said, what do I intend to write about?
As you might gather, many things related to deeper thinking on software engineering (excluding code/language level thoughts), DevOps, Platform Engineering, tech leadership already go on the blog of my company, [Chaordic](https://chaordic.io), and I intend to keep it that way. I'll probably notify people who sign up for emails here about it (where you are not signed up to both, which I'll try to keep track of).

There will be some overlap here, but it will be less edited, more from _"shooting from the hip"_. 
Here I will likely write evolving thoughts & musings about better organizational operating models, better ways of working. Also subjects where tech & entrepreneurship overlap. And probably some amount of tech business analysis, a very tiny bit of finance/geopolitics and general nonsense.

If I had to summarize it: I'm interested in, and will write about, the things in motion that will shape our future.

If that sounds like your thing, feel free to sign up to the mail list, and I'll notify you whenever I write something new!
