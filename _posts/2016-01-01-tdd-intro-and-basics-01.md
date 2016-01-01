---
layout: post
title: TDD (1) - Intro and basics!
description: "We will talk about TDD, BDD and why these things are so important on software development"
modified: 2015-11-10
tags: [tdd,bdd,codeception,phpunit,php]
image:
  feature: tdd.jpg
  credit: Infobase
  creditlink: http://de8xvdbdfow5f.cloudfront.net/wp-content/uploads/2015/01/tdd.jpg
---

(This is the first post of a series about the importance of TDD. Stay tuned for more!)


In the last few years acting as a software developer(!), I have seen a lot of programmers trying to solve problems on different ways. For my surprise, a very few knows something real about TDD.
Some say that TDD is a dream that they will never be reached - for many reasons - while others starts a rant and share how painful were their experience w/Testing Driven Development.
In my humble opinion, TDD is not only a fancy way of programming. It must be treated as a new culture, a more-effective way of writing rock-solid code. For many reasons:


TDD is a important step on way to Continous Integration
---
A few months ago a lot of people asked me something about how to implement an effective CI stategy (*yeah, I consider CI as a strategy. I`ll talk a little more about this later*). But none of them works on unit testing.
So what will happen if you use CI on an 'untested' environment? Big trouble, bigger headaches and a feeling that Continuous Integration is a pile of garbage and a "php-hipster" jargon.



Testing your code before deployment gives you less problems
---
Oh, dear... Problems. Please raise your hand if you got any problems when putting that new feature on production environment. I got plenty of them, specially with untested code.
But when I started using TDD, my life has changed. Now - sometimes - I have problem more with bad infrastructure, sysadmin rant, the 'zealot' DBA than my feature.
Not because I'm pretending to be a "superhero software architech" (*I'll never get this title, rest assured*), but you got more confident of your code.

You are stamping a quality seal on your code
---
Yeah, you heard it: you start to look at your features differently. You start to take care of it, and do a great effort to pass on testing. This way of thinking - or looking at your code - is an important step to assure quality of your code.
This remembers me those 'quality seals' that we found in brand new -and some old - cars in Brazil.

![](/images/volkswagen-adesivo-selo-qualidade-ok-parabrisa-inspeco-zero-13110-MLB20073101354_042014-F.jpg)


So when your feature pass all tests, you are stamping on it a 'quality seal' which allows others to look differently at your code.


TDD urges you to build simple code (KISS)
---
Keep it simple, stupid. Keep your brand-new API as simple as possible. Keep that new feature so simple that anyone who looks at the source could maintain it without thousands of documentation pages.
Keep your code nice and clean, so your experience with TDD will be so much better. This could be nonsense, but don't worry, you'l see.




But before you starting, you must keep in mind that:
---

###TDD is a 'new' way of getting things done
A new 'paradigm', a new way of getting your code run as expected.

###At the beginning could be more frustrating than you thought, but don't give up!
It will be hard. They'll kick you, then they beat you, then they'll tell you it's fair. But don't beat it, because at the the end you will see that's really fair.

###It's not a immediate change
Things don't change overnight and you sometimes will be caught deploying stuff without proper testing coverage. But as I said before, don't give up. Keep going until you get the good habit.

I must confess that I'm new on the TDD world and I haven't figured out a way to test old-legacy codes without so bloddy effort and huge refactoring. But all of my coding since them is getting TDD.

But I promise you that I'll share with you some thoughts, pitfals and study cases about this wonderful practice. We will discuss later.

Oh, and practice comes to perfection, keep in mind!


*References*

[Working Effectively with Legacy Code](http://www.amazon.com/dp/0131177052/)

[Refactor Low Hanging Fruit](http://c2.com/cgi/wiki?RefactorLowHangingFruit)

[Art of Unit Testing](http://artofunittesting.com/)