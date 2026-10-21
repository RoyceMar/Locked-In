# LOCKED IN // OS 🔒

**A gamified focus and productivity app that runs in the browser.**
Start a focus session, earn XP, keep your daily streak alive, and block out the world with procedurally generated brown noise and a full-screen "God Mode."

## Features

- **Focus timer with XP and levels:** every completed session earns XP toward your next level.
- **Daily streaks:** keep a streak going by focusing every day.
- **Brown noise generator:** procedurally generated with the Web Audio API, so there are no audio files to load.
- **God Mode:** a distraction-free full-screen mode built on the Fullscreen API with animated CSS.
- **Cloud sync:** sign in with email and password, and your progress syncs in real time through Firebase Firestore, with a localStorage fallback when you're offline.

## Tech

JavaScript (ES6+), HTML/CSS, Web Audio API, Fullscreen API, Firebase Authentication, Cloud Firestore.

## Run it

Open `index.html` in a browser. That's it: it's a single file with no build step.

> The Firebase config in `index.html` is a public web-app identifier (that's how Firebase web apps work). Access to data is controlled by Firestore security rules, not by hiding the key.

---

Built by **Royce Marquez** · [LinkedIn](https://www.linkedin.com/in/royce-marquez/)
