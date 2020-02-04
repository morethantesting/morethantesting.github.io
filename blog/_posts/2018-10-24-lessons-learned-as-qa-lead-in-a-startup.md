---
layout: post
custom_css: blog/blog.css

title: "What I've learned after 30 days as QA Lead in a startup"
description: "Read more to get to know lessons learned from becoming a QA Lead in a startup, provided with examples and stories from my experience."
excerpt: "In the final part of the series, I reflect on the first 30 days as QA Lead in a startup and talk about lessons that I've learned during that time. For each lesson I tell my own story, including the conclusions and the 'dos and don'ts'."
date: 2018-10-24T12:40:28+00:00
author: MoreThanTesting

image: /blog/assets/lessons-learned-as-qa-lead-in-a-startup.jpg
alt: "Lego workers maintaining the body of a DSLR camera"

read_time: 8
redirect_from:
  - "/lessons-learned-as-qa-lead-in-a-startup"
  - "/lessons-learned-as-qa-lead-in-a-startup/"
  - "/lessons-learned-as-qa-lead-in-a-startup/amp/"
---

_This article is the final part of a series about [joining a startup as the first QA]({{ site.baseurl }}/blog/joining-a-startup-as-the-first-qa/), You can also read the previous part about [the first month as QA Lead in a startup]({{ site.baseurl }}/blog/first-month-as-qa-lead-in-a-startup/)._

* * *

I've spent my first 30 days as QA Lead in a startup and I want to share with you 5 important lessons that I've learned so far.

Let's start.

## Lesson #1: The best way to start is to start over

This is the first lesson, and in my opinion, the most important one.

When I joined the startup I'm currently in, I was biased. I thought that whatever worked well in the previous workplace, would work in this one as well. Consciously or not, I started suggesting improvements to processes and tools without having full context or understanding of why they have been implemented that way in the first place. My intention was good, but my approach was wrong.

And you know what? I wasn't alone. Whenever I talked to people joining the company after me, I heard similar suggestions.

It turns out that when we come to a new place, we see things working differently and we start to wonder. It's our curiosity and there's nothing wrong with that. Then, however, we start making suggestions and most of the time they're not relevant.

The thing is, there are no two exactly the same workplaces in terms of product, technology, engineering, people or culture. Given that, there are no two identical processes for any of these. When you change your job, you change perception, environment and you change your point of view on many things. You literally _start over_, so there's no point to drag the old baggage with you.

Now, going back to my story. What have I learned?

I understood there's no point to stubbornly convince myself and others that we should do things the same way as it has been done in the previous companies I worked for. Simply because it doesn't apply here.

I've made this mistake twice, but since I'm writing this, I hope I've finally learned.

If there's something particular that I want you to remember from this lesson, it's this:

**Dropping the notion of the best practices taken from any previous workplace is the best practice I have now.**

**Start over:**

  * Forget the way things worked before - it's different now.
  * Drop your beliefs - they may not apply now.
  * Reinvent your approach - by observing and adapting your knowledge to the current environment.

## Lesson #2: The first thing to take is to take ownership

At the beginning of my career, I have worked for almost two years in a big corporation, where I was responsible for executing pseudo-automated tests that required a lot of additional manual verification. My role was independent, but I was still a part of bigger team that was kind of a shell. I was inside - someone else was handling things outside. I was still a junior - little did I know about the importance of taking ownership.

Then I joined the first startup in my career and during the first month, I've learned how crucial it is.

At first I was quiet and reserved. I tried not to stand out, because that's how it worked well in the previous job, so why change it? (As you can guess, I didn't know yet that I needed to _start over_). But in that startup, something has changed - the approach of taking up the tasks was different. Everyone was coming up with ideas and taking up tasks proactively, without anyone's suggestion or delegation. It was more about being proactive and responsible. It was _taking ownership_.

Once I noticed how it worked, I started doing the same. The result? Respect from the team and recognition from the team leader. That was the moment I realised that taking ownership instead of waiting for being assigned a task was _the right thing to do_. In fact, that was the foundation of my futher growth.

Not only I could work on things that I was interested in, but I could also add value to the team. They could trust me.

How did it relate to my current QA Lead role? It was exactly the same. With the difference, that this time I knew exactly what I had to do. I realised that joining a new company is the biggest opportunity to show my approach, introduce my thinking and start doing things my way - before anyone even asked.

So remember, the first thing to take is to take ownership - and do it proactively.

## Lesson #3: The good way to ask is to ask for help

This is the kind of lesson that I can't learn enough. I've been reminded this in all workplaces - every time I postponed or refused to ask for help.

I can tell you exactly how many times asking a question or two speeded up solving my problem by hours or even days. And not asking - slowed it down and caused delays. _Every single time._

I thought I could build testing framework alone. I thought I could automate all tests by myself. I thought that only I could perform acceptance testing on a feature. Wrong. Wrong. Wrong. With this mindset, I wasn't accelerating the progress - I was holding it back.

It's strange - we prefer to close ourselves in an invisible box and fight with our problems alone instead of doing a little effort to ask someone for help.

We think that asking for help is humiliating. Wrong. Asking for help is liberating. It's unlocking your work. It's freeing up the possibilities of solution. It's saving time of execution. It's opening the path for delegation. Asking for help enhances all qualities of leadership.

If you're in a leadership role and you don't ask for help - you're not really a leader. You're a bottleneck - you think you know it all and can do better than everyone else but in fact you just slow everything down.

Don't be this kind of leader. **Ask for help**.

## Lesson #4: The wise thing to use is to use data

Again, this is one of the lessons that I've learned early in my career but I still remember until today.

Blame me, but I used to base some of my decisions purely on my own opinions mixed with little experience, without actually backing them up with proper research. I was lucky enough not to mess things up too much. I've learned this lesson the soft way.

I definitely remember it now as QA Lead. And this time I've done it properly. Let me tell you how.

When I started at my current job, one of the first tasks I recognised I had to do was automating UI tests for buying subscription via website. Remember, it was _days_ after I joined and had little context of what's going on - but I knew I had to act.

Did I use the tools I used before? Did I only test on Chrome because everyone uses it? No. First thing I did was taking a look at usage data. I looked up for the most used browsers _among our website users_.

What turned out? Over 50% of visitors used mobile Safari. Could the framework that I was already familiar with test Safari? No.

I've chosen a testing framework based on the real usage - not on the best practices in my previous workplace. Hadn't I looked at data first, I'd end up wasting a lot of time doing the wrong thing.

You might have seen many of the bullet-pointed lists of "The best testing tools you should use" that say you to always use Selenium because everyone does - please stop. Don't test basing on someone's else best practices - use your data. Do you remember lesson #1? Whatever worked for them, may not work for you at all. Forget it and start over. There is only one valid approach.

**Test basing on data collected from users of your product.**

Regarding the bullet-points, here are the only ones you need:

  * Don't guesstimate - ask users.
  * Don't make decisions based on opinions - use data.

## Lesson #5: The important thing to mind is to mind your health

This lesson is about not getting ill, and I'm not kidding.

There's a short story behind it. It's from a collie from my previous work who had become a team leader 6 months before I did. It was his first leadership position and no wonder he was stressed about it.

After few weeks, he told me this: _"Listen, I haven't been ill for ages but 2 weeks in this role and I caught a proper cold. I don't know what happened, if this is a coincidence or not, but all of a sudden I couldn't get up from bed for a whole week. Do you imagine?"._

I imagined - I heard it from other people too. We discussed this further and the only sane conclusion we could come up with was the correlation of taking over a more responsible position and the stress that it brings.

The lesson learned here is to be more careful during the first month and listen to the signals coming from your body. If you feel you have enough - say _"It's enough"_ and go home. Try to find ways to relax - more than you usually do. Find more time to take care of yourself, even though you think you have to focus on "more important things". You may miss a deadline or two but in the long run, you'll be better off. Apply something my friends repeatedly tell me: _"Work hard. Rest hard. But never too hard."_.

Last but not least, if you're looking for medical supplementation, forget carrots and vitamin C. I found out that <a href="https://www.sciencealert.com/here-s-the-only-supplement-you-should-take-for-a-cold" rel="nofollow">zinc is more effective</a> and, if taken as soon as you feel the first symptoms, is a good way to ease or even prevent from the cold. Since I started practicing this, I feel that zinc has already saved me several times.

P.S. Yes, I got ill in the third week.

* * *

And here we are with 5 lessons learned as QA Lead in a startup:

  1. The best way to start is to **start over**.
  2. The first thing to take is to **take** **ownership**.
  3. The good way to ask is to **ask for help**.
  4. The wise thing to use is to **use data**.
  5. The important thing to mind is to **mind your health**.

* * *

With this article, the series of joining a startup as the first QA comes to an end. To read more articles from this series, [follow this link]({{ site.baseurl }}/blog/joining-a-startup-as-the-first-qa/).

If you enjoyed reading it so far, please spread the word and share it with your friends or on social media. I appreciate every share.

Additionally, if you want to be notified when a new article comes out, **subscribe below** and follow blog on [Twitter](https://twitter.com/MoreThanTesting).
