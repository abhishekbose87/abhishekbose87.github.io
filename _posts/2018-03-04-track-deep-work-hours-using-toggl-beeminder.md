---
layout: post
title: Using beeminder and toggl to track my "Deep Work" hours 🤖🔥
---
In the last few years, I became increasingly worried about how my focus was decreasing and I wasn't able to create work to my potential. I knew this was a problem but I had no way to measure it.

> "If you can't identify it, you can't measure it." - Someone

Then when I read the book "Deep Work" by Cal Newport, I finally had better insights to attack this issue I was facing as a remote developer. There was no boss here. So if I wasn't improving myself, then my career as a knowledge worker was going to suffer.

Now while I got the term "Deep Work" to drive my efforts in the right direction, I found that I wasn't able to track my "Deep Work" hours. The manual way of tracking my hours was painful and  I had no incentive to do so. I had some rewards but that didn't help either. So while I spoke to my friends about "Deep Work" and why one should practise it, I was not able to measure it because of my human instincts.

> "If you can't measure it, you can't improve it." - Peter Drucker

Before, I state the system that I have in place right now. I want to mention two important points which one should keep in mind when they are reading any productivity hack post on Internet.

- Hacks are personal. What works for me doesn't imply that it will work for you.
- Hacks evolve over time. You need to have patience to unravel your version.

---

Now without further adieu, let me mention the details of the system I use to track my [deep work hours](https://www.beeminder.com/abhishekbose87/deep-work). It's been working from December and I have found a liking to it.

- Use [toggl](toggl.com) to track my tasks. I added a tag `#deep-work` to identify those items specifically.
- Use [beeminder](https://blog.beeminder.com/tao/) to add an incentive to put in my quota of deep work hours every week. It's simple, if I don't do 10 hours of deep work for the week, then my credit card gets swiped for 5 dollars. *(It's a small price to pay for success)*
- Use a python [service](https://github.com/AdrienLE/beeminder_toggl) to send data automatically from toggl to beeminder since there was no direct integration available on beeminder site. Now since I am a nerd, I hacked the implementation to send data only for `#deep-work` tag as I use toggl to track other items as well 🤓

Boom !! 🚀

![I am Happy]({{ site.baseurl }}/images/all-the-things.png)
