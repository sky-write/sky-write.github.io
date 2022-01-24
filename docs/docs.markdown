---
layout: page
title: Documentation
permalink: /docs/
---

## App Design ##

The app consists of 4 fragments that represent different screens within the app. Each fragment class has an associated class that inherits from the ViewModel. The ViewModel class is built into the Andriod SDK and is responsible for storing and displaying UI-related data. The HomeFragment is the screen where the AR messages can be viewed, therefore, it must implement the SampleRender.Renderer interface. The SampleRender.Renderer interface comes from the AR Core library and, when implemented, allows a AR messages to be displayed using the phone's camera.

![App class diagram](/assets/App-class-diagram.png)

## Database Design ##

A database is required to 

![Database design diagram](/assets/DB-design.png)

![Database sequence diagram](/assets/DB-sequence.drawio.png)