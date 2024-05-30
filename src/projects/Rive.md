---
title: "Rive"
summary: "animating using Rive"
image: /assets/rive-ide.png
imageAlt: "Screenshots of Rive"
tech:
  - "Rive"
  - "Javascript"
  - "iOS"
siteUrl: "#"
repoUrl: "#"
---

[link to demo animation](http://www.manjitbedi.com/projects/Rive-tests/WhiteHills)

I have been learning to how to use Rive - a tool for making animations that can be deployed to iOS, Unity, Web etc.

[Rive.app](https://www.rive.app)

I will be working on this in the short term to create some animations sequences to potentially use in the White Hills iOS app project (also in the portfolio).

I am greatly impressed by the scope of what Rive let's one to do with creating art & then animating it.

<img class="smaller"  src="../../assets/Rive-2.png">
<br/>

## Some Notes

- I went through a challenge working out to receive events in Javascript using Rive.  After much searching & reading online, here is some code that works:
<br/>
 
```
  function onRiveEvent(riveEvent) {
   // Debug code
   console.log(riveEvent.data.name);
   eventName.innerHTML = "Event: " + riveEvent.data.name;
  
   if (riveEvent.data.name == "SomeEventName"){
     // open web page in a new tab
     window.open("https://www.somewebsite.com", "_blank");
   } 
  }

  // Handle events  
  r.on(rive.EventType.RiveEvent, onRiveEvent);
```
<br/>
  
And here is a link to a test page [Rive test](https://manjitbedi.com/projects/Rive-tests/prompt-button/)