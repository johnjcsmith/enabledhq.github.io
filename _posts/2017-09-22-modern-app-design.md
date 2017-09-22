---
layout: post
date: '2017-09-22 17:09 +0930'
author:
  - linh
main-category: technology
categories:
  - technology
published: false
title: 10 plus 1 commandments for the modern mobile app designer
---
 
“My love is alive
Way down in my code
Although we are miles apart
If users ever need a helping hand
I'll be there on the double tap
Just as fast as I can

Don't you know that 
There ain't no resolution high enough
Ain't no bandwidth low enough
Ain't no screen size wide enough
To keep me from getting to your app”

Shout out to Medium’s recent release notes for the inspiration behind the prose above. App makers and designers can and should show their human side and be more user-focused. But more on that later in the article. 

So here are some simple, yet informative rules for the modern mobile app designer.
Don’t hide features behind gestures
 
In a multi-touch UI many apps choose to hide features behind gestures, such as a long-press or two-finger-tap. It’s fine to use gestures like this to trigger features, but always make sure those features are also accessible with a visible control.

Your UI is the only way for you to inform your users about features. If you don’t have a visible control for your feature then it might as well not exist.

The exception to this is when a particular gesture is used in a consistent manner across the entire operating system and your app uses standard operating system controls. In this case users can expect the same gestures to work if they are used to them elsewhere [See Build to the platform]. 

Hiding features behind gestures also makes it more difficult to support accessibility features in your app, which the operating system might otherwise give you “for free.”

For example, in the stock Mail app on iOS, the delete and archive features are hidden behind a long press.






Get rid of features
If you have trouble finding a place to put features then it could mean it’s time to start dropping features and try to streamline your application. 

Think about Google Maps  and how many hidden features there are. The app is a combination of location info,history; directions; local listings; as well as things like social sharing.


 








Some core features of Google Maps. 
So unless you’re Google and have the manpower to merge different platforms into a single app, resist putting that extra feature in altogether. Many of the best applications have a singular focus and limited feature set.
Culling features doesn’t make your app worse. It makes it better by giving your core features the attention they deserve and making your app easier for your users to use.
Don’t use hamburger menus
Following from the section above, if your app has a lot of  features, it’s tempting to use hamburger menus. Data has shown hamburgers are less efficient, have low discoverability and may clash with the platform navigation patterns. 
It’s okay to use it if “the menu items you’re going to hide behind the hamburger icon fall below the 80% of regular usage.”
In other words, if the user can accomplish the main task from the main screen, then the secondary items like settings could go behind the hamburger menu. The taxi booking app GoCatch is a good example for this.

What happens when you tap on the hamburger icon

If your app is really complex and culling features isn’t feasible, use hamburger alternatives such as: tab menu, tab menu with “More” (e.g. Facebook app), horizontal scroll menu, drop down menu etc. 
Support accessibility
Humans are not all the same and out of the box, they come configured with different abilities. So make sure your application takes this into account.
Some simple things you can do include increasing colour contrast for better readability of text, or accounting for people with colorblindness.
Hence, never rely just on colours to communicate different states, and use extra cues such as icons or text to signal different states (as shown below).

 Source: Smashing Magazine 

For users with special needs, try to leverage what is given to you by the platform. iOS, for example, will be able to read most of the screen for users with low vision — if you use the standard controls. You can also annotate UI controls with labels for screen readers to use.
Use animation to be helpful
Motion helps your users build a spatial map of your application. When a user taps a button and a screen pushes in from the right edge — and the back button appears on the left edge — the user is aware on some level that they have navigated more deeply into your app.


Animation helps with spatial awareness. Source: Nick Babich
Most motion comes for free if you stick to standard operating system navigation. But if you’re building your own, always ask yourself: Does this animation help the user or does it turn your app UI into a Disney Movie? 
Avoid lengthy in-app copy
Given the limited screen size on mobile, users don’t want to spend time reading too much text, especially when they’re trying to do something quick. 
Simplify the copy in your app and make sure it’s still approachable, useable, and understandable. 
Take a look at how cluttered this in-app copy is. App functionality aside (or the lack thereof), the amount of text and its ambiguity is quite off-putting. 







Virgin Money app

Avoid pop-ups unless absolutely necessary
Many users will just tap whatever button pops up on an alert without reading it, just to get it out of the way (e.g. asking users to rate the app). 

You don’t want to be this app in the user’s eyes. Source: Usability Geek

So resist prompting them unless it’s absolutely necessary. Example situations where a pop-up alert is acceptable:
Ask users to agree to terms and conditions
Ask for critical permission in initial launch, e.g. access the camera if it’s a photo-taking app
Delete important things, e.g. account

When you do use in-app pop-up alerts, keep them short and in-context, i.e. relevant to the task at hand. 
Avoid generic buttons like “OK,” “Cancel,” and “Yes” or “No.” Instead, write the specific action that will occur when the button is pressed, e.g. “Delete,” “Upload,” and so on.

Source: Think with Google

For secondary alerts or those that are not mission-critical, consider non-modal notifications, i.e. those that don’t force users to interact with them before continuing. 
For instance, status alerts like completed download, successful submission etc. 
Also, instead of having users confirm every action with an alert, you should provide them with the ability to undo their actions, as shown below.

Source: Think with Google

A note about error alerts: if you have to use pop-up alerts, tell users what to do to fix the problems. Don’t be like this…

A user may ask: “What went wrong?” “How do I fix this?” Source: GitHub
Don’t use “Bug fixes and performance improvements” in your release notes, ever
 
This is a rare chance to communicate directly with your users! See the difference between a “filler” release note and good ones below.


Spot the “bad guy”.
 
One the most memorable app release notes I’ve come across is from Medium. They have been cleverly mixing storytelling and useful information, as shown in the example below.
 

The good app release notes
 
Medium even has an archive of their app release notes, recognising that writing these is not for the sake of filling the space.
Be smart about user feedback
Listen to your users but don’t follow what they say, be opinionated about how your app should work
 
Your users are using your application. That is, they are paying you for your decisions, your thoughts, and your design. Don’t always defer to what they say when they have suggestions. 

If a user wants a particular feature then think about why they want it and don’t blindly implement feature requests. Use them as an opportunity to re-think the fundamental workflow of your app and what it is they are trying to do. 

In other words, try to understand their Jobs-to-be-done.

Perhaps your users would be better of with a different app entirely? If so, don’t hesitate to recommend it to them.
Be smart about user testing
Watch users use your app without any interaction, prompting, or discussion from you. Don’t talk to users afterwards, just learn from observing. 

Source: Bug Bash
To further prevent researcher bias, reframe the purpose of your research so as not to “validate” the design, but to “test” it. 
Remember: “If a usability study found nothing to improve in a design then that only proved one thing: that the test was done wrong.”
Build to the platform 
Whether you intend to build your app on a single or multiple platforms, it’s always a good idea to know the specific design conventions for each platform (e.g. iOS, Android, Windows Mobile). 

From there, you can decide between these options:
Strike a balance between adhering to platform conventions and branding conventions (e.g. Facebook app)
Stick to platform conventions (e.g. WhatsApp app)
Stick to branding conventions (e.g. Instagram app)

This depends on things like how complex your app is and how important it is to your overall digital strategy. 

For example, the Australian Taxation Office app has customised UI elements using platform-specific conventions. Notice how the toggle design feels consistent with the respective mobile OS.


How a common screen on the ATO app looks on three different mobile platforms.
Final words
It’s easy to forget who we’re designing for when they’re not there. So here’s a simple tip: test your app with your near and dear. If you’re building a B2B app, ask yourself: “Do I actually want to use this myself?”



