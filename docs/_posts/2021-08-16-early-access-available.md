---
title: "Early Access Now Open"
date: 2021-08-16T07:00:00-05:00
categories:
  - blog
tags:
  - release
  - update
  - early-access
---

I am pleased to announce that RPG Squire is now available for Early-Access availability!

## What Is Working
* GitHub Account Login
   * At the moment, OAuth with a GitHub user account is the only login mechanism.
   * Public user information only (email, public name, homepage, etc).
* The Squire Game System (SGS) is up and running well!
   * Characters system is working really well!
   * Custom images for character portraits.
   * Skill list with dynamic updating and dice rolling
   * Passive ability list

## What Needs Work
* Pathfinder v1 game support
   * The character sheet is pretty much complete, with a fully fleshed-out setup for character progression and class implementation (including all skills, basic combat and movement actions, and other global abilities from the Pathfinder v1 ruleset).
   * The database layout is almost done. The "Alchemist" class categories are the initial testbed for ensuring that it is easy to find/import what you need from the database for the Pathfinder ruleset. That layout will be getting duplicated for all the other classes in the near future as well.
   * This database needs flesh! Right now the skeleton (directory heirarchy and organization) is pretty much all that is there (except for the Languages category - everybody needs to learn to speak first after all!). Please start assembling abilities and classes on your character manually, and then click the button to submit them up to the database!
   * I recommend using the [d20pfsrd](https://www.d20pfsrd.com/) website when assembling your class and abilities.
* Mobile Phone support is nearly there!
   * The mobile detection system is working well so far, and most of the pages have an alternate layout for mobile-usage.
   * The top-header on the main page still needs the page list collapsed down into a single menu button, and we might need to reduce the default font size for mobile devices as well. Still looking at this...
   * **REMEMBER**: The laptop/phone button in the upper-right corner of the app lets you switch between desktop/mobile views really easily!
* Known bugs
   * The "action" button on brand-new items sometimes does not point to the new item until the list is refreshed.
      * I have figured out the source of the problem, but it required re-working quite a bit of how lists are handled, so it will take some time.
      * WORKAROUND: Change tabs back and forth to refresh the list after creating a new item.


## What is Coming Next!
* Starfinder v1 game support
   * The database and character sheet are slowly being assembled, but Pathfinder v1 support is the main focus right now.
* A "Play Game" view.
   * While the "Edit Character" view is perfectly fine to use when playing a game, I am prototyping a new page layout that is a bit more streamlined.
   * This page will have support for custom environment backgrounds, mood music, and more.
* Character Sheet Printing
   * Use RPG Squire to manage your character between sessions, and then just bring a print-out to your next game session!

---
~~ Ken Moore ~~
[RPG Squire](htttps://rpgsquire.com)
