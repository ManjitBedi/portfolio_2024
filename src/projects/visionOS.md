---
title: "visionOS"
summary: "working with visionOS"
image: /assets/visionOS.png
imageAlt: "Screenshot of visionOS"
tech:
  - "Swift"
  - "RealityKit"
  - "Reality Composer Pro"
  - "visionOS"
siteUrl: "#"
repoUrl: "#"
---

### Project Description

July 2024

<video width="273" height="204" autoplay loop>
  <source src="/assets/visionOS.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

I am currently working with getting the "White Hills" app to work natively in [visionOS](https://developer.apple.com/visionos/).  There was some challenges along the way - which is not unexpected.  I documented some of the technical details here:

[Notion page](https://false-balmoral-27e.notion.site/Porting-UI-Kit-apps-to-visionOS-8f53bd7e66c74a07872c86d929eb4fa1?pvs=4)

I am now about to work on adding more 3D content into the app; I am exploring the use of [Reality Composer Pro](https://developer.apple.com/augmented-reality/tools/) (RCP) to create 3D scenes & use shaders to enhance the visual experience.  I did some prototyping to go through the workflow to incorporate content made in RCP.  I am also keen to try out the new timeline possibilities in RCP version 2 as I have worked with the [timeline feature in Unity](https://docs.unity3d.com/Packages/com.unity.timeline@1.8/manual/index.html) before.

When you create an app to work in visionOS, you need to think about the presentation & the use of volumetric content.  Considering that I have an existing app, I want the existing apps views to work primarily in a window & bring new content into the app that is presented in 3D.  This is definitely going to be an iterative process. Also windows are presented in the line of sight for the viewer - the viewer is in control of arranging windows when there are multiple windows. I need to see if this has changed with more layout choices in visionOS 2 🤔. 
 
Working with visionOS, you really want to be building scenes using SwiftUI; I plan to over time convert the app from UIKit & storyboards to SwiftUI.
