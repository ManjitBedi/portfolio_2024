---
title: "Curate Alpha"
summary: "Curate is a unique project that is an audio app that can be experienced & also used to create audio mixes"
image: /assets/curate-alpha-ios.png
imageAlt: "Screenshots of Curate"
tech:
  - "SceneKit"
  - "Shaders"
  - "Superpowered SDK"
siteUrl: "#"
repoUrl: "#"
---



I have been on & off working on this  project from 2016 to 2022. This app is written in Objective-C & Swift for iOS.   This a project conceived by the artist [MeLo-X](https://en.wikipedia.org/wiki/MeLo-X).  with [Lou Auguste](https://www.linkedin.com/in/lou-auguste).  Lou is the show runner / producer. 

<a href="https://apps.apple.com/ch/app/curate-alpha/id1049350366?l=en"><img src="../../assets/Download_on_the_App_Store_Badge_US-UK_RGB_blk_092917.svg" alt="download app" style="height:60px;"></a>

The original app was created by another developer Kyle Truscott. The app displays a 3D scene
showing a 3D model; the [SceneKit framework](https://developer.apple.com/scenekit/) was used for this.

You interact with the UI by dragging with one of more fingers on the "gem" to make real-time audio effects changing the audio output as audio is playing.

When changing the playing song, the shape would rotate to a new position to indicate a different track was playing.

Originally when I joined the project, I was asked to work on the following features & enhancements:

- add more real-time audio effects using the [Superpowered SDK](https://superpowered.com)
- add support for [Spotify using the iOS SDK](https://developer.spotify.com/documentation/ios)
- add a YouTube section video section - this is descoped for now
- changes to the app to be able to download content from the cloud.
- save & export mixes
- add inter-app audio support using [Audiobus](https://audiob.us) - we were assisted on this by the very talented [creative technologist Peter Courtemanche](http://absolutevalueofnoise.ca/?about#)
    - using inter-app audio, the output could be routed to apps like [Garage Band](https://support.apple.com/en-ca/guide/garageband-iphone/chse67d3af5f/ios)
    
    
There was already some real-time effects associated with gestures in the app.  I added a new scene for debugging to test the effects; Melo-X actually quite liked this change & we made it part of the app release after giving it some design attention.
    
I asked a colleague [Craig Shaynak](https://www.kingswell-productions.com), who is an audio expert, to take over some of the audio development work as it is quite specialized knowledge.
    
The Spotify integration got de-scoped for two reasons:
    
  - the Spotify SDK at the time of summer 2016, was not ip6 compliant; the app
    would have been rejected by Apple if it was using that version of the Spotify SDK
  - manipulating the Spotify streaming audio required getting  approval  from Spotify
