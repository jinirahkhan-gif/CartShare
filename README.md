# CartShare

CartShare is a collaborative shopping web app built with HTML, CSS, Bootstrap and JavaScript.

## Features
- Create or join a room using a unique code
- Add and remove shared cart items
- Room-specific data persistence using localStorage
- Real-time synchronization across browser tabs using the storage event
- Activity log
- Printable receipt
- Responsive layout for desktop and mobile

## Run locally
1. Open `index.html` in a browser.
2. Enter your name.
3. Leave Room Code blank to create a room, or enter an existing code to join.
4. Open the same `index.html` in another browser tab/window and enter the same room code to simulate another participant.
5. Add/remove items and observe synchronization.
6. Use **Print Receipt** to generate the receipt.

## Folder structure
CartShare/
├── index.html
├── README.md
├── css/
│   └── style.css
├── js/
│   └── app.js
└── assets/

## Deployment
The project can be deployed as a static site on GitHub Pages, Netlify or Vercel.

## Note
This version uses browser localStorage, as required by the project brief. Synchronization works across tabs/windows sharing the same browser storage. A true multi-device production version would require a backend/realtime database.
