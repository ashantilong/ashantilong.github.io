# HW0
<p>My is Ashanti Long and I am a junior at the College of Chareston. I getting my Bachelor of Science in Computer Science and Math</p>


# Reflections on FOSS

<div style = "color:red">
    
 The Catheral and and the Bazzar starts off very  well I think. In the beginning it gives a detailed summary of the development of the Linux operating software. The concept of open source development has two methods: the Cathedral method, where a large coporation hires alot of programmers to develop software, they want to  keeps the source code secret, and charges large amounts to recoup it costs, not from the original product development, but from the expected legacy problems, technical support, bug fixing, software updates, etc. And then we have the bazaar method, which is the main focus of our class which  encourages open source software. Open source software encourages a programmer or team such as ourself  within the  community to gain the nesscary power to  maintain and lift  the software to keep it relevant. Per the authtor if things continue the way they are the Cathedral method will not be able to compete with the Bazaar method. In the Cathedral method the programmers must be hired and bought, the bazaar method the hackers are like magnets they are attracted to a problem, become more dedicated in fixing the problem for knowldge and practice , revisions and bugs are handled at internet speed. The author contnue to talka  out how many company business model has adopted the open source devleopment method(bazaar). As you read further into the book the auther  explains the hacker ethic and communtiy and how everything works. It was cool to understand the meaning of"hacker" v.s. "cracker" and the true meaning of free software. The author say in the future  that open source software will make deep in-roads into the Fortune-500 companies. That their investmeent in thier hardware and investment being dependent on one software company to make changes is stupid.  Open source software would provide a proliferation of hacker communities willing to constantly update older software. The author appears to know his stuff and progressively throughout the book the author lets it leak out that he is one of the hacker community and is a player/spokesman in this software battle I found this book a real eye-opener, can Microsoft's workforce continue to support software like Windows 2000 with 60 million lines of code, as opposed to Linux taking advantage of a worldwide army of hackers reporting bugs, writing patches, and keeping hardware drivers updated. Time will tell. Then after reading the book me and my team got together and tried to figure out our own open source to work on. We met up on zoom and was kind of overwhelemed just by the many possablities out there that we could choose from. Like how do we narrow it down to three choice and how do we chose one to work on. So we asked ourselves three question : how active is the open source, is there devlopment zone and contribution very detailed and documented on how to make contrubtion and how many issue they post and our these possible issue we can fix. By doing that we limited choose to some we like for example : zulip and mifos . These project had excellent documentation on how to contribute and what ways one person can contribute and it was in programs we liked.
 
</div>


# "Reflections on Open Source in Today's World"
<div style = "color:red">

I read an article about an infuential sercurity devloper named Michael Boelen. He is very active in computer security. He is the author of the popular open source security tools Rootkit Hunter (rkhunter) and Lynis, and he blogs about Linux security on Linux Audit and evaluates security tools on Linux Security Expert. He also formed a company named CISOfy around the Lynis tool to help organizations with security audits of multiple operating systems. Having used Lynis, I was eager to learn more about Michael to learn about his views on Linux, security, and open source software. The following interview has been edited for clarity and conciseness. Micheal talked about how open source is a way to express creativity in software while solving a problem. With the right license, it allows almost anyone to use the software, typically for free. That is also important, as not everyone has the luxury to pay for software or related services. The Dutch are known to be humble, outspoken, and in love with things being "gratis." This word is the same in Latin and means "for thanks" or "for nothing." While the F in FOSS does not refer to this type of free, He  believe it is a powerful driver to bring the software into more people's hands. That is valuable in itself, as it can open the gates to more feedback, ideas, or even code improvements. His  real start with open source was in 2003 with rkhunter. He did not have enough shell scripting experience to help the chkrootkit project when he found it showed several false positives on a FreeBSD system. Instead, he decided it was a great opportunity to learn shell scripting and, at the same time, build a useful tool. As a bonus challenge, I thought it was a good idea to make it POSIX compatible. This way, it could run on Linux, but also on BSD, Solaris, and others. After view year he devloped Lynis  In 2007, while being between two jobs for a month, he talked about how he  wanted to start a new project that helped him in his own job of improving security aspects of Linux and Unix-based systems. Existing tooling seemed to be outdated, so basically he wanted a fresh start. There are many security tools available. I'm reviewing many of them as part of the Linux Security Expert project. After looking at hundreds of tools, hE founded that Lynis has something that many of them don't have. The difference is "simplicity," or making the tool as easy to use as possible. From this experience, I can also share that it is really hard to make a tool simple to use. When it comes to promoting Lynis, I try to diversify things. Sometimes it is writing about it in a blog post or speaking at a conference. At the same time, the value of the tool itself does the real promotion. People tend to share the tool with others because they like it. He talked about how he strongly believe in the value of promotion. It shows your creation to more people, resulting in increased usage and suggestions. So, if you are a tool author, don't skip this part. Lastly he talked abut if you want to get into security then he would suggest implementing security measures on your personal systems or any test devices that you have available. If you don't know where to start, then Lynis might be a good inspiration for what can be done when it comes to Linux security. You also mentioned the Linux Audit blog, which might help readers get more familiar with the subject.
</div>


# "This bugs me"

## EX. 6.4 Find the oldest bug that’s still open in your chosen project. Write a blog entry describing the problem, with a theory about why the bug hasn’t been resolved yet. (Bonus points if you can actually resolve the bug.)
<div style = "color:red">
The oldest open issue I found on the issue without having a PR  was around September 26th 2015. It was labeled as " Installation script breaks other site". They gave it issue #39 sos it was easily to detirmine that this could of been a problem since buliding the project . The issue is based on configurating  files and some backend devlopnment which I really do know much about . Basically some override configuration files was happening when zulip was being installed. This problem was put on the back burner and the README was updated but in 2016 another user requested the issue be reponed because it was still breaking certain installations.

Over time label were added and removed so zulip community would take notice; howvere, it has only been recently gained activity from another user making commits to their own branch of zulip and referenced this old issue. Maybe in the near future it will be resolved soon

</div>

## EX. 6.5 Figure out how to create a new account on the bug tracker of your chosen project. You’ll need that account very soon.
<div style = "color:red">
I have created an account on Github, and a zulip account while also joining the zulip organization. I claimed Csharp code doesn't support string interpolating #17265 which can be seen here : https://github.com/zulip/zulip/issues/17265
</div>  
## EX. 6.6 Go through your project’s bug tracker and find a bug that you think you might be able to reproduce – and then try to reproduce it in the latest build. Take careful notes. Report your experiences as a comment to the bug. If you can reproduce the bug, great! Give as much information as you can. If you can’t reproduce the bug, great! Give as much information as you can, and ask the original reporter if there are other steps you might be able to take to reproduce the bug.

<div style = "color:red">
I chose this bug because I thought it be a simple fix . String Interpolation is a fancy name for compiler based string templates that allow you to embed expression values into literal strings with the compiler expanding the embedded values into the string using the $ operator: String Interpolation is a great way to make code more readable, but keep in mind that it's not a runtime templating solution as you can't read a format string into memory and then evaluate it - that's not possible using the String Interpolation syntax. This is purely a compiler feature that makes inline string literals in your code more readable and maintainable. I have no tried to reproduce just because I just claimed it but I will update this when I do. 
</div>

## EX. 6.7 Find five bug reports in the new state, and attempt to triage them according to the rules above. Your goal is to do as much as you possibly can, in a short period of time, to make those bug reports as useful as possible to the developer to whom they are assigned. (Note: be sure to follow any triage rules that your project may have defined. If there are no set triage rules, be sure to announce your intentions on the project’s mailing list, so that developers can provide you some guidelines if they choose.)
<div style = "color:red">
I decided to pick these five:

Can’t close message edit form after internet connection is lost
Can’t search history of shared-history private streams
filter: Check if search operand is valid
widgets: Prevent edits to /poll and /todo messages.
feature request: Add green/orange presence circles to PM/mention autocompletes
I would rank them from high to low priority as such:

Can’t search history of shared-history private streams
Can’t close message edit form after internet connection is lost
filter: Check if search operand is valid
widgets: Prevent edits to /poll and /todo messages.
feature request: Add green/orange presence circles to PM/mention autocompletes
I rank them in this order because 5. is simply a feature request, this doesn’t affect the overall functioning of the project. 4. is also a simple edit to prevent edits to certain widgets with an error message. 3. Is of medium priority since it seemed to be fixed quickly, but searching with an invalid operand leads to a 400 error which is not desireable. 1. and 2. directly affect how the users interact with Zulip and the 1st regarding search history seems to cause a lot of confusion with users while 2. is also a high priority because in the issue thread, there are problems trying to re create this issue again.

</div>

# "What's Happening?"

<div syle = "color:red">
For today’s blog, I read an article from the IEEE Software Magazine titled Google App Analysis 
    

With the rapid development of technology over the last decade, electronic devices, especially mobile phones, have become a significant part in our lives. The increase diversity and functionality of cellphone apps provides simplicity and value to their users on daily basis. Product features such as rating scores and customer reviews enable potential and exiting users to offer valuable opinions to the app. Unlike app descriptions, these features reflect the most accurate views and personal experiences provided by existing clients. As such, potential clients tend to rely on the ratings and reviews when searching for apps that is most suitable for their needs. Furthermore, customer feedbacks is an excellent source of idea for program developers to upgrade and enhance the system and functionality. Therefore, maintaining a positive review and high rating scores are the primary tasks and goals for app developers. Since app ratings are restricted to three times per year, many ratings are missing in the data gathered from kaggle. Leaving missing data untreated might bias the model result, hence one of the main objective of the aritcle I am reading which is to build a statistic model that forecasts missing rate values. What

The author discussed how With the widespread use of smart phones, the importance of cellphone apps is emerging in our daily lives. The rating of an app impacts the number of downloads which may further influence the spread of the app. In order to explore the underlying behavior of apps' ratings, a research was conducted analyzing rating related data that involves multifaceted factors. Establishing statistical models such as “Generalized Additive Model” provides a conceptual framework for the study and is instrumental in predicting the missing ratings. A number of conclusions are drawn from these models including identification of the non-linear relationship between log installs and ratings, and the positive relationship between log reviews and ratings given number of log installs.


</div>






