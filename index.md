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

<div style = "color:red">
For today’s blog, I read an article from the IEEE Software Magazine titled Google App Analysis 
    

With the rapid development of technology over the last decade, electronic devices, especially mobile phones, have become a significant part in our lives. The increase diversity and functionality of cellphone apps provides simplicity and value to their users on daily basis. Product features such as rating scores and customer reviews enable potential and exiting users to offer valuable opinions to the app. Unlike app descriptions, these features reflect the most accurate views and personal experiences provided by existing clients. As such, potential clients tend to rely on the ratings and reviews when searching for apps that is most suitable for their needs. Furthermore, customer feedbacks is an excellent source of idea for program developers to upgrade and enhance the system and functionality. Therefore, maintaining a positive review and high rating scores are the primary tasks and goals for app developers. Since app ratings are restricted to three times per year, many ratings are missing in the data gathered from kaggle. Leaving missing data untreated might bias the model result, hence one of the main objective of the aritcle I am reading which is to build a statistic model that forecasts missing rate values. What

The author discussed how With the widespread use of smart phones, the importance of cellphone apps is emerging in our daily lives. The rating of an app impacts the number of downloads which may further influence the spread of the app. In order to explore the underlying behavior of apps' ratings, a research was conducted analyzing rating related data that involves multifaceted factors. Establishing statistical models such as “Generalized Additive Model” provides a conceptual framework for the study and is instrumental in predicting the missing ratings. A number of conclusions are drawn from these models including identification of the non-linear relationship between log installs and ratings, and the positive relationship between log reviews and ratings given number of log installs.


</div>


# Stupid or Solid?

<div style = "color:red">


Today blog review on  S.T.U.P.I.D. and S.O.L.I.D. and I’ll be giving a quick review about what .


 S.T.U.P.I.D can be broken down into:

Singleton

<div>
1. Singleton are generally used as a global instance, why is that so bad? Because you hide the dependencies of your application in your code, instead of exposing them through the interfaces. Making something global to avoid passing it around is a code smell. They violate the single responsibility principle: by virtue of the fact that they control their own creation and lifecycle.They inherently cause code to be tightly coupled. This makes faking them out under test rather difficult in many cases. They carry state around for the lifetime of the application. Another hit to testing since you can end up with a situation where tests need to be ordered which is a big no no for unit tests. Why? Because each unit test should be independent from the other.

</div>

<div>

2. Tight Coupling

Tight coupling is when a group of classes are highly dependent on one another. This scenario arises when a class assumes too many responsibilities, or when one concern is spread over many classes rather than having its own class.In general, Tight Coupling is bad in but most of the time, because it reduces flexibility and re-usability of code, it makes changes much more difficult, it impedes test ability etc. loose coupling is a better choice because A loosely coupled will help you when your application need to change or grow

</div>

<div>
3.  Untestability
 Software testability is the degree to which a software artifact (i.e. a software system, software module, requirements- or design document) supports testing in a given test context. If the testability of the software artifact is high, then finding faults in the system (if it has any) by means of testing is easier bug it untestable then we have problem and can cost a lot .
</div>

<div>
4. Premature Optimization
I don't believe early optimization is bad in situations where you know you will hit performance issues. For example, I write surface modelling and analysis software, where I regularly deal with tens of millions of entities. Planning for optimal performance at design stage is far superior than late optimization of a weak design. Another thing to consider is how your application will scale in the future. If you consider that your code will have a long life, optimizing performance at design stage is also a good idea. In my experience, late optimization provides meagre rewards at a high price. Optimizing at design stage, through algorithm selection and tweaking, is way better. Depending on a profiler to understand how your code works is not a great way of getting high performance code, you should know this beforehand.

</div>

<div>
5. Indescriptive Naming
 Indescriptive class/field/method naming is a bad code smell. When you write your application, please, don’t forget that another people may maintain your code in future. If  you fully understand the abbreviations in your methods, other people may not be on the same wavelength with you. Moreover, today you remember these unassociated names but what if you need to update your application in a few months or years? To my mind, you will be the first victim of absence naming strategy.
</div>

<div>
* Duplication

Please, be faithful to DRY (Don’t repeat yourself) principle. You enhance complexity of alteration in application by making duplication in the code. It leads to situation when you need to spend a lot of time, alter different  classes (in the most cases they are not) to change some small piece of logic. One of the reason of code duplication is tight coupling. If your code is tightly coupled, you just can’t reuse it. And here comes your duplication.

</div>

Now that we have reviewed what stupid code is, lets examine the principles of solid code!

<div>
1. Single Responsibility Principle

The single responsibility principle provides another substantial benefit. Classes, software components and microservices that have only one responsibility are much easier to explain, understand and implement than the ones that provide a solution for everything

</div>


2. Open Closed Principle
 
 Open/Closed Principle as: “Software entities (classes, modules, functions, etc.) should be open for extension, but closed for modification.” The general idea of this principle is great. It tells you to write your code so that you will be able to add new functionality without changing the existing code
 
 </div>
 
 <div style = "color:red" >
 3. Liskov Substitution Principle
 
 practical software development. The principle defines that objects of a superclass shall be replaceable with objects of its subclasses without breaking the application. That requires the objects of your subclasses to behave in the same way as the objects of your superclass.
 
 </div>
 
 <div style = "color:red" >
 4. Interface Segregation Principle

principle was first defined by Robert C. Martin as: “Clients should not be forced to depend upon interfaces that they do not use“. The goal of this principle is to reduce the side effects of using larger interfaces by breaking application interfaces into smaller ones.

</div>

<div style = "color:red">
5. Dependency Inversion Principle
 
 states that high level modules should not depend on low level modules; both should depend on abstractions. Abstractions should not depend on details. Details should depend upon abstractions.


We have now summarized these two set of principles and a main lesson learned from this article 

</div>



# Release early and often


<div style = "color:red">



In this blog post will reflect on my readings from Teching Open Source chapters 8 and 9.

This chapter the author disccused how important documentation is in code. Doing projects or assigment in school , going back at code during past assigment , the more you write and be descriptive your comments will be easier to read by other and yourself and you can remeneber what yoy did.

Water Methon includes: Planning , Content , Writing ,Internationalisation/Localisation


You have written a piece of code, and released it into the world. You have done this because you think that others might find it useful. However, people need to understand why your code might be useful for them, before they decide to use it. Documentation tells people that this project is for them. If people don’t know why your project exists,
they won’t use it. If people can’t figure out how to install your code, they won’t use it. If people can’t figure out how to use your code, won’t use it.Proper documentation provides evidence of what has transpired as well as provides information for researching discrepancies. Supporting documentation may come in paper or electronic form. In recent years, more often, official supporting documentation has moved from paper based to electronic forms.


Chapter 9
The authors is discussing the phrase unanimous with FOSS ‘Release early and often.’ It is a informative outlook om encourage students to particpate in meaningful FOSS and professors' should break the threshold and adopt this practice for students.


</div>


# Chapter 5 

<div style = "color:red">

Chapter 5 of Client-Centered Software Development revolves around Domain Class Development. This involes finding and resuing code from earlier open source projects and coding some classes from scratch. This chapter also covers unit testing principles.

1. Reusing External Legacy Code
Class can reoccur in mutiple location in the domain. Person class is an example. Reusing External Legacy gode say you shoukld look in dsomain for similarly well devloped solutions that fit its needs.

2. Reusing Internal Legacy Code
Talking about uppdated old open source products to meet requriiments for additional requirements and fix serious shortcomings in the product. 

3. Coding Domain Classes from Scratch
 Domain tend to be very special . Most of the time unquire domain come withint the same  organization.

4. Adding Functionality with Constructors and Getters
Not all functions in a new class can be predicted but Getters and setters are used to protect your data, particularly when creating classes. For each instance variable, a getter method returns its value while a setter method sets or updates its value.

5. Software Testing

The importance of software testing and quality assurance is of high value in a software development cycle. Both of the processes refines the whole process and ensure superior quality to the product. Also, it reduces maintenance costs and provides better usability and enhanced functionality.


Designing Test Cases

A good test case design technique is crucial to improving the quality of the software testing process. This helps to improve the overall quality and effectiveness of the released software. Following are the test case design techniques to ensure high-quality of the released software

Debugging
Debugging has many benefits such as: It reports an error condition immediately. This allows earlier detection of an error and makes the process of software development stress-free and unproblematic. It also provides maximum useful information of data structures and allows easy interpretation

</div>


# "Chapter 6 "

<div style = "color:red">

Database Principles
A database has the following properties: It is a representation of some aspect of the real world or a collection of data elements (facts) representing real-world information. A database is logical, coherent and internally consistent. A database is designed, built and populated with data for a specific purpose.


Connecting to a Program
It will display every connection with the associated process. You may also use a program called tcpview. Just run the executable and it will show you all of the current connections being made by your system. You will need to be an administrator in order to see all of the connections being made but if you are infected with something serious or a rootkit, the connections may also be hidden. If you really wanted a fool proof way, you would need to setup a gateway or proxy of some sort for the machine.


Database Security
Database security measures include authentication, the process of verifying if a user's credentials match those stored in your database, and permitting only authenticated users access to your data, networks, and database platform.

Server level
Database level
Table level
Column level
Testing
There is a three step process for unit testing each database module.

Setup - create objects and insert new rows in the table, C
Test - replace and update rows in the table, R U
Teardown - D

</div>

# "Chapter  9"


### Chapter 7
<div style = "color:red">


Chapter 7 talks a lot about  User Interface Design. Talks about the general guidelines which include:

Task Oriented - can each be mapped out 
Language - can all user understatand and read 
Simplicity
Navigatability
Visual consistency
Discoverability - no error in pages 
Data integrity -  accuracy of data 
Client-Server Integrity
Security
Documentation
MVC Pattern
The Model View Control pattern is used to organize UI and program files.

Model - data connection
View - user interface 
Controller - inputs and outputs 

Chapter 9
Open-source software can also be commercialized from selling services, such as training, technical support, or consulting, rather than the software itself.

Another possibility is offering open-source software in source code form only, while providing executable binaries to paying customers only, offering the commercial service of compiling and packaging of the software. Also, providing goods like physical installation media 

Open-source companies using this business model successfully are, for instance RedHat,[6] IBM, SUSE, Hortonworks (for Apache Hadoop), Chef, and Percona (for open-source database software).

Also keep in mind what service you will use to license this product. Some alternatives to hosting your CO-FOSS product: GitHub, GitLab, BitBucket, SourceForge

</div>

# "Meeting Charleston"

<div style = "color:red">


I went to the gathering for the  fellow CS CofC alumni. They showed various panels , It was aweosme that the speakers all slightly different backgrounds and interests, From what i could remeneber a few of their profession was systems engineering, product design, and network security. Listening to thier journey about how they started their profession and the advice they had was awesome.  Someone ask the  panelists if they had any thoughts on graduate school or just getting cerfication . One said there was really nothing differnt other than making connection when younger  Another talk abou the duration of cerifcate and it depends on what you want to do where certicate is more helpful. Then the last  panelist  thoguht of graduate school as pointless because why you are studying old topic the world of design is changing , and could be trending towards something new so you would be left behind , where your portfolio matters more than your book smarts. Overall it was a good meeting and it was good to hear professional opinion 

</div>











