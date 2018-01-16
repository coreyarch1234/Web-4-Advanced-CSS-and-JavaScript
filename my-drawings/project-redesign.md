# Tangent

Tangent is an iOS app that allows you to convert handwritten math equations from your notes to beautifully typed digital text.

# How it works

I want to help you better document your notes digitally.
I have made the transfer process as easy as snapping a picture.

Simply, take a picture of the specific equations or math problems from your notes and Tangent converts the image to text on your phone.

We aim to further our goals by actively developing the following features in our upcoming updates:
1. Copy and paste equations by pressing 1 button.
2. Search through math problems you have saved.
3. Generate practice tests from math problems in your library.


![ScreenShot](https://i.imgur.com/7rLxAHYl.png)

![ScreenShot](https://i.imgur.com/OWFDFz2l.png)

![ScreenShot](https://i.imgur.com/dMlbVosl.png)

![ScreenShot](https://i.imgur.com/6iM16Izl.png)

# Technology and Process

I developed custom interface with React Native Camera enabling micro-measurements with > 90% accuracy.

I architected a Node.js backend with Mathpix and KaTeX APIs to convert 800+ raw image data objects to rendered html.


# What I want to Improve

The core functionality of the app works, however, there are some foundational weaknesses that must be
addressed ASAP in the next update. These are:

1. Adding a loading screen once a user takes a picture.
    - Right now, when a user takes a picture, they will have to wait a couple of seconds before they are sent to the next screen. Without feedback, they will think the app froze.

2. Adding a loading screen after a user submits their problem info for the same reason as 1.

3. Adding a better onboarding system. When the user first opens the app, they are shown 2 rows explaining what to do. One says to tap the camera icon to take a picture, but the user will believe that they have to tap the row itself.

As for pure design changes:

1. The problem list screen that displays the title and subject of the problem must be redesigned. I want to make it pop out more and look more attractive.

2. I want to redesign the problem detail page that shows the digital text. I can add different text designs using html since the display is a webview.

The areas I want to improve for the above design changes are:

1. Layout
2. Color
3. Typography
4. Placement of items on the screen. 

I want to add these core changes that will drastically improve the UI:

1. Add a delete feature if a user wants to get rid of a post.

2. Add an edit feature to the problem list page in case a user made a mistake. Ideally, this would be implemented when the user is first shown the digital text, but I am not sure if that is feasible within this time-span.
