---
layout: post
title:  "Final Release"
date:   2022-05-01 09:20:46 +0000
---
Hello everyone.

We are excited to showcase our Final Release and third demonstration of our application:

<iframe width="560" height="315" src="https://www.youtube.com/embed/Puz4DBV01I0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## App Updates ##
### Notifications ###

### Holiday Reminder Notifications ###

### Hashed Postcodes ###

When a user sends a message to a postcode, it is first hashed by the client then sent to the database server to be stored. When a user's device checks if messages have been received, they will hash their own postcode and compare that with the contents of the database.

This improves privacy significantly, making it impossible for us the developers and other users to read user postcodes directly.

### PBR Image Textures ###

Another Improvement to the app is the use of PBR Image Textures in rendering the banners. AR Core supports roughness, metalness and ambient occlusion data to be encoded into the Red, Green and Blue channels of an image. This is then mapped onto a banner, making the lighting look much more realistic.

For some of the banners, adding PBR image textures has created really subtle lighting improvements, but for others, there is a significant improvement. In particular, the balloons on Congratulations look a lot more realistic by being able to reflect a lot more light. Other significant improvements are the eyes on the Get Well Soon teddy bear and the snowman in Merry Christmas.

![happy birthday banner](/assets/happy-birthday.png)
*Comparison to show the effect of adding PRB Image Textures*

### UI Improvements ###

### Watson TTS ###

## User Stories ##

Previously, the following three user stories have been implemented in both the Minimum Viable Product (MVP) and the Beta Release:
 
1. As a user, I want to use this app on my Android device.
2. As a user, I want to save pictures of AR messages, so that I can view them later.
3. As a user, I want to see a message 100ft up from the ground.
4. As a user, I want to send AR messages to friends and family, so that I can communicate with them in a unique way.
5. As a user, I want to receive AR messages from friends and family, so that they can communicate with me in a unique way.
6. As a user, I want to change the text size of the app, so that I can easily read any text.

Currently, the following user stories have been implemented in the Beta Release:

1. As a user, I want to be notified when there are new messages sent to my area, so that I can keep up to date with new messages.
2. As a user, I want to be able to change my notification preferences, so that I don’t receive unwanted notifications.
3. As a user, I want to be prompted to send a message at holiday events, such as Easter of New Year, so that I don't forget to send out messages.
4. As a user, I want to have the App read out messages using IBM Watson, so that the app is more accessible to me.

## Response from Client ##
> AMAZING!!!! GREAT WORK!!

\- John McNamara, IBM