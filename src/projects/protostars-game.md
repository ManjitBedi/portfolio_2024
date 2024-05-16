---
title: "Protostars"
summary: "An game of exploration for children"
image: /assets/proto-stars-game.png
imageAlt: "Screenshot of Protostars"
tech:
  - "Unity"
  - "C#"
siteUrl: "#"
repoUrl: "#"
---

### Project Description

May 2021 to Sept 2022

I was part of a 2 person developer team working on this game at [Evolved Play](https://www.evolvedplay.com) working with a team of game industry veterans; the creative leads were [Kevin Caldwell](https://www.linkedin.com/in/kevin-c-1630824/) & [Sandee Vallee](https://www.linkedin.com/in/sandeevalle/) with game design  by [Kelly Tran](https://www.linkedin.com/in/kmichaelatran/) - it was a very collaborative process.   The game was going through iterative game play refinement & testing with young players & their families; it was coming along quite nicely if I may say so.  The project was being developed for mobile first.

One of the major features that I was working on a space map level using hexagonal tile maps:

- it is worth mentioning, the game play here went through many revisions following the user testing with young players
- in the space map, the player would tap to move to available position with the ultimate quest to find the portal to the next level
- obstacles could be removed by using actions associated with available energy
- there was performance issue with path finding which was resolved by using the Unity jobs system & this incredible asset called [Any Path](https://bartvandesande.nl/anypath/index.html); doing path finding is an expensive task - the available paths would be computed every time that a player moved

