notes:

Scenario:
You’ve been hired by a small athletics club. They need a simple, clean landing page to promote their upcoming Team Kit Shop.
They need it fast, mobile-ready, and without a bunch of slow junk. They’re not designers — you are now.

Requirements
1. Content Sections (must be in this order):

Hero section with:

Big event title ("Spring Athletics Team Shop")

Subheading ("Order your custom gear before May 31st!")

A simple button ("Shop Now")

About section explaining what the shop is ("Get official custom gear for your club. Limited-time only!")

Featured products (just 3 placeholders — product image, name, and price)

Countdown Timer (counts down to May 31, 2025)

Contact section ("Questions? Contact the club shop coordinator.")

2. Technical Specs:

Use pure HTML, CSS, and vanilla JS. No frameworks. No libraries. No templates.

Make it responsive — should look good on desktop, tablet, and phone.

Use brand colors:

#FF6500 (orange)

#1D2743 (navy)

#119ADD (blue)

#F7F7F7 (light grey/white)

Fonts: Poppins (Google Fonts link: https://fonts.google.com/specimen/Poppins)

Performance: Aim for >90% on a Lighthouse audit. No heavy images.

3. Bonus Challenges (optional but strongly encouraged):

Smooth scroll navigation when clicking the "Shop Now" button (JS required).

Hover effect on product cards (scale slightly or change background).

Sticky navigation bar on scroll.

Deliverable
A working .html file

A .css file

A .js file

(Optional: deploy it free to Netlify or Vercel and send me the live link)

(Optional: upload it to a GitHub repo — I’ll review it there if you want)

Timeline
Give yourself 5-7 days MAX.
Not because it’s "due" — but because urgency is part of being a real dev.
(I’d expect a professional to hammer this out in a day or two — but you’re building foundations, not rushing perfection.)

What I’ll Look At If You Want Feedback
Code structure (clean, commented, logical)

Responsiveness (does it actually adapt — not just shrink)

Vanilla JS quality (no junk, no bloated functions)

Problem-solving (how you approached challenges, not just the result)

This challenge will tell you more about your coding ability right now than 50 hours of tutorials.
You in?
(If yes, reply with “I’m in.” and start hammering keys.)
When you’re ready to show it, just send it here — I’ll review it straight, no fluff.








You said:
I’m in
ChatGPT said:
Hell yes.
That's exactly the attitude that separates coders who say they want it from coders who become it.

Quick reminders before you dive in:

Start ugly. Pretty later.

Build piece by piece. Don't try to do everything at once.

Push broken code to GitHub if you can — broken progress > fake perfection.

When you get stuck, don’t whine, debug. (Console log is your best friend.)

First Move:
Set up your basic folder structure like a real dev:

swift
Copy
Edit
/event-shop/
    index.html
    /css/
        style.css
    /js/
        script.js
    /img/
        (put any placeholder images here if you want)
Next Move:

Get the Hero Section up and visible.

Style it fast and dirty.

Then work your way down.

Last Tip:
You will hate your code at some point. That's the signal you're learning. Keep going.

When you’re ready, drop your GitHub link or paste your code here —
I'll give you a real review (no fake "good job!" unless you earn it).

Hammer time.
(If you need a free placeholder image set or icons for your products, just ask — I’ll hook you up with quick resources.)







You said:
Yes please
ChatGPT said:
Perfect — here's a fast, no-BS set of resources you can use to make your project look decent without wasting hours hunting around:

Placeholder Images
For Product Images:
Use https://placeholder.com/

Example for a simple product card:

html
Copy
Edit
<img src="https://via.placeholder.com/300x300.png?text=Product+Image" alt="Product Name">
(You can change the size and the text easily — super fast.)

Free Icons (for buttons, contact section, etc.)
Use https://heroicons.com/ — clean, free SVG icons.
(Just grab the SVG and paste it directly into your HTML — no heavy icon libraries.)

Example: a simple mail/contact icon you can paste into the Contact section.

html
Copy
Edit

You can change the color with CSS (fill, stroke, etc.) easily.

Free Countdown Timer (if you get stuck)
If you struggle making the countdown timer with JS,
here’s a basic vanilla JavaScript idea to study — but don't just paste it — understand it:

javascript
Copy
Edit
const countdown = () => {
  const countDate = new Date('May 31, 2025 23:59:59').getTime();
  const now = new Date().getTime();
  const gap = countDate - now;

  const second = 1000;
  const minute = second * 60;
  const hour = minute * 60;
  const day = hour * 24;

  const textDay = Math.floor(gap / day);
  const textHour = Math.floor((gap % day) / hour);
  const textMinute = Math.floor((gap % hour) / minute);
  const textSecond = Math.floor((gap % minute) / second);

  document.querySelector(".day").innerText = textDay;
  document.querySelector(".hour").innerText = textHour;
  document.querySelector(".minute").innerText = textMinute;
  document.querySelector(".second").innerText = textSecond;
};

setInterval(countdown, 1000);
You’ll need HTML placeholders like:

html
Copy
Edit
<div id="countdown">
  <span class="day"></span> Days 
  <span class="hour"></span> Hours 
  <span class="minute"></span> Minutes 
  <span class="second"></span> Seconds
</div>
Summary
You now have:

Placeholder product images

Free clean SVG icons

A headstart on a countdown timer if needed

No excuses.
Build something scrappy and working.
Ugly but functional > Pretty but broken.

When you're ready (even half-done), send the GitHub link or paste the code.
I’ll review it brutally but fairly — like a code reviewer would at a real company.
