# CheckedIn

#### Technologies: HTML, CSS, Object-Oriented JavaScript, Web APIs (DOM, Web Storage)

CheckedIn is an open source, browser-based CRUD application providing users with a minimalistic platform to manage their contacts and be reminded of when to get in touch with others. 

## FAQ

### Why last initial, instead of last name? 

The currently deployed application is an MVP and functions entirely on the front end, through the use of the Web Storage API.

This means that all of the CRUD activity is stored within localStorage, which is inherently not as secure as a designated server-side DB. 

The author believes that the use of localStorage in this manner was a strategic decision that offers a great security trade-off for speedy deployment and rapid prototyping. 

**Last initial was used, in lieu of last name, in order to provide a layer of anonymity for the user given the inherent security risk with localStorage.**

### What could be done to bolster the security of user data collected in localStorage? 

The author is brainstorming ways to promote enhanced user privacy and, as of Feb 4th, 2021, **believes that the use of W3C's [Web Cryptography API](https://www.w3.org/TR/WebCryptoAPI/) coupled with [Google Firebase](https://firebase.google.com/) may be the first step towards the right direction.**   

### Will CheckedIn become a native mobile application?

Given the heightened level of isolation and disconnectedness brought about by the ongoing pandemic, the author remains convinced that a designated platform like CheckedIn may serve a tangible purpose to users and be of practical use for many, not just for those within the author's network. 

With that said, the author is open to scaling the application upon peer feedback and back end configuration. 

**As of current, CheckedIn is being developed into a mobile-responsive application available on mobile browsers (albeit it is not being planned to be scaled for native mobile platforms.**
