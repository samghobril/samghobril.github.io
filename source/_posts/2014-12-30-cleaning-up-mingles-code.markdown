---
layout: post
title: "Cleaning Up Mingle's Code"
date: 2014-05-24
comments: true
categories: 
---
While working on Mingle’s 1.1 update, I’m noticing that some of its code is really cluttered. Some parts feel like they’re being held together by duct tape, and some other parts are just abnormally massive. This is because I learned a lot of stuff while working on Mingle. So before continuing work on the update, I’m going to work on cleaning up Mingle’s code.

<!-- more -->

I found this year-old [article from objc.io](http://www.objc.io/issue-1/lighter-view-controllers.html) called Lighter View Controllers, and it looks like a great starting point. I love this piece of advice:

> One of the most powerful techniques to slim down your view controller is to take the UITableViewDataSource part of your code, and move it to its own class. If you do this more than once, you will start to see patterns and create reusable classes for this.

I’d never thought about these kinds of things before. I’d always focus on getting a feature working, then moving on to the next one. The structure of the code was getting worse and worse, and I barely, if ever, took notice.

In order to make my work more enjoyable, I’m taking some time to clean things up. When things seem polished and clear, every problem will appear easier to solve.

It’s the equivalent of cleaning up my desk before studying. I’m glad I’m doing this.