Readme · MD
# Animations & UI Feedback
 
A single-page demo built with Tailwind CSS showing common UI animation and feedback patterns: loading states, hover effects, notification badges, and staggered reveals.
 
## Sections
 
1. **Built-in Animations** — animate-spin, animate-ping, animate-pulse, animate-bounce
2. **Button Animations** — hover scale, color, rotate, and translate transitions
3. **Card Animations** — hover lift, group-hover icon effects, animated border reveal
4. **Notification Badges** — ping/pulse/bounce used as attention indicators
5. **Loading States** — skeleton loader, spinner button, bouncing dots
6. **Staggered Animations** — four cards using animate-bounce with different animation-delay values (0ms, 150ms, 300ms, 450ms) to create a staggered effect
## How to Run
 
Just open index.html in a browser. No build step or install required — Tailwind loads from the CDN.
 
## Notes
 
- hover:scale-110 is used for the 110% hover scale effect (scale-120 is not a valid Tailwind step).
- Staggering in Section 6 is done with Tailwind's arbitrary-value syntax ([animation-delay:150ms]) on top of the built-in animate-bounce animation, so no custom keyframes are needed anywhere in the project.

## Tech Used
- HTML
- Tailwind CSS (via CDN, @tailwindcss/browser)