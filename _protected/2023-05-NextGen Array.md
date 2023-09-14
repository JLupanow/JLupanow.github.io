---
layout: encrypted
title: Revitalizing a Content Engagement Platform
subtitle: Amidst the pandemic, I transformed a platform to support virtual events by creating cohesive experiences, gaining stakeholder support, and showcasing the strength of user-centered design.
role: This was fulltime work as a product designer. I spearheaded the project by conducting user research, wireframing, prototyping, and writing user stories to support implementation.
timeline: May through December 2021
date: 2021-12-31 00:00:00
description: In the wake of the COVID-19 pandemic, I led the transformative redesign of Array's content engagement platform, which transitioned from serving in-person life science events to delivering virtual experiences. This project, spanning May to December 2021, included collaborating with developers to revitalize the interface while maintaining functionality for internal and external users. Thorough research, stakeholder engagement, and iterative design were pivotal, resulting in the adoption of a radical interface overhaul. Material UI was chosen for efficient implementation, with internal support garnered through company-wide surveys. The new design not only succeeded in bridging participant and presenter experiences but also streamlined customization efforts, leading to the eventual retirement of legacy platforms. The project showcased the significance of stakeholder buy-in, cross-functional cooperation, and user-centered design, setting a foundation for future successes.
featured_image: array-feat.png
accent_color: '#4C60E6'
gallery_images:
  - array-feat.png


---





<h2 id="challenge">The Challenge</h3>



Array provides a content engagement platform for life science events. For instance, if a new medical treatment became available and the doctors developing the treatment wanted to hold an event to share their findings with others in the field, Array technicians would come in and set up tablets to show each participant the slides and supporting materials. The platform allows participants to engage with the material by answering polls and surveys, asking the presenter questions, taking notes, and more. Then in 2020, the COVID-19 pandemic hit. **Array, a leader in in-person life science events, had to transition to the virtual world**. They wanted to build a high quality online event experience and rejuvenate the platform's appearance to compete with the many emerging virtual meeting platforms.

**My challenge was to redesign the platform to support both virtual and in-person events while improving the experience for internal and external users**. The project spanned from May 2021 to December 2021, with ongoing updates post-launch. I spearheaded the design process and worked independently under the guidance of the Director of Product while collaborating closely with a team of six developers.


<div class="image-wrap">
<img src="/images/projects/NextGenArray/meeting.png">
</div>

<div class="caption"><i>In-person event using Array's content engagement platform</i></div>




<h2 id="process">The Process</h3>



1. <a href="#research">Initial Research</a><br />
2. <a href="#brainstorm">Brainstorm and Wireframe</a><br />
3. <a href="#interview">Prototype and Interview</a><br />
4. <a href="#visual">Apply Visual Design and Gain Internal Support</a><br />



<h3 id="research">Initial Research</h3>



I began **conducting interviews with key stakeholders across departments and reviewing existing personas**. Once I had a good understanding of how the existing interface worked and what concerns our internal users had regarding the platform, I **joined ten events across a variety of event types so I could observe our external users**. I combined the information from my initial interviews with my observations from the events as I defined my user groups and their pain points. 


<div class="image-wrap">
<img src="/images/projects/NextGenArray/table.png">
</div>

Based on this initial research, I learned that technicians were writing custom CSS and HTML files to customize the interface for each client, which was not only taking up a ton of their time, but it was also a huge security vulnerability. Additionally, participants were having a hard time finding and using the engagement features unless the buttons were pointed out to them at the start of the show, which resulted in less engagement data available for our event organizers to take back to their teams. I also found that the participant and presenter experiences were so different that users couldn't tell it was the same application. This resulted in a huge learning curve for new presenters, so technicians had to spend a lot of extra time training presenters before the event.

So in addition to the business goals outlined above, my goals for improving the user experience were:
- **Unify the participant and presenter experiences where possible**
- **Make the interface configurable rather than "hack-able"**
- **Make it as easy as possible for participants to find the engagement features**



<h3 id="brainstorm">Brainstorm and Wireframe</h3>



With these goals in hand, I began experimenting with different solutions. Since this was one of my early projects with the company, I wasn’t sure how radical of a change they were open to, so **I created a set of wireframes depicting two different paths forward: a conservative evolution and a more radical transformation**. 

The first solution included much smaller enhancements, namely a hideable sidebar and improved slide navigation controls. The benefit of this design was that the learning curve for existing users wouldn’t be too steep and because the changes were smaller, the development would be less work and would move faster. The trade-off was that the participant and presenter experiences still were not very cohesive, which was one of the goals of this project.

The second solution included more radical changes, like taking apart the sidebar component and moving its resource links behind a hamburger menu and moving its engagement action buttons down below the slides. The advantage in this case was that the interfaces shared far more elements, which made the participant and presenter experiences feel more cohesive. Also, the engagement buttons, which were one of the main selling points of the platform, were more easily accessible. The drawback was that our life science experts may have a harder time finding the menu of resources behind that menu icon, and because there were more changes, the development lift would be larger and would likely take longer.


I held a whiteboarding session with the Director of Product and a few developers where we discussed feasibility and alignment with strategic objectives to identify the best path forward. 

<div class="image-wrap">
<img src="/images/projects/NextGenArray/old-interfaces.png">
</div>
<div class="caption"><i>Participant (left) and presenter (right) interfaces when the project began</i></div>

<div class="image-wrap">
<img src="/images/projects/NextGenArray/brainstorm.png">
</div>
<div class="caption"><i>Initial wireframes: Option A was a conservative evolution with a hideable sidebar and improved slide controls and Option B was a radical transformation with an engagement action bar across the bottom and a hamburger menu for additional content </i></div>



<h3 id="interview">Prototype and Interview</h3>



Based on the feedback from the whiteboarding session, **I decided to go with the more radical transformation**. I wanted to uncover possible pain points associated with this new interface before moving forward, so I made a few modifications based on our discussion, created some additional wireframes, and linked them together to create a prototype. Then I **used this prototype as a tool during interviews with four technicians** where I walked them through the main use cases for both the participant and presenter views. During the course of those interviews, I identified the hamburger menu as a potential issue for participants. Technicians were concerned that these users would continue to struggle to find relevant resources during events. As a result, I switched to a scrollable tab-style menu before applying visual design.

<div class="image-wrap">
<img src="/images/projects/NextGenArray/v2.png">
</div>
<div class="caption"><i>Updated wireframes showing the participant (left) and presenter (right) designs with scrollable menu items and increased branding space</i></div>





<h3 id="visual">Apply Visual Design and Gain Internal Support</h3>



After updating the wireframes based on feedback from the development team as well as the technicians, I brought the designs to life with visual design. During the whiteboarding session, the developers asked for help selecting a new design library because they were switching from Vue to React for the new interface, so I worked with them to select Material UI, which is based on Google's Material Design System. As I applied visual design, I leveraged as much of Material UI as I could to reduce development time later. 

<div class="image-wrap">
<img src="/images/projects/NextGenArray/visual-designs.png">
</div>
<div class="caption"><i>Designs sent out as part of company-wide survey</i></div>

Because there was a lot of hesitancy toward change across the company (and the company had less than 100 employees), I conducted a survey so a variety of stakeholders could provide feedback on the designs before implementation. **I got responses across all departments and was pleased to find that 77% of the internal stakeholders surveyed preferred the new participant experience over the existing one, and 94% of them preferred the new presenter interface over the existing one**. I also gave people the opportunity to share their favorite and least favorite parts of the new designs and added a few open-ended questions where people could share anything else they wanted regarding the redesign. After the survey was over, I shared the results with the entire company. This process helped improve transparency and made people feel like their opinions were being heard, respected, and considered, which was instrumental in getting folks across departments to support our new solution and eventually become champions for it.

There were also several valuable ideas that came out of those survey responses. I heard from many of those surveyed that they felt the presenter interface may be too cluttered or distracting for someone who is presenting, so I **introduced "focus mode" for presenters** where the branding bar, menu, and action buttons are hidden away while a user is presenting, which also makes the slides larger, reveals a speaker timer, and gives quick access to stop presenting or view questions coming in from participants.

<div class="image-wrap">
<img src="/images/projects/NextGenArray/focus-mode.gif">
</div>
<div class="caption"><i>Focus mode added for presenters as a result of survey</i></div>




<h2 id="outcome">The Outcome</h2>



After completing the redesign and getting buy-in across departments, I wrote user stories for the development team and worked with QA to oversee the implementation of the designs. **Less than two years after I started this project, all legacy platforms have been shut down and all clients are using this new solution**. I'm also pleased that as in-person events picked back up following the pandemic, the new platform has successfully supported not only in-person and virtual events but also hybrid events (some participants and presenters attending virtually while others are together in person). I also extended the designs to work responsively across mobile, tablet, and desktop devices to suit an even larger range of event types. Most importantly, not only are internal stakeholders across departments proud of the new designs, the users appreciate it too.

The redesigned interface succeeds in providing a familiar experience for participants and presenters alike, which has resulted in **reduced rehearsal time required for presenters**, especially for presenters who have previously joined events as a participant. This new design is also **more secure and saves the technicians time** because it is based on simple customization options for colors and branding rather than relying on the technician injecting custom CSS and HTML into the platform. In regards to the ease of finding engagement features, there has been anecdotal evidence that this is the case, but more data needs to be collected and analyzed, particularly regarding the number of notes taken, questions asked, etc, across event types to determine the true impact of the redesign with regard to engagement.



<div class="image-wrap">
<img src="/images/projects/NextGenArray/on-laptop.png">
</div>
<div class="caption"><i>Array's platform as of 2023</i></div>

If I were to approach a similar project in the future, I would conduct user research with external users and leverage more data, not only in the initial design phases but also for tracking the success of the project. I would look at the use of the engagement features over time to see the exact impact of the redesign as well as later design updates. I would also look at data regarding the training time for new presenters to see how much that was reduced by unifying the participant and presenter experiences.



<h3 id="lessons">Lessons Learned</h2>



* **Getting buy-in on designs from stakeholders is invaluable.** By taking the time to listen to feedback and providing transparency about the design process with a few dozen technicians and salespeople, we were able, as a company, to explain the design rationale to hundreds of clients, which made existing clients want to continue doing business with us and won us new business as well. This is part of what enabled our previously in-person event-based company to not only survive but thrive during a pandemic. By getting buy-in from the developers early and often throughout the design process, we were also able to build out the designs in record time.
* **Listen to all feedback, but take it all with a grain of salt.** You never know where a great idea could come from. In this case, I designed the "focus mode" for presenters based on feedback I gathered from people in operations and sales, and it was a huge hit with presenters. But on the flip side, people will often provide feedback based on their personal preferences or other solutions they have seen. It's my job as the product designer to never lose sight of the user needs, engineering constraints, and business objectives.

<div class="thank-line">Thank you for reading. If you are interested in my work, reach out. I’d love to learn about your project and see how I can help!</div>

<a href="#" class="cta button--fill contact-trigger js-contact">Get in Touch</a>