# GenreMash Cinema — Streaming + Movie Ticket Booking

A responsive, dark cinematic front-end inspired by the layout patterns of streaming services and movie-ticket platforms. It is an academic prototype, not an official Amazon Prime Video or BookMyShow product.

## Requirements
- Node.js 18+ installed
- VS Code (recommended)

## Run in VS Code (Windows)
1. Extract the ZIP.
2. Open the extracted `GenreMash-Cinema-Prime` folder directly in VS Code. The `index.html` and `package.json` files are at the top level of this folder.
3. Open **Terminal → New Terminal**.
4. Run:
   ```powershell
   npm start
   ```
5. Open http://localhost:4200 in your browser. Keep the terminal open while using the site. Stop with `Ctrl+C`.

No `npm install` is required; the local server uses Node.js built-in modules only.

## Features
- Cinematic hero and featured titles
- Trending, popular, new release and top-rated rows
- Search and genre filters
- Movie details modal, demo trailer preview, and My List (localStorage)
- Movie-ticket showtime search with demo theatre/time options
- Interactive seat selection and booking summary
- Simulated payment flow; no real money is charged
- My Bookings history saved in localStorage
- Movie Studio concept generator and saved concepts
- Responsive desktop/tablet/mobile styling
- Sign-in and registration screens with email validation, password minimum of 7 characters, confirmation matching, and browser-local demo accounts
- Locally bundled poster crops derived from the reference screenshot provided in the conversation

## Important limitations
- This is a client-side academic prototype. Movie metadata and showtimes are sample/demo data.
- No licensed movie streams, live cinema inventory, production-grade server authentication, online payment gateway, or cloud database is connected. Login and registration are browser-local academic demos; passwords are hashed with Web Crypto before local storage, but this is not a production authentication system.
- Browser localStorage keeps lists/bookings only on the current browser/device.
- Poster thumbnails are cropped from the user-provided design reference and are low-resolution visual placeholders. Replace them with licensed poster assets before public deployment.
