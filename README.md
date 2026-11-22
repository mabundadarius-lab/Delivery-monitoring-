DropTrack: Delivery Tracker
An interactive, animated delivery tracking app built with plain HTML, CSS and JavaScript. No build step or dependencies.

Features
Live map visualisation: SVG city map with an animated route, a moving courier, pulsing destination, ambient traffic and drifting clouds
Order status stepper: Ordered, Packed, Out for Delivery, Delivered, with live status text and tap-to-jump
Estimated arrival: live ETA, arrival clock time, distance remaining and a progress meter
Courier contact: call screen with ringing animation, mute/speaker toggles and call timer, plus a chat with typing indicator, quick replies and context-aware courier answers
Interactive map: zoom in/out, follow-courier mode, drag to pan, and tappable pins
Simulation controls: play/pause, 1x/2x/4x speed, and a timeline slider to scrub through the delivery
Delivery preferences: leave-at-door and notification switches, courier note, tipping
Order details: expandable item list with totals that include the tip
Track another order: enter a code (DLV-1042, DLV-2077, DLV-3150) or use the quick chips; invalid codes shake and show a message
On delivery: emoji confetti, delivered banner and a star rating
Share: copies or shares a tracking link
Accessibility
Real buttons and labelled inputs, tab/tablist roles with arrow-key support, switch roles, live regions for status updates, Escape closes dialogs, visible focus rings and reduced-motion support.

Customise
Orders, items, couriers and the route are plain data at the top of the script in index.html (ORDERS, ROUTE, DURATION).

Run locally
Open index.html in any browser.

Deploy
GitHub Pages: Settings > Pages > deploy from the main branch, root folder.
Vercel / Netlify: import the repository; no build settings needed
