---
title: "Home page hacking with PixiJS"
summary: "exploring web tech to create animation"
image: /assets/home-page-1.png
imageAlt: "screenshot of home page"
tech:
  - "PixiJS"
  - "Typescript"
  - "Node.js"
siteUrl: "#"
repoUrl: "#"
---

### Project Description

[My home page](https://www.manjitbedi.com) - check out the bouncing animals.

I have been hacking parts of my web-site. In May 2024, I started rebuilding the home page using [PixiJS](https://www.pixijs,com).

It has been interesting & took some time; additionally, I opted to use [Node.js](https://www.nodejs.org) with [Typescript](https://www.typescriptlang.org) & [Webpack](https://www.npmjs.com/package/webpack). It took some time to get it configured and to build nicely. Like one thing, I did not want to have all the assets appearing in the root folder.  The page is set up such that the HTML is over top of the HTML canvas where PixiJS is doing it's stuff.
I wanted to keep the project organized & modular with multiple Typescript modules & having a css page.

Once that was done, I could focus on creating a little animated scene in PixiJS.  This involved loading textures, creating sprites & doing some animation in the ticker callback to update the page.
 
Working with PixiJS was familiar & also different.  I know enough now to do more with it 👍🏽. 
 
```
// Listen for animate update
app.ticker.add((time) => {
  // Continuously rotate the container!
  // * use delta to create frame-independent transform *
  container.rotation -= 0.01 * time.deltaTime;

  UpdateWorld(app, time);
  UpdateAnimals(app, time);
});
```
<br/>  
   
I created a starter project & made it public in [GitHub](https://github.com/ManjitBedi/Pixi-Node-starter).

<br/>  


![home page code](../../assets/home-page-code.png)

![home page screenshot 2](../../assets/home-page-2.png)