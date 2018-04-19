---
layout: post
title: HiFi Prototype
date: 18-04-19
tags: [assignment, hifi, prototype, high-fidelity]
---

### The Prototype

Our InVision prototype can be found [here](http://invis.io/NGGTUYQV3FW). The following is an overview of our high fidelity prototype:

![Fig. 1: High Fidelity Prototype Overview](/img/Overview.png)

**Task 1: Event Discovery and Notification**

A user browses their feed, which is populated with artwork, discussions, and events related to interests that they list upon first login (and which they can modify under settings), as well as to groups that they follow.

![Fig. 2.1: A populated feed](/img/Feed-Main.png)

When a user sees an event for which they'd like to be notified, they press the star icon.

![Fig. 2.2: The user stars the event they'd like to follow](/img/Feed-Starred.png)

When the time comes, a2a notifies them of the upcoming event. When the user opens the app, they are brought to the notifications page.

![Fig. 2.3: An overview of the notifications page](/img/notifications.png)

If they touch the thumbnail for the event, they can view the event page for more details.

![Fig. 2.4: Detail of a post](/img/Feed-Post.png)

**Task 2: Art Showcasing**

When a user would like to upload an image, they touch the "plus" icon, which will bring them to the following page:

![Fig. 3.1: Initial upload page](/img/Upload1.png)

Pressing the peach-colored "choose file" button calls a menu which allows them to decide from where they'd like to take the art file to upload.

![Fig. 3.2: Menu for selecting file location](/img/Upload2.png)

The app will communicate with the selected source, allowing the user to view their files and select one.

![Fig. 3.3: Overview of files in Drive](/img/Upload3.png) ![Fig. 3.4: Selected file in Drive](/img/Upload4.png)

The user may also input additional information, such as a title for their work, a description, and some tags to help users find the piece via search bar. Upon satisfaction, the user presses the upload button and their work is shared with the community.

![Fig. 3.5: Uploaded file, empty input fields](/img/Upload5.png) ![Fig. 3.6: Uploaded file, filled input fields](/img/Upload6.png)

### Implementation Decisions / Design Changes

**Feed Post Buttons**

Some usability test participants commented that they could not recognize the Follow button on a post, confusing it with a Seen icon indicating view counts. We reworked our Follow button to a Star button for clarity, and also added a real Seen icon to let users know how well posts reach other users. We also recolored all interact-able buttons to peach (the app's accent color), and other icons grey.

![Fig. 4.1: A populated feed](/img/Feed-Main.png)

**Upload Text Fields**

We changed the appearance of all text fields in the upload page from text boxes to borderless fields, indicated by simple lines under the texts. This helps preserve consistency with other parts of the app, such as the onboarding text fields.

![Fig. 4.2: Uploaded file, empty input fields](/img/Upload5.png)

**Things We Decided Not to Implement Yet**

There are a few pieces of our app which, while important to the overall product, are not relevant to our two main tasks. The entire functionality relating to groups, while important for establishing how the events which users can follow appear, are not important to the discovery and notification itself, nor is it relevant to art showcasing through the app. Profile editing is similarly important, but our main focus at this point is the primary task of showcasing that art, not editing what's already been uploaded. The workflow for partaking in discussions is also not included. For the sake of creating high-fidelity prototype in four days without going overboard, we prioritized things that we thought a user would more directly encounter while performing our two main tasks.
