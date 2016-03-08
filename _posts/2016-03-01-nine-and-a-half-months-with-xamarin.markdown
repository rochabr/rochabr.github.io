---
layout: post
title:  "9 1/2 months with Xamarin"
date:   2016-03-08 6:28:00
categories: developer xamarin
comments: yes
---
On January 3rd I got a call from my current boss, I was still living in the wonderful land of Rio de Janeiro and I was eager to get out of there as soon as possible so you can imagine my excitement when he called me to discuss an opportunity in the US. They needed someone that was already working in the company for a while and had a strong mobile development background (check and check). We went through his ideas, I gave my two cents and somewhere, in the middle of our conversation, I asked about if we were going to use Objective-C and Java for iOS and Android development.

He told me that we would be using Xamarin, a cross development mobile development platform.

 "What the hell is Xamarin?" was my first thought, because, to be honest, I've tried many cross development tools for mobile development before and they were all not worth the cost or the time. Titanium, Phone Gap, Corona; they all worked, but the results were not good.

The idea of cross platform development is great, in my opinion. Develop for all platforms, code faster and keep the quality of your work. Sounds awesome. Easier said than done, though. So, I was sad at first, because I was excited to show off my Objective-C skills and teach the new team how cool it is. But it was just a minor bump in the way of my happiness.

Fast forward 6 months and I'm in the US, I have a desk and a MacBook Pro 15", top of the line. I also have Xamarin Studio installed and I'm willing to learn what this tool is all about. I've read some good reviews and some really bad ones. So, my first thought was: it is not that great, but it has value. 

So, I have started and, 9 months later I’ve been asking myself: should people use it? The answer is disappointing: It depends.

Let me provide a little pro/con list, to make it easier to understand:

Cons

-	Xamarin is expensive. Licenses, training, certification, events. They are all way out of you regular developer price range.
-	The "Write once, run anywhere" motto is a myth, unless you are looking at a very simple app. Once you get a little bit dependent of the OS, you have to start building two or three different applications. 
-	The development process is slow compared to Objective-C (iOS) and Java (Android). Building screens and positioning components is not that easy, specially when you have complex UI elements.
-	The learning curve is something to think about. The idea of "Am I doing the right thing?" is constant and disturbing.
-	The big guys aren't using it. Facebook, Google, Amazon, Evernote, Booking: they are going with real native. So don't expect to see cool frameworks like [Pop][pop-url] on Xamarin, unless you build them yourself or wait for someone to do it for you.
-	Help online is scarce and it always comes from the same guys, who are very good, nonetheless.
-	You end up depending a lot on third party libs to make your job easier and, although some of them are reliable, you can never be sure that John Smith or Jane Doe will keep updating his/her libs.
-	Experts are rare and usually expensive. Don't get fooled by certified developers. There is a big difference in being a Xamarin Certified Developer and being a real badass black belt Xamarin developer.
-	Windows Phone apps can only be developed using Visual Studio on a Windows environment.
-	Debugging applications for Android is one of the most painful things I've ever suffered professionally. The connection with the debugger doesn’t stand, for some crazy reason and the message below is very common.

![Error debug message](http://fernandorocha.io/images/debuggerandroid.png)

-	Also, this compiler issue comes and goes:

![Error compiler](http://fernandorocha.io/images/compilerissues.png)

Pros

-	Xamarin works. It takes time, it is not always pretty, but it works. We are able to deliver quality products in the end of our development cycles.
-	You can share at least 20% of your code between platforms. If you make an effort, you can get to 90%, using Xamarin Forms, but it's not worth it, in most of the cases. Even Xamarin suggests that this technology is not for every app.
-	C# is a powerful and an easy language to learn. You can do a lot with C#. The design patterns work well and you have a ton of test frameworks.
-	Xamarin university is REALLY good. I can't say this enough. It's probably one of the best online classes I've ever seen in my life.
-	Xamarin is perfect for quick mockups and tiny MVPs, where you are not trying to make things very pretty, but trying to give an idea of how your app you behave in Android and iOS.
-	Xamarin is expanding. Microsoft just bought it and I hope to see some of their executives at [Xamarin Evolve][evolve-url], this year.
-	As iOS native development, you need a Mac to compile the app. The good thing is that you'll only need one, since you can use Visual Studio for the development.

At the end, all I can say is: you should use Xamarin if:
-	Your team is strong with C# and have zero experience with mobile development in other platforms.
-	You have money to spend.
-	If you really want to write one code for all platforms, you should design simple interfaces.
-	You are willing to bet that the development platform will become better in the future.

These are my thoughts about this technology. Personally, I’ll continue doing my personal projects with the beautiful and always reliable Xcode.


[pop-url]: https://github.com/facebook/pop
[evolve-url]: https://evolve.xamarin.com/

