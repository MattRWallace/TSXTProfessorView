# TXST ProfessorView
To create this extension, I started with the wonderful work done by Joshua Manigault [here](https://github.com/joshuamanigault/ASUProfessorView) to provide this functionality for ASU students.

**See Rate My Professor reviews directly in your Texas State class search!**  

This extension enhances the Texas State University class catalog by showing professor ratings and reviews from Rate My Professor right where you need them.

![Example screenshot](https://raw.githubusercontent.com/MattRWallace/TSXTProfessorView/refs/heads/screenshots/screenshots/Example.jpg)

---

## Features
- Quickly view professor ratings and reviews while browsing TXST course listings.  
- No need to visit Rate My Professor separately.  
- Works seamlessly on Texas State’s catalog search pages.

---

## Installation

### For Users (Browser Web Store)
* [Chrome Web Store - IN REVIEW]()
* [Edge - IN REVIEW]()
* [Firefox - IN REVIEW]()

### For Developers/Contributors
1. **Clone the repository** or **Download the extension files** from this repository.
2. Install dependencies
```
npm install
```
3. Build the extension
```
turbo build check-types
```
4. Find the dist folder at `extensions/<browser>/dist/` and follow the guidance to load it as a local extension for your target browser:
    * [Chrome](https://developer.chrome.com/docs/extensions/get-started/tutorial/hello-world#load-unpacked)
    * [Edge](https://learn.microsoft.com/en-us/microsoft-edge/extensions/getting-started/extension-sideloading)
    * [Firefox](https://extensionworkshop.com/documentation/develop/temporary-installation-in-firefox/)


---

## Notes
- Works on [TXST Catalog](https://reg-prod.ec.txstate.edu/StudentRegistrationSsb/ssb/courseSearch/courseSearch) pages only.  
- Make sure you refresh the catalog page after installing the extension.  
- Data comes from Rate My Professor.

---


Enjoy faster course planning with integrated professor reviews!
