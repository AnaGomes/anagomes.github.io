---
layout: post
title: 101 Software Development
---

In a common developers world, where features always seems to come first, concerns like code quality, performance, optimization or security are easily forgotten. Pace becomes more and more important, regardless of the future cost it might obligate.

### Nowadays
However, once someone taught me that 90% of a software creation is all about maintaince and only 10% it's the actual development. Taking this into account I would like to hightlight some key points that might be a life saviour on the long run:

- **Crystal clear tasks:** both the description and the acceptance criteria should be well defined. Imagine that you have a bunch of customer data with elements like name, phone number, address, id number, birthday date, etc. Someone asks you a user-friendly way of presenting this data in your website. Without any further instructions, you can do a straight dump of the data to a table ordered by name. You think "Job done!" until the moment that you're told that what is actually needed is a phonebook-like interface with name, cell and address ordereding. (... missing something on this)

- **Documentation:** neither too much nor too little of it. It should be enough to give another person the context of the main purpose of that method, class, or project. If you feel that you to have to write a whole paragraph just to explain a simple function perhaps you should review the code itself first. 

> Debugging is twice as hard as writing the code in the first place. Therefore, if you write the code as cleverly 
> as possible, you are, by definition, not smart enough to debug it.
> Brian W. Kernighan

- **Optimize, optimize, optimize:** i like to think of developing like painting or writing a story. It's a never ending work. Either by adding more features some time or just by the need to improve performance because one day a bunch of customers all the suddenly appeared. I was just remembering about the spike of Pokemon Go. The developers though that had a finished work until they realized the success, servers crashing and lots of bugs found. But don't freak out right away. There is always a solution - perhaps a pattern might help you on this?.

- **Refactor:** this one follows the concept of the last bullet point. You did a simple code that perfectly works for the scenario you had. But all the sudden you acknowledged a whole country of new customers that are now asking for that unique feature that would fit perfectly in your project. And it is when you look at it that you see: that PoC database system no longer suits your needs neither do the way that you access the API for geolocation, e.g. Now is the time... for Refactor. Take advantage of the control version to help on this if something goes wrong and go for it. Adapt. Be a chameleon.

- **Security measures:** so, you did all the other items and you feel great until someone gets in there and destroys it. Newer frameworks and versions of languages begin to have basic protection against the clear text login or XML External Entity injection.

Last but no least remember: even a master has something to learn. Don't ever forget to sometimes go into the wild and get something. 
<sup><sub>(I know sometimes it gets you some bruises in the run but in the end, the feeling is great, isn't it? ;) )</sub></sup> 




