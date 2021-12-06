---
layout: post
title:  "Minimum Viable Product"
date:   2021-12-03 09:20:46 +0000
---
Hello everyone.

We are excited to showcase our first demonstration of our application:

<iframe width="560" height="315" src="https://www.youtube.com/embed/lsZOr8O476I" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

The application currently has five different fragments:
- Gallery
- Notifications
- Home
- Message
- Settings

## Fragments ##
### Gallery ###
The Gallery fragment allows you to view images that you have taken using SkyWrite. You can click on an image in the grid to enlarge it and click again to minimise it again. Currently there is no animation for enlarging and minimising, but this will be added in the future.

### Notifications ###
The Notifications fragment is not implemented yet but in the future it will display notifications when a user sends to a postcode. When a user sends a message to a given postcode, the users in that postcode will receive a notification saying that a message has been sent to that postcode, and they can view it.

### Home ###
The Home fragment is where users can view the messages and take photos. It will search for a plane (i.e. the ground), and once a plane has been detected, the user can tap on the ground to place an anchor to keep the 3D message in place. Then the user can move their camera up to view the message in the sky. In the future the anchor will be automatically placed.

### Message ###
The Message fragment is currently is not fully implemented but users will be able to send a message to a given postcode in the future. The user can currently click on a selection of messages and input a postcore. In the future, when the user presses send, it will store this in a database, for other users to then retrieve from.

### Settings ###
The Settings fragment is not implemented but in the future the user can change the settings such as theme and how frequently to update the messages.

## User Stories ##
The following three user stories have been implemented in the Minumum Viable Product (MVP):
 
1. As a user, I want to use this app on my Android device.
2. As a user, I want to save pictures of AR messages, so that I can view them later.
3. As a user, I want to see a message 100ft up from the ground.

Additional user stories:

1. As a user, I want to change the text size of the app, so that I can easily read any text.
2. As a user, I want to send AR messages to friends and family, so that I can communicate with them in a unique way.
3. As a user, I want to be able to change my notification preferences, so that I don’t receive unwanted notifications.
4. As a user, I want to receive AR messages from friends and family, so that they can communicate with me in a unique way.

Sequence Diagram:

Retrieve all message
Add a banner
Retrieve all banners

## Response from Client ##
> In terms of suggestions for evolution - of course we spoke of incorporating Watson Speech to Text - so users can select the type of message they want - and then choose the particular message from the returned options.
>
> Also maybe it might be worth looking into if its possible to make the messages more animated :)
>
> And lastly - would it be possible to add a Text to Speech component so that Watson reads out the message as you pass through the notification range. 
>
> Wonderful work folks!

\- John McNamara