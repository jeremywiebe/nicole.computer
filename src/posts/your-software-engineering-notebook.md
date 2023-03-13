---
title: Your Software Engineering Notebook
date: 2023-02-14
tags:
  - blog
---

As an engineer one of the most important jobs we do is manage knowledge. During an ordindary day I meet with folks, work on features, deepen my understanding of the codebase and our learner's needs, and have ideas for where I'd like things to go technical and otherwise. The thing is, without a conscious effort all of this knowledge can slip through our fingers.

Have you ever been asked by coworker, "Hey I was working on some code and saw you changed it 3 months ago. Can you bring me up to speed?" or been asked at the end of a review-cycle to evaluate your own work or had to pull together all of your thoughts on a library you've been using for several months? An egnineering notebook gives all of this knowledge a place to live.

I've kept an engineering notebook for over a decade. It's been sometimes paper, sometimes text files, and sometimes kept within in app- but the core of the notebook is always the same- a place for my day to be structured, my mind to play with ideas, and a record of what I've worked on.

## What is an engineering notebook?

An engineering notebook is where you keep track track of the heartbeat of work. It's a daily practice of writing things down. There's a notebook company, Field Notes, who's slogan is
"I'm not writing this down to remember later, I'm writing this down to remember now". That your engineering notebook. You're writing things down now to keep you focused, on task, and thinking about the bigger picture. Here's the basics of what you'd like to capture:

- What's happening today? What do I need to do?
- What's on my mind? What am I thinking about? What questions do I have?
- What did I learn today?
- What did I accomplish today?

The easiest way I think to get started is to keep a directory of files with the format `YYYY-MM-DD`. I like to use markdown so a simple daily page might look like:

```
# January 6, 2023

## Goals for today

## Notes

## End of day
```

It can be tempting to make this a tooling exercise and spend months bikeshedding on the right tool. To get started, though, I want to encourage you to keep everything in plaintext, in a folder, and use an editor that you already know. You should backup the journal, using git or using a file syncing service. As you use your notebook more and more you will start to find the things that work for you. Maybe you find you'll need a section for tracking performance. Or you might find that you want a calendar list. Or maybe you want to practice seeing the good work your coworkers are doing and have a section for teammate wins. Your notebook will be unique to you and the way you work. With that said, here's a look at how I structure mine.

## Good Morning, world!

I start my day with a boot-up process. I open a new markdown document for the day. Then, I take a look at my calendar for the day and copy the list of events for the day into my notebook (`icalbuddy` is a wonderful little utility for interacting with iCal and I pipe it's output to `pbcopy` so I can move the event list right into my note.)

Then I list out my goals for the day. I'll scan through Jira to see what's on my radar and copy a list of ticket names and links into my notebook. This todo list is my source of things-I-need-to-do for the day. If I'm in a meeting and someone asks me, "Hey, can you read this document?" I put it onto my todo list for the day. As I fill out my list for the day it's also a good time to pop open yesterday's note and copy over anything from the previous day that's still on my radar.

## Core Work

I work in timed-blocks to get through my work (usually 45 minutes). For every task that I work on I'll put a header under the notes section. So if I grab a ticket to "adjust line numbers in the passage widget" then there will be a section for that in my notebook.

As I work I'll write down anything I notice about the codebase. I find a lot of my work branches and there might be multiple ways to solve something so I try to write quick notes on each of the possible approaches and then why I chose the one that I did. This discipline of arguing out different approaches helps me sharpen my thinking about the why of what I'm doing.

While I'm working I often notice things that aren't related to the task but I'd like to fix. For example while working in a node project I noticed that `yarn start` didn't do anything and I wished that it started the testing server. Rather than break my workflow I pop that into my notebook as something that I'd like to address later. By writing it down I let my mind stay on the task at hand and I'm confident it won't be forgotten. (And for yarn start, it wasn't, I fixed up the issue right after finishing the task I was on).

## Shutdown

At the end of my day I write up a summary section of what I accomplished for that day. I often, but not always, share this with my team so that they can have visibility into how I spent my time and what I'm thinking about. Sharing this summary also gives a searchable record of the things that I worked on so that it's easier for others to find context around my work.

## Your engineering notebook

I hope you'll keep a notebook. It's the best ways I know to stay focused and retain context of what you're working on day to do. It'll make you a better writer, a better communicator, and a better engineer.
