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
