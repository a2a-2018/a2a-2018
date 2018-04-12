---
layout: post
title: Usability Testing Check-in
date: 2018-04-11
tags: [assignment, usability testing, check-in]
---

**HEURISTIC EVALUATION**

We conducted 2 heuristic evaluations. For each of the heuristic violation uncovered, we assigned a severity rating and revised the design to satisfy the heuristic.

**1. Inconsistency of Notification Tab**

![Figure 1: Notification Tab Inconsistency](/img/Event7.jpg)

Problem: The notification tab opens up  a dialog box instead of a full page like the other sections. Users are confused about whether they should navigate this section in a different way compared to other sections that they have seen. Moreover, the inbox and notification sub-sections are squeezed together into one screenful, presenting users with a very crowded interface.

Heuristics Violated: Consistency and Standards. Minimalist Design.

Severity Rating: 2

Revision:

![Figure 2: Notification Tab Redone](/img/Event7b.JPG)
![Figure 2: Notification Tab Redone](/img/Event8b.JPG)

We reworked the notification section into a full page, similar to other tabbed sections. We also renamed the "Recent" sub-section to "Notifications" and "Inbox" to "Messages" to avoid confusion. Only one of the sub-sections is displayed at a time, and users can switch between using a handy tab at the top of the page.

**2. Inconsistency in Upload Workflow**




**3. Inconsistency in Back Button Placements**

![Figure 5: Inconsistency in Back Button Placements](/img/Edit1.jpg)

Problem: For most of our design, the "Back" button of each screen is placed at the upper left corner of the interface. However, for some sections, the button has been placed at the end of a field to be filled in, requiring users to spend extra time locating the simple, commonly used feature.

Heuristic Violated: Consistency and Standards.

Severity Rating: 1

Revision:

![Figure 5: Inconsistency in Back Button Redone](/img/Edit1b.JPG)

We relocated the "Back" button to the upper left corner, standardizing all parts of the interface.

**FIRST USABILITY TEST**

KY is an undergraduate senior at Williams College majoring in Computer Science. A former participant in our series of contextual inquiries, KY is a potential user - a student artist at a rural, small college who constantly seeks out new arts and artists in the vicinity. They also wish to advertise their projects, in hope of connecting with possible collaborators.

We conducted the test in Jesup Hall, where student artists typically go to for digital pre-processing needs. KY often take advantage of the high-spec, well-calibrated computers here to edit photos, videos, or posters before posting them. In their free time, they also often check for new arts and events on social media.

At the beginning of the test, we provided KY with some background on our project and instructed them to complete two tasks on the interface, thinking out loud throughout the process. We did not answer any questions they raised, and we sometimes asked our own questions to clarify their confusion with various aspects of the app. Quan was the computer, Grace was the observer, and both were the facilitator.

There were two effective strategies that we would continue using: (1) allowing KY to think out loud and (2) occasionally probing them to point at the specific features that stumped them. At the same time, there were several times where Quan interrupted Grace to write down some additional observations, or Grace interrupted Quan to work the interface in a different way. Allowing some flexibility in our testing roles is great, but for subsequent tests, it might be great to minimize such disruptive switching.

**1. Confusing icons in Feed Section**

![Confusing icons in Feed Section](/img/Discover1.jpg)

Problem: The interactive portion of each Feed post is cluttered with the "View" count and unrecognizable "Follow" icon. First-time users might be confused by all of these icons and would take some experimentation to get used to.

Severity Rating: 2

Revision:

![Confusing icons in Feed Section Redone](/img/Discover1b.png)

We simplified the possible tasks for each Feed post. Now users can comment, like, and follow a post. the follow functionality is designated with an conspicuous "Follow" button to avoid confusion.

**REVISED PROTOTYPE**

**TASK 1: Event Discovery and Notification**
The user finds an event that interests them.
![Figure 2.1](/img/Event1.jpg)

They touch the "follow" icon to tell a2a that they'd like to be reminded about the event when it draws near.
![Figure 2.2](/img/Event2.jpg)

When it's time, the user receives a notification about the event.
![Figure 2.3](/img/Event3.jpg)

They open the notification on their phone and a2a opens.
![Figure 2.4](/img/Event4.jpg)
![Figure 2.5](/img/Event5.jpg)
![Figure 2.6](/img/Event8b.jpg)

They can also touch the notification about the event, which will bring them to the Event post.
![Figure 2.7](/img/Discover1b.png)
