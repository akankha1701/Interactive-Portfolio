# Akankha Interactive Portfolio — Internship Task

## 1. Task Objective
The original static portfolio was upgraded with plain JavaScript to demonstrate DOM manipulation, event handling, dynamic UI updates and basic animations.

## 2. Files
- `index.html` — semantic page structure and interactive elements.
- `style.css` — responsive UI, cards, animations, dark mode styling and mobile navigation.
- `script.js` — all JavaScript interactions.
- `profile.png`, `about.png`, `image1.png`, `image2.png`, `image3.jpg` — supplied visual assets.

## 3. Interactive Features Implemented
1. **Mobile navigation menu** — opens/closes on small screens.
2. **Dark mode** — toggles the theme and saves the preference using `localStorage`.
3. **Typing animation** — changes the hero text between multiple phrases.
4. **Scroll reveal animation** — sections/cards animate into view using `IntersectionObserver`.
5. **Animated skill bars** — progress bars expand when the skill cards enter the viewport.
6. **Active navigation highlighting** — the current section is detected while scrolling.
7. **Project detail modal** — each project opens a dynamic details popup.
8. **Contact form validation** — validates name, email, subject and message using JavaScript.
9. **Back-to-top button** — appears after scrolling and smoothly returns to the top.
10. **Dynamic copyright year** — JavaScript inserts the current year automatically.

## 4. DOM Manipulation Used
The JavaScript uses methods such as:
- `getElementById()`
- `querySelectorAll()`
- `classList.add() / remove() / toggle()`
- `textContent`
- `innerHTML`
- `dataset`
- `addEventListener()`

## 5. Responsive Design
The layout uses CSS Grid, Flexbox and media queries. The navigation changes to a mobile menu, while skills/projects collapse from multiple columns into one column on smaller screens.

## 6. Validation and Debugging
The contact form prevents the default submit action, checks each required field, displays field-level error messages and shows a success message after valid input.

## 7. Optimization Choices
- JavaScript runs after `DOMContentLoaded`.
- `IntersectionObserver` is used instead of continuously calculating element positions during scroll.
- Passive scroll handling is used for the back-to-top visibility check.
- `prefers-reduced-motion` is respected in CSS.
- Theme preference is stored locally instead of requiring a server.

## 8. How to Run
Keep all files in the same folder and open `index.html` in a modern browser. No framework, package installation or server is required.

## 9. Important Note
The contact form is a frontend demonstration. It validates the input but does not send email because no backend/email API has been connected.
