# Yahia Mohamed Zakaria

**Backend developer - Node.js and TypeScript.** Final-year Communication and Computer
Engineering student at Mansoura University, graduating January 2027.

I build REST APIs and server-rendered applications with Express, TypeScript and MongoDB.
**I am looking for a software engineering internship** where I can work on a production
codebase and learn from experienced engineers.

- Currently working through PostgreSQL, automated testing and CI, and a daily
  data-structures and algorithms habit
- Linux-based development workflow
- Arabic (native), English (CEFR B2, EF SET 54)

---

## What I can defend in an interview

I keep this list and the one below separate on purpose. Everything here is something I have
built with and can explain - the design decisions, the trade-offs, and what I would do
differently.

| | |
|---|---|
| **Languages** | TypeScript, JavaScript (ES6+), HTML, CSS |
| **Backend** | Node.js, Express, REST API design, MVC layering, middleware design |
| **Validation and auth** | Zod, session-based authentication, bcrypt, Multer file handling |
| **Databases** | MongoDB, Mongoose, SQL (joins, aggregation, subqueries) |
| **Tools** | Git, GitHub, Linux, Postman, npm, EJS |

## What I am still learning

Listed separately because I would not yet claim these under pressure. They move up as I
finish them.

PostgreSQL - Prisma - Vitest and Supertest - Redis - Docker - CI/CD - data structures and
algorithms

---

## Projects

### [Secure Image Gallery](https://github.com/devYahia/lil-Pintrest)

`TypeScript` `Express` `MongoDB` `Multer` `EJS`

Image sharing app where the interesting part is the upload path. The Multer filter checks
MIME type **and** file extension, because either one alone is trivially bypassed, and
deletes are guarded by an ownership check that returns `403` when a logged-in user tries to
delete someone else's photo.

### [Shopping Cart REST API](https://github.com/devYahia/cart-master-api)

`TypeScript` `Express` `MongoDB` `Zod`

JSON REST API where Zod schemas are the single source of truth: request types are derived
from the schemas with `z.infer`, so validation rules and TypeScript types cannot drift
apart. Adding a product already in the cart increments its quantity rather than creating a
duplicate line item.

### [User Management Dashboard](https://github.com/devYahia/user-management-dashboard)

`TypeScript` `Express` `MongoDB` `EJS` `Zod`

Server-rendered admin panel with full CRUD, strict MVC separation, centralized error
handling and flash messaging. Uses `method-override` so updates and deletes are genuine
`PUT` and `DELETE` routes even though HTML forms can only send `POST`.

### [Interna.work](https://interna.work) - AI Internship Simulator

`Next.js` `TypeScript` `FastAPI` `PostgreSQL`

Placed **14th out of 122 teams** at GDG Hackathon 2026 with a five-person team on a
three-day deadline. I contributed 98 of the team's 153 commits across the Next.js
dashboard, the FastAPI layer and the database schema, and coordinated the frontend and
backend integration.

### Engineers Arena - private client work

`NestJS` `PostgreSQL` `Prisma` `BullMQ` `AWS` `Docker`

A production e-commerce and manufacturing platform I scoped, deployed and operate. The
repository is private because it is client work. What I own is the architecture decisions,
the deployment and the day-to-day running of it: background job processing in a separate
worker process, an outbox pattern for reliable event delivery, idempotency keys on
payments, S3 presigned uploads and a hardened Docker Compose setup. I am currently working
back through it in depth so I can defend every part of it, not just the parts I chose.

### First Word - Arabic Sign Language Translation

`Unity` `Meta Quest 3`

Graduation project translating Arabic Sign Language bidirectionally on Meta Quest 3 using
VR hand tracking. I own the speech pipeline - speech-to-text and text-to-speech - feeding
the Unity recognition layer.

---

## Also on my profile

Telegram bots and TON blockchain tools I built while learning: an exchange bot with a
payment flow and admin dashboard, an investment tracker with FIFO allocation and scheduled
settlement, and a support bot. They are Python and JavaScript rather than my main
TypeScript work, but they are where I first dealt with money handling, retries and
scheduled jobs.

---

## Contact

- Email: [devyahiazakaria@gmail.com](mailto:devyahiazakaria@gmail.com)
- LinkedIn: [yahiamzakaria](https://www.linkedin.com/in/yahiamzakaria/)
- Website: [yahia.website](https://yahia.website)
