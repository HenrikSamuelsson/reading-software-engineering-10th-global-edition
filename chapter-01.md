# Exercises Chapter 1

## Exercise 1.1

Explain why professional software that is developed for a customer is not simply the programs that have been developed and delivered.

## Solution 1.1

Professional software can besides the program delivered include objects such as user manuals, customer specific configuration files, documentation of design, test results, list of known deviations from the customer requirements.

There can also be a need to produce material related to legislation's that must be followed such as the General Data Protection Regulation.

## Exercise 1.2

What is the most important difference between generic software product development and custom software development? What might this mean in practice for users of generic software products?  

## Solution 1.2

A generic software is developed for a wider range of customers than a custom software. A custom software will in the extreme case be developed to be used by a single customer even though it would possibly have several users since the customer would typically be a company.

The end user is known ahead of starting the development in a custom product development project and will possibly be part of the development process, providing input and request for changes as the work proceeds. The exact end users are not known in generic software development meaning that the strategy used for collecting input and requirements will have to be handled in some other way.

Users of generic software products will typically have little influence on the development and the end functionality since the pool of users is typically large and only a small amount of users are realistically deeply involved in the development. The fit between the users needs and the functionality of the software will hence not be as good as it could be. The benefit is that the users share the cost of the development and the price comes down greatly per user.

## Exercise 1.3

Briefly discuss why it is usually cheaper in the long run to use software engineering methods and techniques for software systems.

## Solution 1.3

Software engineering methodologies and processes will add overhead in many ways. Examples are planning, architectural design, written requirements, test automation, documentation and review of the artifacts created during this process. In the short run so can this been seen as obstacles slowing down the development but in the long run so will the benefits of having a structured process decrease the total development time. This is due to that the structure a software engineering processes ensurers quality and reduces confusion about what to be developed. It must also be accounted for that developers will come and go in the project, not having good documentation will make it hard for new developers to get up to speed.

## Exercise 1.4

Software engineering is not only concerned with issues like system heterogeneity, business and social change, trust, and security, but also with ethical issues affecting the domain. Give some examples of ethical issues that have an impact on the software engineering domain.

## Solution 1.4

Developing military equipment can be an ethical issue depending on a developers personal view on this matter.

Not following the license rules when including code from open source projects is an ethical issue.

Taking shortcuts or cheating in the validation process of safety critical systems possibly in the future causing harm to people is an ethical issue.

Development of systems to be used for by non democratic countries that might use it suppress the democratic movement is an ethical issue.

## Exercise 1.5

Based on your own knowledge of some of the application types discussed in Section 1.1.2, explain, with examples, why different application types require specialized software engineering techniques to support their design and development.

## Solution 1.5

Cost of change is related to how much up front planning must be done. A system that is not connected and hence not remotely reachable, such as some embedded systems, can be very costly to update to a new software version. A technician might need to travel to each instance and open up the unit to be able to perform the update. When the cost of change is high so is it worth to spend more time on up-front planning to minimize the risk of having to perform a future update due to bugs or missed requirements on the product.

For systems of systems there will be a need for systems work that will not be required for simpler systems such as stand-alone application or a more simple entertainment system. A systems department will typically start the planning and do a high level design splitting the system into parts and the work is then distributed to several more specialized teams that do the detailed design and actual implementation.

Some systems will have need to have a high level of security due to being accessible from the outside world by both the normal users and also malicious attackers. Interactive transaction-based application such as banking systems and e-commerce systems will require security design of authentication procedures. But other systems such as modeling and simulation used by scientists and engineers in a closed environment have much less strict requirements on security.

Life time of the system affects how much effort shall be put into future proofing the system. Can be so that an  interactive transaction based application requires less effort in future proofing if the application is to be used for a one-time event at a given date. Assume for example that a web-site is to be developed for following the schedule of the upcoming Olympics that will occur at a given date regardless of the state of the web-site. Here it will much important to have something in time than to plan for how to maintain the system in the future. On the other hand say that a systems of systems control system for an aero plan with an expected life-time of 20 years is to be developed. This type of system will require more documentation, planning, and procedures to ensure that the code can be maintained in the future.

## Exercise 1.6

Explain why the fundamental software engineering principles of process, dependability, requirements management, and reuse are relevant to all types of software system.

## Solution 1.6

The process used for development of various software system can vary greatly but there should still be made a decision on what process to follow and the choice should be documented. Often there is no need the develop and unique process instead an existing process can be chosen and the process documentation can simply point to already defined process description located in a book or online. The reason for having a process is to have structure, and quality assurance, in the development and for everyone in the team to know what the expectations are for the project to be considered done when it comes to documentation to be produced and how to handle the storage and versioning of the artifacts produced.

A degree of dependability is needed for to be meet for the system to be usable. The quality of dependability can be allowed to vary, a safety critical system will require a high degree of dependability, and in the other spectrum we might have a phone application for entertainment such as augmented reality that can be released even with a number of known problems. But even if the dependability can vary so must there be a defined minimum level to be meet for a software system to be useful for the end user.

Requirements management is a must for all types of software systems to have some type of progress tracking and steering towards the end goal in the development process. Some projects do a lot of upfront planning and and others will only plan for the upcoming two weeks but there needs to be some known requirements to know when the current work is done and also to be ables to test the system.

Reuse is important in all projects since it is not cost efficient or fast to reinvent the wheel again and again for any type of project including software projects. There is virtually not a single software project that does not includes some type of reuse. Minimally a project will make use of the standard library that comes with the programming language used in the project. Then usually also both third-party components and already in-house developed ones will be included in the software system.

## Exercise 1.7

Explain how electronic connectivity between various development teams can support software engineering activities.

## Solution 1.7

Communication is key for collaboration between teams because information needs to be shared as soon as more than one person is to be involved in a development project.

Electronic connectivity based communication is preferred due to the real-time turn around time in the information flow even for geographically distributed teams.

Todays systems for connectivity will also enable sharing of a wide array of mediums, such as text, sound, and video, for both group and one to one interaction.

There are also various types of board based electronic systems for tracking and planning.

Finally there are electronic systems for storing and maintaining code in a central repository enabling distributed teams work in parallel on a shared code base.

## Exercise 1.8

Uncertified individuals are still allowed to practice software engineering. Discuss some of the possible drawbacks of this.

## Solution 1.8

There is a higher risk of failure in a development project when staffing with uncertified new unknown individuals that might not have the required basic knowledge, or incorrect knowledge about prioritization of the work to be done.

Certification is however no guarantee for the success of a project since there are also a lot of other factors that comes into play but if two candidates for the team seems equal otherwise so is the proper choose to go for the one that do have certifications on the resume.

## Exercise 1.9

For each of the clauses in the ACM/IEEE Code of Ethics shown in Figure 1.3, propose an appropriate example that illustrates that clause.

## Solution 1.9

Public: The software engineer shall follow the rules and regulations such as the International Traffic in Arms Regulations (ITAR) to safe guard the national security that is in interest of the public to prevent conflicts.
