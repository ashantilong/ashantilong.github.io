# ashantilong.github.io
GitHub Pages : You will maintain a professional-grade blog titled with your full name where you will post all individual assignments by the date specified. Your team will maintain a professional-quality wiki where you will post all team assignments by the date specified. Each assignment must be professional in appearance with pertinent identifying information

**HW1: Chapter 1**

**1.3 Four important attributes of professional software are**:
- Maintainability
- Dependability and security
- Efficiency
- Acceptability/Usability


**1.4 The four most important attributes are essentially maintainability, dependability, efficiency (performance) and usability. Other attributes that may be significant could be reusability (can it be reused in other applications), distributability (can it be distributed over a network of processors), portability (can it operate on multiple platforms e.g laptop and mobile platforms) and inter-operability (can it work with a wide range of other software systems).
Other attributes that are also significant are:**
- Response time (non-functional attribute)
- Interactivity
- Reliable
- Evolution


**1.8 Discuss whether professional software engineers should be licensed in the same way as doctors or
lawyers.**
-I believe that professional engineers should be certified in the same ways as doctors and lawyers because like doctors and lawyers you understand who has the right credential. Software is extremely important in today’s world and it is increasing higher than any occupation . For instance, high security government software should not be made by just any guy with some knowledge of programs. We should have a way to differentiate between the people who should be in charge of creating and fixing critical programs and those who aren’t quite ready for that type of responsibility

**1.9: For each of the clauses in the ACM/IEEE Code of Ethics shown in Figure 1.4, propose an
appropriate example that illustrates that clause.**
-PUBLIC – Software engineers shall act consistently with the public interest.
A software engineer will create non-malicious software that is robust enough to maintain the welfare of its stakeholders.
- CLIENT AND EMPLOYER – Software engineers shall act in a manner that is in the best interests of their client and employer consistent with the public interest.
A software engineer will create software that is to the standard/specifications of those who request it.
- PRODUCT – Software engineers shall ensure that their products and related modifications meet the highest professional standards possible.
A software engineer will create software that is acceptable, dependable, secure, efficient, and maintainable.
- JUDGMENT – Software engineers shall maintain integrity and independence in their professional judgment.
A software engineer will practice good ethics in their profession despite any negative pressure they may receive.
- MANAGEMENT – Software engineering managers and leaders shall subscribe to and promote an ethical approach to the management of software development and maintenance 
6. PROFESSION – Software engineers shall advance the integrity and reputation of the profession consistent with the public interest.
A software engineer will ensure that a software’s development is at least up to industry standard if not better.
- COLLEAGUES – Software engineers shall be fair to and supportive of their colleagues.
A software engineer is an understanding, unbiased and dedicated worker within their team.
- SELF – Software engineers shall participate in lifelong learning regarding the practice of their profession.
A software engineer continues learning as the standards of software engineering change, such that they may maintain the industry standard for development.
**1.10 To help counter terrorism, many countries are planning or have developed computer systems that
track large numbers of their citizens and their actions. Clearly, this has privacy implications. Discuss
the ethics of working on the development of this type of system.**
- In working on the development of this type of system, there is a fine line between what is ethical and what is not. On one hand, citizens do not want to be tracked because they want to maintain privacy, but on the other hand it is within public interest to prevent terrorist action. 
Therefore, the best solution to this problem is assuring that the privacy of those being tracked is protected by the software. 
This means a strong consideration for the security and dependability of the software, as well as a high ethical standard set for the engineers developing it.


**HW2: Reflections on software engineering practices**

Today I will be discussing with you: Silver Bullet while using Cherry Picking and Scientific Method, Google Copy Repo and Make Se More Ethical as information to back up certain things or give examples .  “Silver Bullet” by Frank Brookes discusses the monster known as Software engineering. When I was growing up my sibling use to babysit me while my parents were at work. We would always watch anime because my brother went to Japan with my father for several years and that where he was introduced to anime, loved it and wanted to introduce it to us. I remember the first anime I ever watch was アンパンマン and ドラゴンボール. The plot was the same, the evil villain reck havoc on the city, planet, and hero friends etc. And everyone would wait for the hero to save the day to make thing easier for everyone and to end everyone suffering. One watches horror movies like Blade, Underworld etc. Where vampire reach havoc on the world and as you are getting bit by a vampire you just think within your head that you wish you had a silver bullet to kill this vampire and make thing easier for you and end the suffering. The point I am trying to make, and the point Brooke made is that there is no silver bullet in software engineering. We as developer might think the solution is nontechnical and straightforward but software can become a disaster like a tsunami or as frightening as a vampire or werewolf. From: miscommunication, to complex structure, flawed product, unaffordable budget etc. I think we as developer or as programmer wished we had a silver bullet like hardware has and reduce productivity and production with reduction of cost. As you read “Silver Bullet”, Brooke categories software difficulties into two groups: essential difficulties which discusses the difficulties that was inherent by the software itself which are problem that unavoidable due to the complex nature of the software.   Then accidental difficulties which is the result of one overcomplicating things for themselves and making things harder. Which I think relates to the “Cherry Picking and Scientific Method” article.  Cherry Picking is a very misleading and untrustworthy method which relate to making thing more difficult for yourself.  Cherry Picking does not provide all the test cases for the experiment and it hard to find pattern in data so I would categories this as accidental difficulties. Then Brook goes on discussing the source of essential difficulties and why there will never be a silver bullet. They are listed as: complexity, conformity, changeability, and invisibility. A example of one of these essential difficulties is google code repo. The monolithic model that google made surely makes it easier to comprehend the complexity of the codebase, since there is no coercion of repository boundaries between dependencies. However, as the scale increases, code discovery can become more difficult. Which many problems that arise in software engineering is the nonlinear increase in size. So, what can we do to fix these problems?  We should reuse, incremental development and nurture your software engineers. I think nurturing our software engineers and make sure they follow the right path and ethics. Software developers are a huge part of today society. They are the one protecting our infrastructure. They write 1000 of lines of code today to model today society and impact people live. They protect and secure our information from hackers. Software engineering is in everything: banking, surveillance, drones, security, cars and etc.. They truly impact the world .


**HW3: Chapters 11 & 12**


**11.4 What is the common characteristic of all architectural styles that are geared to supporting software fault tolerance?**
- A system that provides fault tolerance will include redundant and diverse hardware and software.


**11.7 It has been suggested that the control software for a radiation therapy machine, used to treat patients with cancer, should be implemented using N-version programming. Comment on whether or not you think this is a good suggestion.**
- Using multi-version programming to evaluate radiation therapy is a good method. If we have multiple system running cohesively on a hardware, which is set in the same settings, then if these two systems calculate the same output, the output should be correct. I am not sure how many would be required to produce the same output, but based on probability, the more machines required to produce the same output, the safer it is


**11.9 Explain why you should explicitly handle all exceptions in a system that is intended to have a high level of availability**


-This is due to if they are not handled then the software will shut down. Software developers must provide exception for anything that could be detected and possible exceptions that may arise. If the software fails and the system shuts down
**12.5 A train protection system automatically applies the brakes of a train if the speed limit for a segment of track is exceeded, or if the train enters a track segment that is currently signaled with a red light (i.e., the segment should not be entered). There are two critical-safety requirements for this train protection system: The train shall not enter a segment of track that is signaled with a red light. The train shall not exceed the specified speed limit for a section of track. Assuming that the signal status and the speed limit for the track segment are transmitted to on-board software on the train before it enters the track segment, propose five possible functional system requirements for the onboard software that may be generated from the system safety requirements.**
1.	Check whether the signal status is green for the upcoming section of a track (a)
2.	Check whether train is going faster or slower than the intended speed limit for that section of track (b)
3.	If (b) calculates that the train is going faster, apply brakes gently
4.	If (b) calculates that the train is going slower, speed up gently
5.	If (a) is red, search for another option of track segment that has a green signal status
6.	If either (a) or (b) are not within the critical safety requirements, alert the human conductor

**HW4: Reflections on software failures**

- What is the difference from “Fault”, “Error” and “Failure? Well, this would be all categorized as dependability that we read in chapter 13 and 14.  If we talk in term of dependability it is the system property that cohesively unite elements such attributes as reliability, availability, safety, security, survivability, maintainability. The aim of the reflection is to summarize basic concepts of dependability occur in several articles: Thearac-25 Accident, 2010 Radiation Follies, FBI Auto Warning, Spacecraft Accident, FBI Fiasco 2005, FBI Fiasco 2010, Why Software Project Fail etc.. A structured view of dependability follows, according to a) the threats, i.e., faults:  It is a condition that causes the software to fail to perform its required function., errors:  refers to difference between Actual Output and Expected output  and failures: It is the inability of a system or component to perform required function according to its specification., b) the attributes, and c) the means for dependability, that are fault prevention, fault tolerance, fault removal and fault forecasting. If we look at the article Thearac-25 Accident which discusses radiation therapy machine.  One can see it is a major breach security and dependability. It is basically a X-Ray or a combination of electron to kill cancer cell deep in the body. However, this type of treatment killed many people due to overdose of radiation in the body. This is “Fault” because it was discovered that there were many bugs in the software meaning the bug was the component which was the turntable and magnets being in the wrong position and in causing overdosing patients. Preliminary risk assessment and analysis aim to identify the generic security risks for a system and its associated data. This risk assessment is an important input to the security requirements engineering process. Security requirements can be proposed to support the general risk management strategies of avoidance, detection, and mitigation. Which they failed to do. Which is a faulty software design. Then if we look at 2010 Radiation Follie is another radiation overdose case. While in some cases technicians did not know how to properly administer the test, interviews with hospital officials and a review of public records raise new questions about the role of manufacturers, including how well they design their software and equipment and train those who use them. If we look at the article “Why So Project Fail” it is stated that 55 % project fail due to the lack of time, staff and resources. Hospital are populated throughout the world and the amount of equipment and software they need only increases so we can assume that software engineers are pressured to produce fast and efficient software which can connect to the lack of time. Both causes of overdose can also relate to the lack of testing that manufacturers did.  But when there’s a lot of pressure to deliver on a project at a certain time, testing is typically the first thing to be abandoned. If we look at the article Spacecraft Accidents which is collection of software failure in spacecraft and look at some of the accidents. For example: Ariane 501 which flew off course. If we look at the accident report we can discover the loss of information was due to specification and design errors in the software of the inertial reference system. The software was reused from the Ariane 4 and included functions that were not needed for Ariane 5 but were left in for “commonality.” In fact, these functions were useful but not required for the Ariane 4 either. However, I just see this a laziness and not wanted to modify such changes to be efficient thus I find this as an exposure which is possible loss or harm to a computing system. This can be loss or damage to data or can be a loss of time and effort if recovery is necessary after a security breach. If we look at the rest of the article we will see the same pattern of common trends that is breach of security such as : insufficient time, inadequate planning, unclear on project specifications, to many people on one project and lack of testing 


**HW5: Chapter 4 and Reflections**

-The reading for today: magicial number 7 , tire preasure monitering system , spy car act of 2015 and test driven development showed importance of incorporating Test-Driven Development while also showing how the establishing of the requriment of non-functional and functional before one can reach the development phase.Doing nonfunctional and functional is essential to the growth.  If a developer does not have a clear understanding of these concepts they could forget about thing that could impact the film which could lead to a catastrophic errors and running out of time. If we look at  “Magical Number Telephone number Seven” it show that if we do not understand functional and non-functional requirement we can easily forget certain layout and forget certain feature and that can delay us a lot as developers , especially if we are discussing or working on  big projects.

**4.5 Using the technique suggested here, where natural language descriptions are presented in a standard format, write plausible user requirements for the following functions:**
•	An unattended petrol (gas) pump that includes a credit card reader. The customer swipes the card through the reader then specifies the amount of fuel required. The fuel is delivered and the customer’s account is debited.
The system shall be sure that there is fuel available.
The system shall determine the price for the specified amount of fuel.
The system shall deliver the correct amount of fuel.
The system shall shut off once specified fuel amount is reached.
The system shall debit the customer’s account for the price of the amount of fuel delivered.
•	The cash-dispensing function in a bank ATM.
The function shall verify the validity of the card used.
The function shall verify that the PIN used matches the specified card and account.
The function shall make sure the account has the amount specified.
The function shall be sure the dispenser has the available funds requested.
The function shall dispense the specified amount of cash.
The spelling-check and correcting function in a word processor.
The function shall alert the reader to a misspelling.
The function shall check whether the targeted word is in the specified (installed) dictionary.
The function shall attempt to match the typed word to the closest word in the dictionary.
The function should offer suggestions for corrections of misspelled words.
The function should offer to ignore a misspelling.
The function should offer to add a spelling to the dictionary.
**4.6) Suggest how an engineer responsible for drawing up a system requirements specification might keep track of the relationships between functional and non-functional requirements.’**


-A diagram or list would be ways that would allow an engineer to keep track of the requirements as well as the connections between them. A diagram would allow visual connections and relationships between functions to be easily recognized rather than the confusion that could result from keeping everything separate in lists.


**(4.7) Using your knowledge of how an ATM is used, develop a set of use cases that could serve as a basis for understanding the requirements for an ATM system.**
Withdraw funds: By swiping their card through the card-reader, the user then inputs a PIN (personal identification number) to verify access to the account. The records of the bank who holds the account are checked, and the account is then confirmed. The user may then choose from a list of options on the ATM screen. The user can input an amount (or may have the option to choose from a predetermined amount) to be withdrawn from their bank account. The system confirms that the user has enough money in their account before dispensing the specified amount of cash. After the cash is dispensed, the user will confirm that the transaction is complete by pressing the button on the screen. They are then logged out of their account and the ATM is prepared for the next user.
Transfer funds: After confirming access to their account by the process aforementioned, the user is again presented with a list of options on the screen. By choosing the button to transfer money, the user can choose to move money between their own accounts, for example, transferring money from their savings account into a checking account, or into the account of another user provided they have the account number to transfer the money into. The user must then confirm the amount and the destination, the money is transferred and the transaction is complete as the user logs out of the account and the ATM is prepared for the next user.
Check balance: By again confirming access to their account, the user is presented with a list of options. The user may then choose the option for checking their account balance on the screen. The ATM accesses the bank records for the specified account and displays it on the screen for the user to see. The user may then choose to press “End” therefore logging out of their account on the ATM.

**HW6: Chapter 2**

**2.1  Suggest the most appropriate generic software process model that might be used as a basis for managing the development of the following systems. Explain your answer according to the type of system being developed:**


•	A system to control antilock braking in a car - the waterfall process is usually adapted for safety-critical systems because of the higher amount of analysis and documentation required before implementation. Because testing is a huge part of finalizing the software, it seems the waterfall model is the most appropriate generic software process. 
•	A virtual reality system to support software maintenance - software maintenance is best done through versions and updates over long amounts of time, which would be the incremental development process.
•	A university account system that replaces an existing system - the integration and configuration process seems like it would be the best choice for a new account system as it takes reusable components (like formulas and sums) and integrates them into a new system and setting.
•	An interactive travel planning system that helps users plan journeys with the lowest environmental impact - I think this could be more than one of the software process models, but I will say incremental development. A planning system would need to be adaptable and have multiple versions.






