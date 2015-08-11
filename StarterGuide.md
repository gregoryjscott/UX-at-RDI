#UX at RDI: Starter Guide

####Who is this document for?
This document is specifically written for programmers, business analysts and project managers at RDI. Perhaps you are already the UX guru in your branch. Or perhaps you don’t really understand what they mean when someone tells you your website needs “better UI”. Either way, this document aims to clarify what UX means at RDI and includes some considerations you might consider in your projects

##UX at RDI
At RDI we take pride in our ability to develop complex IT systems by addressing the complete needs of our clients.  While not always explicitly stated in our project requirements, a key consideration for every project with a user interface is how we can best deliver professional systems that are intuitive or familiar to our users. 

*User experience (UX) is the process of enhancing user satisfaction by improving the workflows, usability, ease of use, and that sense of flow experienced by the user while interacting with the product or system.*

Let’s put this in more practical terms. Every day at RDI, we are making many small decisions that affect the UX of our products. These include:

* The colors, fonts and graphics
* The layout and spacing
* The words (actual content) of the system
* The words we use to identify menus, heading and buttons
* How we structure and organize a system (menus, navigation, sections)
* How a user interacts with information in the system
* How we build forms and other functionality

Paying more attention to these small decisions and how they affect the overall user experience will greatly improve the UX and overall quality of our products. 

From a business perspective, improving overall UX at RDI means:

* Our products will be competitively differentiated in the marketplace.
* Our systems will achieve faster, better user acceptance.
* Users achieve a state of flow in our systems and user satisfaction is higher.
* User errors (and resulting “bugs”) are reduced.
* Our solutions require less training and documentation.
* We inspire loyalty in our clients.
* The business process is repeatable and scalable.
* ROI is high – good UX design pays for itself.

##UX UI at RDI

Currently, when we talk about UX in the context of RDI projects we are focusing on the colors, layout, words, etc. These are actually all aspects of the user interface (UI).

Many people confuse the terms UI and UX because they are related, but not the same. UI is only a small part of UX. Generally speaking, **user interface design and development (UI) refers to the visual design (look and feel) and how the user interacts with that look and feel.** At RDI, our developers build good-looking, modern user interfaces using HTML, CSS, javascript and other front-end technologies

##The difference between UI and UX

So if most of what we do at RDI is UI, what is UX? What else is there?

Have you ever used a beautiful, modern website with a super-slick UI only to discover that you can’t figure out its registration process? That site had nice UI, but needs to work on its UX.

UX includes all aspects of the UI, but also includes aspects such as organization, ease of use, consistency and that sense of flow that makes a user happy to use the product. UI is what you build and how the user interacts with it, whereas UX addresses why you build something in a certain way and how a product works as a whole.

Let’s put this in more practical terms. Pretend you are building a form with a modal popup message letting the user know about an urgent issue with their data.

UI is: | UX is:
-------------------------------------------------- | --------------------------------------------------  
What should this pop-up look like? | Should I use a pop-up here or would a different workflow be more user-friendly?
How does a user close the pop-up? | Does using a pop-up disrupt the user while she’s entering data?
Should the background behind the pop-up get greyed out? | I’m not using pop-ups anywhere else on the site. Am I being consistent?

Here’s another example. Pretend you are building a new website with a heavily nested navigational structure.

UI is: | UX is:
-------------------------------------------------- | --------------------------------------------------  
What should the navigational menu at the top of the page look like? | How should the navigational items be grouped? Should there be sub-groups? How many?
Should I use a hover drop down menu for each main menu item? | In addition to a top navigational menu, are there other ways we can organize information so the user can find it?
What should each navigational item be called so that users will know exactly what it is? | Can the user find the page they are looking for in a reasonable amount of time?

The next sections will give you some specific UX tools to help you figure the most appropriate ways to build the UI.

##What does UX look like in an RDI project?

Just as we build analysis, testing and project management into every RDI project, every applicable project should have some UX time built in as well. This means building it into our project plans and estimates by default.

Additionally, it means making sure the project team knows who is thinking about UX. At RDI, people play a variety of roles on projects. Developers sometimes play the role of business analyst; project managers do development; everyone does testing. In this same way, every project should have at least one person whose job is to think about UX. Depending on the project, this might be a programmer, tech lead, business analyst or designer. Sometimes our clients play part of this role, particularly if they are the primary user.

##How do you DO UX?

Here are some specific suggestions on how to include UX in your projects.

####Know who your user is
Who are the primary and secondary users? Most of the time, you are not the target audience, so designing the system based on what makes sense to you isn’t going to work. What is the user’s level of tech-savviness? What are their main goals? What is their level of domain knowledge? Knowing this information will help you make informed decisions about how to build the UI later in the process.

For example, your client may use a lot of lingo related to their industry. But before you start using that lingo on a website for the public, you might want to evaluate who the audience is? Will they understand what the lingo means?

*Useful tools and techniques: Requirements, User interviews, Personas*

####Think about what success means for your users
Requirements tell you what the site is supposed to do, but that isn’t quite the same thing as a successful user experience. For example, the requirement might be that the user be able to sign up for a site. However, if there is no confirmation to the user that they signed up successfully, the users get confused. Your client starts to receive calls from users who say the site is broken. You met the requirement, but the UX does not meet the user’s needs.

*Useful tools and techniques: User interviews, Personas, User stories, User testing*

####Design before you code
If you are a programmer, you probably don’t start coding without some kind of technical design. Likewise, don’t start coding without a basic UI design. This might be an informal whiteboard sketch, a mockup, or a full-blown clickable prototype. By doing a bit of design first, you will be forced to think about the user experience, and not just what is easy for you to code.

While you think about design, keep in mind that:

* Your first idea may not be the best.
* As you sketch, you may realize what you designed doesn’t work. Don’t be afraid to rethink or start over.

For some projects, these early designs will be something you present to the client. Mockups, wireframes or low-fidelity prototypes are all useful tools for making sure you and the client understand what will be built or for trying out different options. Clickable prototypes can even be used for up-front user testing if needed. Tools such as Balsamiq and Microsoft Expression Sketchflow allow you to create mockups that users can click through, much like using a real system.

*Useful tools: pen and paper, whiteboards, Balsamiq, Microsoft Expression Sketchflow. For low-fidelity prototypes Bootstrap with an unobtrusive theme works well and gives you lots of out-of-the-box elements.*

####Test with real users
We do a lot of different types of testing in software development. However, if you don’t put your system in front of real users (this may or may not be the client) and have them use it, you won’t know if you are meeting the user’s success criteria.

Note that user testing and user acceptance testing (UAT) are not the same. UAT is used to test that the requirements have been met. User testing verifies that users can successfully use the system and meet their goals. User testing should ideally happen before and during a build, whereas UAT happens at the very end of a project. 

*Useful tools: clickable mockups or prototypes, prototype sites*

##What (specifically) can I do?

Everyone should be able to incorporate the above suggestions into your project work. However, here are some specific suggestions depending on your role. Regardless of the role you are filing, if you are on a project where UX is not being considered, you are encouraged to voice your concerns.

####Project Managers
As a project manager, you can:
* Make sure your estimates include time for UX design and make sure you build it into the project plan.
* Make sure the test plan includes user testing.
* Make sure at least one member of your team is thinking about UX. (Maybe this is you.)

####Business Analysts
As a BA, you probably already do a lot of UX design work. When you focus on the solution and how a system should work, you are thinking about UX.

As a business analyst, you can:

* Find out:
  * Who are the users?
  * Who is the target audience and what are their characteristics?
  * What constitutes “success” for these users?
* If it seems relevant, interview actual users of the system (in addition to stakeholders.)
* If it seems useful, create personas.
* Create a site map or document a proposed site structure. If this is unclear, consider doing a card sort.
* Create mockups or wireframes, or assist the developers with this task.
* Facilitate user testing.
* Keep the team focused on the user.

####Programmers / Technical Leads

As a programmer, you can:
* Ask questions about the user in addition to requirements.
* Design before you code by creating sketches, mockups or low-fidelity prototypes.
* Enlist the help of a graphic designer if you need it.
* Consider using a framework such as Bootstrap to improve your application’s look and feel.
* When building complex forms and pages, step back and try to view it from your user’s point of view. Will they understand it? Are there assumptions you are making?
* Think about what you call things (buttons, sections, menus). Will it make sense to the user?

##Other Resources

Here are some other documents and resources you might find useful:

* UX Checklist for your RDI project (COMING SOON)
* RDI Tools and Software for UX (COMING SOON)
* UX People Resources at RDI (COMING SOON)
