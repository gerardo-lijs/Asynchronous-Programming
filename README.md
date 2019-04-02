# Asynchronous Programming in .NET
Curated resource links I've collected while doing asynchronous programming in .NET. Some of them were very useful to me during my learning path and hopefully, they will help other software developers. Suggestions are welcome.

#### Videos
* [Six Essential Tips for Async by Lucian Wischik (2013)](https://channel9.msdn.com/Series/Three-Essential-Tips-for-Async)  
I usually prefer reading blogs or books rather than watching videos but in this case, they are absolutely worth in order to understand graphically the asynchronous program flow with await/async.

#### Blogs
* [Async Guidance by David Fowler](https://github.com/davidfowl/AspNetCoreDiagnosticScenarios/blob/master/AsyncGuidance.md)  
Provides excellent small code samples of good and bad patterns

* [Async Anti-Patterns by Mark Heath](https://markheath.net/post/async-antipatterns)  
Enumerates some of the most common mistakes you will probably find or even code yourself while doing Asynchronous programming.

* [Stephen Cleary](https://blog.stephencleary.com)  
Stephen Cleary is an expert in asynchronous programming since 2012. He has written many posts addressing many issues. Keep in mind TAP and TPL libraries changed a lot through the years so maybe you will find solutions for problems that are already solved in the framework.

* [Do not await what does not need to be awaited by Jiří Činčura](https://www.tabsoverspaces.com/233659-do-not-await-what-does-not-need-to-be-awaited)  
A detailed post explaining some specific cases where you can use Task without await. It doesn't really make a big difference but if you are able to understand the discussion it's probably a sign that you're on the right track with async!

#### Books
* [C# 7.0 in a Nutshell by Joseph and Ben Albahari](http://www.albahari.com/nutshell/)  
Chapter 14 - Concurrency and Asynchrony provides in depth knowledge of Threading/Tasks and Obsolete Patterns like APM, EAP, and BackgroundWorker

* [C# in Depth by Jon Skeet](https://csharpindepth.com/)  
Chapters 5 and 6 on asynchronous programming are very well explained and worth reading

#### Samples
* I'm currently preparing some small samples about practical uses of async/await in Desktop and Web Applications for a Meetup and will, later on, add them to this repository

#### Extras
* [Why your ASP.NET Core application won't scale (Feb 2019)](https://www.youtube.com/watch?v=J-xqz_ZM9Wg)  
David Fowler and Damian Edwards demonstrate the importance of correctly using async/await in ASP.NET Core
* [The promise of an async future awaits by Bill Wagner (Feb 2019)](https://www.youtube.com/watch?v=ghDS4_NFbcQ)  
Nice talk given in NDC London
