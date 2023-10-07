# Text Editor

## Description

Using IndexedDB and localstorage, and a custome service worker, we deploy a PWA app that can run offline.
The app mimic a Text Editor using the code mirror themes, and fetches the text data from its contents and displays them.

## Tech stack

- Node.js
- Express.js
- IndexedDB (idb)
- Webpack

## Installation

<pre><code>npm run start </code></pre>

## Test

Test by doing the following

- Open the text editor and add some text
- close the app or refresh it and see how the text is still saved
- install the app on your computer and see how you can continue to use it even when offline!

## Screenshots

![App on computer](screenshots/Screenshot%202023-10-07%20at%208.57.23%20AM.png)

![jate database in indexedDB](screenshots/Screenshot%202023-10-07%20at%208.56.18%20AM.png)

![jate database in localstorage](screenshots/Screenshot%202023-10-07%20at%208.56.34%20AM.png)

![jate Service worker](screenshots/Screenshot%202023-10-07%20at%208.56.41%20AM.png)

![jate Manifest](screenshots/Screenshot%202023-10-07%20at%208.56.46%20AM.png)


## License

<img src="https://img.shields.io/static/v1?label=License&message=MIT&color=GREEN"/>
