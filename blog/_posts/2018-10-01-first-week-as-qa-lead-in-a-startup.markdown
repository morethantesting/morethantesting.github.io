---
layout: post
custom_css: blog/blog.css

title: "First week as a QA Lead in a startup — 5 steps for 5 working days"
description: "Read more to learn 5 steps that you should do in the first week as a QA Lead in a startup, including real examples and practical advice."
excerpt: "In this article, I talk about 5 steps that you should do in the first week as a QA Lead in a startup, based on real examples of how I've actually done it."
date: 2018-10-01T13:34:57+00:00

image: /blog/assets/first-week-as-qa-lead-in-a-startup.jpg
alt: "Lego trooper standing under a tree with a weapon"

read_time: 8
redirect_from:
  - "/first-week-as-qa-lead-in-a-startup"
  - "/first-week-as-qa-lead-in-a-startup/"
  - "/first-week-as-qa-lead-in-a-startup/amp/"
---

_This article is the third part out of five articles about [joining a startup as a QA Lead]({{ site.baseurl }}/blog/joining-a-startup-as-qa-lead/). You can read the previous part about [the 3 things I wish I knew on the first day in a new job]({{ site.baseurl }}/blog/first-day-as-qa-lead/)._

* * *

In this article, I will tell you about the first week as a QA Lead in a startup. We'll start getting more into QA-specific details now.

So, one week. Five working days. Doesn't sound like a lot, does it? But don't get fooled. It turns out these are very, very important five days.

Why? Because this is the time when you can make a great impact. Time, when you define what you and the team are going to focus on in the near future.

Look at it this way --- in the first week, you're free. You're fresh and you see things from a different perspective. That means it's a perfect time for you to pay attention to what's happening around and plan your future work.

So what should you do in the first week? Here are 5 steps that I recommend.

## **1. Get the baseline**

First of all, you should find out what the current status of the QA process among all products and projects is --- **the baseline**.

Note that **it is the most important task** in the first week. Both the short-term and long-term decisions will be based on the outcome of this challenge. Thanks to this, you'll not only see where you stand, but it'll also help you prioritise the most important things.

These three steps that will help you get the baseline:

### **Talk to people**

Firstly, talk to the _engineering manager_ --- he has the best high-level overview of what the biggest pains are.

Then talk to the _engineers_ from all areas: front-end, mobile, back-end, hardware. They will give you a fresh update on how it really is.

Finally, talk to the _product managers_. Talk about how you see your collaboration. That's because as a QA Lead you'll work with them way more than with anyone else.

Here's a bunch of questions that you may find helpful during your investigation:

  * what has been working well so far?
  * what are the biggest pains you can see?
  * how would you fix them?
  * what does slow down your work the most?
  * what are users struggling with?

Frankly, when I first talked to engineers asking them these questions, I was surprised by the responses. As we spoke, they not only recognised what we could improve but they also provided ideas on how we could do it. And me? I was just asking questions, listening to answers and writing the problems down. And the solutions started emerging alongside.

### **Observe**

Once you have an insight into the current process, start observing how everything works.

Compare what you see to what you've seen in your previous companies. Take advantage of the unbiased, fresh point of view and objectively assess the situation:

  * is the project management process simplified?
  * are the requirements well-defined?
  * is team communication efficient?
  * is the testing culture embedded in the team?

Next, get access to the analytics tools where data is stored. Learn how customers use the service or product and include it in your reports.

And remember --- it's not only the quality of the product and service you'll be taking care of but also the quality of teamwork and communication within the team.

### **Write it all down --- and show it**

Last but not least, gather all that knowledge in one place. Note everything down and share with the team.

There are two main reasons why you should do it:

  1. You show your work.
  2. Everyone is up to date with the current status.

By showing your work, you gain respect. It boosts everyone's confidence. At this stage, no one will doubt that you should be doing something else instead.

And bringing everyone on the same page will help you prioritise and focus on the right things. You will also be able to back up your decisions --- and no one will question that.

How did I do it? I presented it in the form of a status matrix listing all projects and matching them with QA factors that we wanted to improve. Also, it's cool to see how everything improves as you go.

Here's a status matrix I created for one of the startups that I worked for:

{% include image.html src="/blog/assets/qa-process-status.gif" alt="QA Status Matrix" %}

## **2. Assess the risks**

Now that you've done the research, it's time to figure out what to take care of first. Prioritisation is a challenge but here's where the risk assessment comes to the rescue.

There are two things you can leverage to help you with this task:

  1. Using data.
  2. Using your experience and QA gut feeling.

Using data is straightforward. Get it, analyse, make conclusions.

Note that by data I mean not only the baseline you've gathered from the team, but most importantly what you can get from users. Whether these are the outcomes of user testing or analytics data of the product.

Also, here's where you should use your experience and listen to your QA gut feeling. You have to trust yourself --- no one can do it better than you.

In my case, I used the following deduction method to find the most critical path:

  1. What is the most important thing for this early-stage startup? _Grow, make money and get customers._
  2. How does the startup can achieve that? _By selling a product to customers._
  3. How customers can buy the product? _Through the website and in-app._
  4. Do we test buying a product via the website and the app? _Sometimes, manually._
  5. **Conclusion:** _Let's automate end-to-end tests that cover customer's critical path in order to create a safety-net whenever we make any change to the product._

The quick takeaway from that is to think not only from a customer perspective but also from a business perspective. As a tester in a startup, you have to sometimes compromise on both.

## **3. Set a short-term vision**

Based on the baseline research and the risks assessment you've done, you're now ready to set a short-term vision.

I've mentioned before that getting the baseline is the most important task for the first week --- and I wasn't lying. But it's the short-term vision that will have the biggest impact in the near future.

What should be included?

  1. An attack plan for mitigating the biggest risks while focusing only on the priorities and the quick wins.
  2. Tasks in the project management system that can be accomplished within a month.

Some advice on that: **don't make it perfect, just make it right.**

What I'm trying to say is that you're not setting anything in stone here. Sure, you have to write down something, but treat it more like guidelines. I suggest you take an iterative approach: first you try, then you learn, then you adapt. This means the plan can be modified as you go --- and that's fine as long as you focus on the right things.

Note that in contrast to the long-term vision, in this short period you should be focused more on the results than on the process.

What I did was creating a phased attack plan for implementing end-to-end automated UI tests for both website and mobile platforms. It went as follows:

**Phase 1**

  1. Research website UI testing frameworks allowing to test on desktop and mobile Safari (which at the time was the most used browsers among our visitors).
  2. Set up the testing framework in the project's repository.
  3. Proof of concept: create the simplest test and run locally on Safari.

**Phase 2**

  1. Extend the test suite with the user's critical path of ordering a product.
  2. Make it run on a continuous integration platform on every pull request created to the master branch.
  3. Document the decisions and solution for reference.

Remember that implementing the short-term vision is the responsibility of the whole team. As soon as you finish, present it to your team and make sure you agree on that. Then you can delegate some tasks to your collies. That's it, well done!

## **4. Set a 1-on-1 with your manager**

If you asked me what the most important meetings in a startup are, I'd say a short daily catch-up meeting with the team and 1-on-1 with your manager. These are the meetings you simply cannot skip.

You don't have to wait for the 1-on-1 meeting to appear in your calendar on your behalf. Be proactive and set it yourself.

There are four things I strongly recommend you to adapt:

### **Make the purpose of the meeting clear**

While it's the responsibility of the manager to do so, you should remember about this step nevertheless.

### **Make a shared doc**

You might have realised by now that I'm a fan of writing things down. But it's not just a whim. With so many things going on, you simply won't remember everything between the meetings. Having a shared doc is a great reference to go through and summarise what you talked about previously.

### **Make it regular**

Make sure there's an invite in your calendar. Link the shared doc in the description of the meeting and point out the clear purpose of the meeting. How regular should it be? It depends on your needs. For instance, my manager and I do it weekly.

### **Show your work**

Again, this is a very important piece of your job --- to share what you do. So before each meeting, list down the things that you are currently focused on.

Here's an example of the structure that I always fill in the doc:

  1. _Personal things_ --- my updates, i.e what I'm happy or sad about, any questions or comments.
  2. _Done things_ --- what I've achieved in the previous week.
  3. _Ongoing things_ --- what I'm working on at the moment. A good place to highlight obstacles, delays or anything that doesn't go as planned.
  4. _Next things_ --- what I'm planning to focus on in the next week.
  5. _Manager's updates_ --- a placeholder for my manager's updates.

One important note: always try to start the meeting with some light but genuine small-talk. It can be as simple as asking: _how are you doing today?_.

I know many people don't like it --- and I'm not a fan too --- but this immensely helps to break even the toughest ice. Especially useful if you have something serious to discuss later on.

And remember, this is a meeting for you and it's you who should be talking the most. If your manager talks more than you --- something is not right there.

If you want to know more about 1-on-1, <a href="https://theengineeringmanager.com/management-101/121s/" rel="nofollow">here's an in-depth article from the manager's perspective</a>.

## **5. Hang out with the team**

Last but not least, **say yes to everything social**. Whether it's a team lunch or drinks after work --- go for it. Even if it distracts you from planned work.

You can go one step further and instead of waiting for an invitation --- make one. People want to get to know you but by staying in their comfort zones they're not always the first ones to reach out to you.

Why socialising is so important in the first week? Because getting connected with the team and working on relationships as soon as possible will pay off as soon as you need to collaborate with them. And you will, sooner than you think.

So if you're asked to go out with the team, don't find excuses just because you don't feel like going. Say yes and use this opportunity to learn something new about your collies, whether it's related to work or their personal life.

If it comes to me --- I'm an introvert. But at work, I always push myself to talk to people and socialise. Not only because I want to get to know my teammates better, but also because it positively affects our teamwork.

Finally, having good relationships makes you more influential. And influence is what you should aim for when you're a leader.

* * *

And that's it! To sum up, here we are with the 5 things for 5 days of the first week as a QA Lead:

  1. Get the baseline
  2. Assess the risks
  3. Set a short-term vision
  4. Set a 1-on-1 with your manager
  5. Hang out with the team

In the next article of the series, you can read about [6 pieces of advice for the first month as a QA Lead in a startup]({{ site.baseurl }}/blog/first-month-as-qa-lead-in-a-startup/).
