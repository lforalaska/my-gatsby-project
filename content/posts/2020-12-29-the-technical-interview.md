---
template: post
title: Tech Industry Interviews
slug: tech-industry-interviews
socialImage: /media/410hiapgycl._sx348_bo1-204-203-200_.jpg
draft: false
date: 2020-12-28T23:58:57.266Z
description: "An overview of the tech industry and common interviewing methodologies. "
category: advice
tags:
  - industry
  - interviewing
---
You've seen the book probably. 

![Cracking the coding interview by Gayle Laakmaan McDowell](/media/410hiapgycl._sx348_bo1-204-203-200_.jpg "The most infamous interviewing prep book")

At the same thickness as your college calculus textbook, it elicits usually the same amount of joy from the reader. If you have not had the pleasure yet, this book is undoubtedly one of the top resources available. The first few chapters summarize the industry and interviewing process. I'll give the spoilers here.

## Industry Overview

There's a common acronym used to describe the "top" big tech companies: FAANG. Sometimes FANG, sometimes FAANMG. It's usually some combination of Facebook, Apple, Amazon, Netflix, Google, and Microsoft. These companies are amongst the highest paying and their name on your resume is considered a golden stamp of approval in most circles. Along with the FAANG, there are companies at the similar compensation scale that most tech circles hold in high esteem, even if your grandparents have never heard of them. These companies include Stripe, Uber/Lyft, AirBnB, and ByteDance (TikTok). To see an overview of compensation of these companies, check out[](https://www.levels.fyi/2020/?ref=top_bar_banner) [levels.fyi](https://www.levels.fyi/2020/?ref=top_bar_banner). Getting an interview at one of these companies is best done through an internal referral as they receive thousands of outside applications for each posting. 

Usually the next "tier" of tech companies are the hot startups. Startups that recently raised a Series C and are growing rapidly. None of your family members have probably heard of them, but you'll likely get to do a greater variety of things than at the bigger companies. Many of these positions are also fully remote. They probably offer sizable equity and less base salary, though more and more companies are becoming flexible on how you'd like to be paid. A handful of these companies will IPO and could generate incredible wealth for early employees. At these companies, the interviewing process will most likely emulate the FAANG-style ones, but with less formality. At this stage, a referral is also worth a lot more since there are less employees. 

Then there's every other tech company. Some of these are extremely early stage startups where you'd be an engineer, but also a designer and customer support. Your base pay is likely very small and your stock options are sizable (and risky). The interviewing process is very informal. Most likely you just know one of the cofounders. The interview process may be more of a selling point where they're just trying to convince you to join. Other companies are long established public companies that are in "maintenance" mode. You'd learn a few things, but most of the employees tend to be just waiting out their days until retirement. Work life balance is usually good and the pay is decent. The interviewing process can vary dramatically. They may do something similar to FAANG style, they may do take home assignments, they may use a third party assessment tool. 

## The Interviewing Process

At FAANG style companies, you can pretty much count on this exact sequence:

1. Recruiter phone screen. A recruiter calls you to make sure the details on your resume are correct. This is a short 15-30 min phone call and will be completely non-technical.
2. Technical phone screen. An engineer calls you to solve a problem over the phone or Zoom. You usually have an hour to solve 1-2 problems. The difficulty level depends on the company. Some companies also replace this step with a third party assessment tool such as HackerRank.
3. Onsite interview. During COVID, this is just a very very long Zoom call, about 4-5 hours is common. You'll likely to 2-3 coding interviews, a behavioral interview, and a systems design interview. More details on this in the next section.

At smaller companies, you might receive a take home assignment in place of a technical phone screen or in place of the onsite. The take home assignment is usually a "real business problem" application and they ask you to do as much as you can in 2-4 hours.

## The Coding Interview

Before COVID, the coding interview was also called a whiteboard interview. So called because you would "code" on a whiteboard, meaning there was no way to run your program. You'd have to write it out with a marker or pen in front of another engineer. I remember when I first heard about this process. I was a senior in college and I threw the book across the classroom upon reading that. If you are frustrated or appalled ("that's now how you code in real life though!"), trust me you are not alone. There's little sign to show this will change any time soon, so at the very least I can try to prepare you for it. 

Now during COVID, the coding interview happens via an online text editor while someone sits on a Zoom/phone call with you. Sometimes it's Google Docs, other times it's more specific software such as CoderPad. In some cases, companies will let you actually run your code. You should assume you *cannot* let the computer run your code. Meaning, you will need to verify and debug your code manually. 

> I feel the need to warn you at this point because I've had a few people ask-- "Wait if everything is online now, why can't I just look up the problem during the interview?". On morale principle, cheating is never good. But I will also warn you at this point that there are built-in tools that attempt to detect cheating. Most editing software will show when you have navigated away from the window, even if it's not a tab switch. Your interview can most likely hear you type and if they don't see anything, that could be a warning sign. Moreover, even if you were to find the answer immediately, you'd have to explain how you solved the problem to the interviewer. Good interviewers will push your understanding or extend the application. To the experienced interviewer, it is obvious when someone has looked up the problem without truly understanding it. 

Okay so now that we agree cheating is not the answer, your next step is to prepare. You should know all basic data structures such as arrays, dictionaries, linked lists, queues, stacks, and trees. For algorithms, you should know the run time and space complexity of sorts and merges. Depending on the company, some types of questions are more popular than others. I highly recommend purchasing [Leetcode Premium](https://leetcode.com/subscribe/?ref=lp_pl) if you are interviewing at a FAANG because they have curated problems by company. For example, Facebook is notorious for asking graph theory problems (during my interview, I was asked 2 binary search tree problems). 

If you've never heard of some of the data structures in the previous paragraph, this is your cue to go learn them first. At my first technical interview, I was asked a question about a linked list and I had never even heard of that data structure before. You can imagine the sweats I had in that moment. Save yourself now and watch some YouTube videos. HackerRank produces content on all the basic data structures and there's many YouTubers these days that do walkthroughs of popular interviewing questions. 

If you have heard of those data structures, but it's been awhile, make sure you practice!

![Comic strip about practice](/media/e0b.jpg "Practice??")

Yes, practice. I understand the frustration many college students and even seasoned industry professionals have about these "leetcode" problems. "But you'll never use this in real life!!". On some level, that's true. I've never been asked to invert a binary search tree or implement a recursion solution on the job. The industry hiring methodology is about minimizing false positives even at the risk of high false negatives. There are undoubtedly talented engineers who are rejected by this arcane practice, but I would also say I have never met a bad engineer at my job. 

When you do practice, make sure you practice explaining your thoughts out loud. There should be no confusion about what your code does. This means there will be significant talking before any code is written. Here is an example interview answer for the popular question [Verifying an Alien Dictionary](https://leetcode.com/problems/verifying-an-alien-dictionary/):

1. State the problem and goal

> Okay so after reading the question, my goal is to write a function that returns true/false for whether the array "words" is sorted in a given lexicographical order.

2. State the brute force solution

> The brute force solution would be to compare each letter in each word to every letter in every word that comes after it, returning false if any of the pairs don't satisfy the lexicographical order. This would run in O(letters squared)*O(words squared).

3. State the better solution

> One way we can cut down the runtime would be to compare each letter of each word only to the word immediately following. This limits our traversal of the same letters, resulting in a runtime of O(letters*words). 

4. Pseudocode the better solution and talk through what you're thinking, such as:

> I'll need to convert the lexicographical string to a dictionary because I'll have to perform a lot of lookups. Look ups using a dictionary is O(1) time. 

5. Code

6. Debug manually

> Let's use the example array and step through the code line by line

Other things to keep in mind:

1. Don't be afraid of asking questions if there's any confusion.

> Is the string order always 26 characters? 

2. Check in with your interviewer periodically.

> Do you have any questions about my solution?

## The Behavioral Interview

This is probably the interview you are most accustomed to. 

"What are your greatest strengths and weaknesses?"

 "Tell me about a time you failed and learned."

 These questions are trying to dig at whether you are someone who aligns with company values. Most companies post their [values on their website](https://www.facebook.com/careers/facebook-life/) and you should definitely read them beforehand and think about how they apply to you. 

Similar to the coding interview, it is important to practice this part. People often chuff at practicing the behavioral interview because they want to "sound authentic". Don't fall into this trap. Thinking about your narrative and how you align with specific values is an important exercise. It will not make you sound fake, it will make you sound *prepared*. Write out full answers to these common questions and practice saying them out loud until you have it memorized. 

At some companies, the behavioral interview can save you from a poor performance on the technical. 

## The Systems Design Interview

For most new grads, this interview will be like pulling teeth. The questions will be something like: 

"Design a news feed API."

"Design a URL shortener."

"Design YouTube." 

If you have not worked in industry before, these questions are nearly impossible. Fear not, this interview also tends to count the least for new grads. This question only becomes highly weighted in senior and above positions. 

If you are short on time, this is the question I recommend skipping preparation. Instead, I will offer you the practical advice of what to do when you don't know the answer. First, admit that you do not know the answer. Then, try to figure out the answer. Try not to guess or throw out buzzwords. State your assumptions and your goal. Engage with the interviewer for hints. Interviewers do not want to see you struggle (much as you might feel differently). Interviewers want to see you shine at your best, so engage them in your learning process. 

## Overall

If you walk away from this article with anything in mind, I hope it is **practice**. Ask your friends to mock interview you. Set a timer for yourself and do interview problems. When you don't know the answer, learn it. When you do know the answer, extend it.