---
layout: post
custom_css: blog/blog.css

title: "First week as QA Lead in a startup — 5 steps for 5 working days"
description: "Read more to learn 5 steps that you should do in the first week as QA Lead in a startup, including real examples and practical advice."
excerpt: "In this article I talk about 5 steps that you should do in the first week as QA Lead in a startup, including real examples showing how I have actually done it."
date: 2018-10-01T13:34:57+00:00

image: /blog/assets/first-week-as-qa-lead-in-a-startup.jpg
alt: "Lego trooper standing under a tree with a weapon"

read_time: 8
redirect_from:
  - "/first-week-as-qa-lead-in-a-startup"
  - "/first-week-as-qa-lead-in-a-startup/"
  - "/first-week-as-qa-lead-in-a-startup/amp/"
---

_This article is the third part out of five articles about [joining a startup as the first QA]({{ site.baseurl }}/blog/joining-a-startup-as-the-first-qa/). You can read the previous part about [3 things I wish I knew on the first day in a new job]({{ site.baseurl }}/blog/first-day-in-a-new-job/)._

* * *

In this article I will tell you about the first week as a QA Lead in a startup. In contrast to the previous parts, this time I'll get more into QA-specific details.

So, one week. 5 working days. Doesn't sound like a lot, does it? But don't get fooled. It turns out these are very, very important five days.

Why? Because this is the time when you can make great impact. Time, when you define what you and the team is going to focus on in near future.

Look at it this way --- in the first week, you're free. You're fresh and you see things from different perspective. That means it's a perfect time for you to pay attention to what's happening around and planning your further work.

So what should you do in the first week? Here are 5 steps that I recommend.

## **1. Get the baseline**

First of all, you should find out what the current status of QA process among all products and projects is --- **the baseline**.

Note that **it is the most important task** in the first week. Both short-term and long-term decisions will be based on the outcome of this challenge. Thanks to this, you'll not only see where you stand, but it'll also help you put priority on most important things.

There are three steps that will help you in getting the baseline:

### **Talk to people**

Firstly, talk to the _engineering manager_ --- he has the best high level overview of what the biggest pains are.

Then talk to _engineers_ from all areas: frontend, mobile, backend, hardware. They will give you the fresh update on how it really is.

Finally, talk to _product managers_. Talk about how you see your collaboration. That's because as a QA Lead you'll work with them way more than with anyone else.

Here's a bunch of questions that you may find helpful during your investigation:

  * what is already working well?
  * what are the biggest pains you can see?
  * how would you fix them?
  * what is slowing down your work the most?
  * what are users struggling with?

Frankly, when I first talked to engineers, asking them these questions, I was surprised of the responses. As we spoke, they not only recognised what we could improve but they also provided ideas how to do it. And me? I was just asking questions, listening to answers and writing problems down. And the solutions started emerging alongside.

### **Observe**

Once you have insight into current process, start watching how everything works.

Compare what you see to how it worked in your previous companies. Take advantage of the unbiased, fresh point of view and objectively assess the situation:

  * is the project management process simplified?
  * are the tickets well-defined?
  * is the team communication efficient?
  * is testing culture embedded into the team?

Next, get access to analytics tools where the data is stored. Learn how customers use the service or product and include it in your reports.

And remember --- it's not only the quality of the product and service you'll be taking care of, but also the quality of teamwork and of communication within the team.

### **Write it all down. And show it**

Last but not least, gather all that knowledge in one place. Note everything down and share with the team.

There are two main reasons why you should do it:

  1. You show your work.
  2. Everyone is up to date with current status.

By showing your work, you will also get respect. It will give confidence not only to you but also to the team. At this stage, no one will doubt that you should be doing something else instead.

Bringing everyone on the same page will help you prioritise and focus on the right things. You will also be able to back up your decisions --- and no one will question.

Personally, I presented it in form of a status matrix listing projects and matching them with QA factors that we wanted to improve. Also, it's cool to see how everything improves as you go. Here's a status matrix I created for one of the previous startups that I worked for:

{% include image.html src="/blog/assets/qa-process-status.gif" alt="QA Status Matrix" %}

## **2. Assess the risks**

Now you've done the research, it's time to figure out what to take care of first. Prioritisation is a challenge but here's where the risk assessment comes to rescue.

There are two things you can leverage to help you with this task:

  * using data,
  * using your experience and QA gut feeling.

Using data is straightforward. Get it, analyse, make conclusions.

Note that by data I mean not only the baseline you've gathered from the team, but most importantly what you can get from users. Whether these are outcomes of user testing or analytics data of the product.

Also, here's where you should use your experience and listen to your QA gut feeling. You have to trust yourself --- there's no one who can do it better than you.

In my case, I used the following deduction method to find the most critical path:

  1. What is the most important thing for this early stage startup? _Grow, make money and get customers._
  2. How does the startup can achieve that? _By selling a product to customers._
  3. How customers can buy the product? _Through website and in-app._
  4. Do we tests buying a product via both website and app? _Sometimes, manually._
  5. Let's automate end-to-end tests that cover customer's critical path in order to create a safety-net whenever we make any change to the product.

Quick takeaway from that is to think not only from customer but also from business perspective. As a tester in a startup, you have to sometimes compromise on both.

## **3. Set short-term vision**

Based on the baseline research and risks assessment you've done, you're now ready to set a short-term vision.

I've mentioned before that getting the baseline is the most important tasks for the first week --- and I wasn't lying. But it's the short-term vision that will have the biggest impact on the near future.

What should be included?

  1. An attack plan for mitigating the biggest risks with a focus only on priorities and quick wins
  2. Tasks in project management system that can be accomplished within a month.

One advice on that: _don't make it perfect, just make it right._

What I'm trying to say is that you're not setting anything in stone here. Sure, you have to write down something, but treat it more like guidelines. I suggest you to take an iterative approach: first you try, then you learn, then you adapt. This means the plan can be modified as you go --- and that's fine as long as you focus on the right things.

Note that in contrast to long-term vision, in this short period you should be more focused on the results than the process.

What I did was creating a phased attack plan for implementing end-to-end automated UI tests for both website and mobile platforms. It went as follows:

**Phase 1**

  1. Research website UI testing frameworks allowing to test on desktop and mobile Safari (which at the time was the most used browsers among visitors).
  2. Initialise the testing framework in the project's repository.
  3. Proof of concept: create the simplest test and run locally on Safari.

**Phase 2**

  1. Extend the test suite with user's critical path of ordering a product.
  2. Make it run on Continuous Integration service on every pull request to master branch.
  3. Document the decisions and solution.

Remember that implementing short-term vision is responsibility of the whole team. As soon as you finish, present it to your team and emphasise how important it is. Then you can delegate some of the work to your collies. That's it, well done!

## **4. Set a 1-on-1 with your manager**

If you asked me what are the most important meetings in a startup, I'd say a short daily catch-up meeting with the team and 1-on-1 with your manager. These are the meetings you simply cannot skip. Period.

Don't wait for 1-on-1 meeting to appear in your calendar on your behalf. Be proactive and set it yourself.

There are four things I strongly recommend you to adapt:

### **Make the purpose of the meeting clear**

While it's responsibility of the manager to do so, you should remember about this step nevertheless.

### **Make a shared doc**

You might have realised by now that I'm a fan of writing things down. But it's not just a whim. You simply won't be able to remember everything between the meetings. Having a shared doc is a great reference to go through and summarise "what we talked about last week".

### **Make it regular**

Make sure there's an invitation in the calendar. Link the shared doc in the description of the meeting add description about the clear purpose of the meeting. How regular should it be? It depends --- for instance my manager and I do it weekly.

### **Show your work**

Before each meeting, list down things that you are currently focused on.

Here's an example of structure that I always fill in the doc:

  1. _Personal things_ --- my updates, i.e what I'm happy or sad about, any questions or comments
  2. _Done things_ --- what I've achieved the previous week
  3. _Ongoing things_ --- what I'm working on at the moment. Good place to highlight obstacles, delays or anything that goes not as planned
  4. _Next things_ --- what I'm planning to focus on in the next week
  5. _Manager's updates_ --- placeholder for my manager's updates

One important advice here: always try to start the meeting by asking how you're doing or talking about what happened to you last weekend. It's a small-talk and some people may not be as good at it (I'm not) but believe me --- this helps to break even the toughest ice. Especially useful if you have something serious to discuss later on.

And remember, this is a meeting for you and it's you who should be talking the most. If your manager talks more than you --- something is not right.

If you want to know more about 1-on-1, <a href="http://theengineeringmanager.com/management-101/121s/" rel="nofollow">here's an in-depth article from manager's perspective</a>.

## **5. Hang out with the team**

Last but not least, **say yes to everything that's social**. Whether it's a team lunch or beer after work --- go for it. Even if it distracts you from planned work.

You can go one step further and instead of waiting for invitation --- make one. People are keen to get to know you, but by staying in their comfort zones they're not always the first ones to reach out to you.

Why socialising is so important in the first week? It's because getting connected with the team and working on relationships as soon as possible will pay off sooner than you think.

So if you're asked to go out with the team, don't find an excuse because you prefer to stay alone. Say yes and use this opportunity to learn something about your collies, whether it's related to work or their personal life.

If it comes to me --- I'm an introvert. But at work I always push myself to talk to people and socialise. Not only because I want to get to know my teammates better, but also because it positively affects our teamwork.

Finally, having good relationships makes you more influential. And influence is what you should aim for when you're a leader.

* * *

And that's it! To sum up, here we are with 5 things for 5 days of the first week as QA Lead:

  1. Get the baseline
  2. Assess the risks
  3. Set short-term vision
  4. Set 1-on-1 with your manager
  5. Hang out with the team

In the next article of the series, you can read about [the 6 pieces of advice for first month as QA Lead in a startup]({{ site.baseurl }}/blog/first-month-as-qa-lead-in-a-startup/).
