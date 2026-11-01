# Hi, I'm Emily Qhawekazi Maramani

**Product engineer · UI/UX designer · Full-stack developer · Johannesburg, South Africa**

> A dentist sees a cavity and fills it. I see the gaps in the digital world, and I fill them.

The awkward flow, the form that quietly loses data, the tool a team pays for that still doesn't do the job: those are the gaps I notice. I'm UX/UI-focused because an idea only works if all kinds of people can use it, on any phone, in any language, with any level of confidence on a screen. Then I ideate, design and actually put it into action, and I don't stop until it ships. That's why I'm moving into product engineering: owning a product from the gap I spotted to the feature people use.

**Portfolio:** [my-portfolio-three-roan-41.vercel.app](https://my-portfolio-three-roan-41.vercel.app/) · **LinkedIn:** [emily-maramani](https://www.linkedin.com/in/emily-maramani-ab0765320) · **Email:** emilyqm01@gmail.com

## How I work

| | |
|---|---|
| **1. Spot the gap** | Find the real problem and who has it: a lost booking, a missed deadline, a subscription that isn't earning its keep. |
| **2. Design for everyone** | Information architecture, mockups and interaction details, with accessibility, language and low-data phones in mind from the start. |
| **3. Build it end to end** | React and Next.js on the front, PostgreSQL / Supabase or Node and MongoDB behind it, with security enforced in the database. |
| **4. Ship it** | Deploy, hand over, and measure whether the gap actually closed. |


---

## Featured work

Client projects are private repositories, so each one has a public **case study** explaining the problem, what I built and the decisions behind it.

### iHub Comms — one communication platform for iHub, in place of paid subscriptions
`Client` `Product engineer` `Team: CTRL + Create` · React, Vite, Supabase (PostgreSQL, RLS, Realtime)

**Problem:** iHub was paying subscriptions for several platforms that each covered one slice of a cohort's needs, and information was so spread out that learners missed deadlines and mentors couldn't see who was falling behind.

**What I solved:** I came up with the idea, owned the product and designed all of the UI/UX and mockups, then put together a team, CTRL + Create, to build it with me. One invite-only platform covers announcements, chat, tasks, submissions, schedule, attendance, courses and notes, with permissions enforced in the database. We pitched it to iHub for internal use.

**Under the hood:** Row Level Security per role, a security-definer invite function and a trigger that blocks self-promotion, Realtime subscriptions, Storage scoped to each cohort, and Edge Functions for email invites and integration sync.

📄 [Read the case study](case-studies/ihub-comms.md) · 🔒 Private repo

### Un De Plus Tours & Transfers — a tour website that actually takes bookings
`Existing client` `Solo` · Next.js, TypeScript, Tailwind, Supabase, Vercel

**Problem:** The client's site looked finished but booking and contact forms submitted nowhere, buttons were dead, contact details were placeholders and the build crashed — every lost form was a lost booking.

**What I solved:** Wired every form to a database with an admin dashboard, built a trip planner that saves itineraries to an account and exports them to PDF, email or Google Docs, added a 19-language switcher and an accessibility widget, and took it live on the client's own domain.

**Under the hood:** Next.js App Router, Supabase Auth with RLS (own itineraries only, admins see all), re-runnable SQL migrations, jsPDF loaded on demand, and Google Docs export via Google Identity Services.

📄 [Read the case study](case-studies/un-de-plus.md) · 🌐 [unde-plus.co.za](https://unde-plus.co.za) · 🔒 Private repo

### St Frusquin Sporting — a football club site built for mobile data
`Client` `Solo` · React, Vite, CSS Modules, Formspree

**Problem:** A five-team community club had no website, 100+ match photos, and parents mostly browsing on phones with limited data.

**What I solved:** Cut the first page load from 32 MB to 3.9 MB with thumbnails, organised fixtures, squads and gallery by division with official league links, met WCAG AA contrast, and used honest "coming soon" states instead of inventing fixtures.

**Under the hood:** thumbnails in the grid with full resolution only in the lightbox, an accessible dialog with focus trap, prefers-reduced-motion support, CSS Modules with design tokens, and one build deployed to GitHub Pages and Vercel.

📄 [Read the case study](case-studies/st-frusquin-sporting.md) · 🌐 [Live site](https://st-frusquin-sporting.vercel.app) · 🔒 Private repo

### Airbnb Clone — full-stack booking platform with a host dashboard
`Capstone` `Solo` · React, Node.js, Express 5, MongoDB, JWT, Jest

**Problem:** Guests and hosts need different things from the same data, and each should only be able to change what's theirs.

**What I solved:** One REST API serving a guest site and a host dashboard, with JWT auth, bcrypt passwords, role checks, correct HTTP errors and 43 API tests, live on Render.

**Under the hood:** Express 5 with routes, controllers and Mongoose models kept separate, JWT middleware, bcrypt in a pre-save hook, central error handling, and Jest + Supertest against a test database.

📄 [Read the case study](case-studies/airbnb-clone.md) · 🌐 [Live site](https://emily-airbnbclone.onrender.com/) · 🛠️ [Host dashboard](https://emily-airbnbclone-admin.onrender.com/) · 💻 [Code](https://github.com/Qhawekazii/Emily_AirbnbClone)

### Tic-Tac-Toe · Neon Arena — clean state with an unbeatable CPU
`Intern assignment` `Solo` · React, useReducer

**Problem:** Board, turns, scores, modes and history all change together; scattered state makes the screen and the rules disagree.

**What I solved:** All game state in one reducer, one function that decides the result, a minimax CPU that can't be beaten, and time-travel through move history.

**Under the hood:** one useReducer with named actions, a single getGameStatus() shared by reducer and UI, minimax for the hard CPU, and a CPU that plays through the same action as a person.

📄 [Read the case study](case-studies/tic-tac-toe.md) · 🌐 [Play it](https://tic-tac-toe-five-ebon-96.vercel.app/) · 💻 [Code](https://github.com/Qhawekazii/tic-tac-toe)

---

## More projects

| Project | What it is | Links |
|---|---|---|
| **BookFinder** | React search over the Open Library API | [Live](https://book-finder-gold-nu.vercel.app/) · [Code](https://github.com/Qhawekazii/Book-Finder) |
| **PawFinder** *(team)* | Dog breed explorer with Context API and custom hooks | [Live](https://react-dog-search-app.vercel.app/) · [Code](https://github.com/hlatsiboy113-png/react-dog-search-app) |
| **Urban Threads** | Streetwear store with Firebase auth, catalogue and live cart | [Live](https://qhawekazii.github.io/Q-s-Urban-Threads/) · [Code](https://github.com/Qhawekazii/Q-s-Urban-Threads) |
| **KinderNest** *(team)* | Childcare platform concept | [Live](https://kindernest-five.vercel.app/) · [Code](https://github.com/St10482946/kindernest) |
| **iHub Website Prototype** *(team)* | Sprint 5 capstone website for iHub Africa | [Live](https://client-website-prototype-i-hub.vercel.app/) · [Code](https://github.com/KMukendi10/Client-Website-Prototype-iHub) |
| **MeTube / Netflip** | YouTube- and Netflix-inspired layout practice | [MeTube](https://github.com/Qhawekazii/MeTube-Clone) · [Netflip](https://netflip-clone.netlify.app/) |

## Tools I work with

**Frontend:** React, Next.js, TypeScript, JavaScript, HTML, CSS, Tailwind, Vite
**Backend & data:** Node.js, Express, Supabase (PostgreSQL, Row Level Security, Edge Functions), MongoDB, Firebase
**Mobile:** Kotlin, Jetpack Compose, React Native
**Practice:** Product design, UI/UX and mockups in Figma, Git and pull-request workflows, Jest, Vercel

## Education

- Zaio × iHub Full-Stack Web Development Programme (2026)
- Higher Certificate in Mobile Application and Web Development — Rosebank College (in progress)
