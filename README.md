<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FFE066,50:FFB3C1,100:E5484D&height=220&section=header&text=Piyush%20Kumar%20Singh&fontColor=2B2A28&fontSize=45&fontAlignY=32&desc=Backend%20Developer%20in%20the%20making%20%20%7C%20%20Node.js%20%C2%B7%20Express%20%C2%B7%20MongoDB&descColor=2B2A28&descSize=16&descAlignY=52&animation=fadeIn" width="100%" />

<p align="center"><i>Learning backend the honest way — one project, one bug, one commit at a time.</i></p>

<p align="center">
  <a href="https://www.linkedin.com/in/piyush-kumar-singh-935263404/"><img src="https://img.shields.io/badge/LinkedIn-Connect-F4E9CB?style=flat-square&logo=linkedin&logoColor=A7D8F0&labelColor=2B2A28" alt="LinkedIn"/></a>
  <a href="mailto:piyushkumarsingh.pks31@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-F4E9CB?style=flat-square&logo=gmail&logoColor=E5484D&labelColor=2B2A28" alt="Email"/></a>
</p>

<div align="center">

**Second Year @ PSIT Kanpur** · **5 backend projects shipped** · **50+ REST endpoints built from scratch**

<sub>✎ Currently learning: MongoDB transactions, file uploads & centralized error handling</sub>

</div>

---

## Learning Path

Every project below was built after the previous one — each adds one new concept on top of the last.

| # | Project | What it taught me |
|---|---|---|
| 1 | **DevTinder** | Express routing, Mongoose models, JWT auth — following along a course |
| 2 | **To-Do App** | First CRUD built on my own |
| 3 | **Expense Tracker** | Ownership checks (IDOR), pagination, search, filter, sort |
| 4 | **Scrrible** (Blog API) | Relations & `populate`, nested routes, draft/published flow, cascade delete |
| 5 | **E-Commerce Backend** | Role-based access, cart logic, order snapshots, stock management |

---

## Flagship Project — E-Commerce Backend

**[github.com/singhpiyush31/E-Commerce-Backend](https://github.com/singhpiyush31/E-Commerce-Backend)** · REST API for an online store

<sub>Node.js · Express 5 · MongoDB · Mongoose · JWT · bcrypt</sub>

> *Admin manages the catalog, users fill a cart, orders freeze prices — 23 endpoints, 5 models, every rule enforced on the server.*

| Area | What's built |
|---|---|
| **Auth & roles** | JWT in cookies · `User` / `Admin` roles with middleware chaining (`userAuth → isAdmin`) · role never accepted from the client |
| **Catalog** | Category & Product CRUD (admin-only) · public listing with **search, category/brand/price-range/in-stock filters, 4 sort modes & pagination** · category delete blocked while products reference it |
| **Cart** | One cart per user · re-adding a product merges quantity · **stock validated on every add/update** · set quantity to `0` to remove |
| **Orders** | Built **only from the cart, never from the request body** · product name & price **copied as a snapshot** so old receipts never change · stock decremented on order, **restored on cancel** |
| **Order lifecycle** | `Pending → Confirmed → Shipped → Delivered` · users can cancel until delivered, admins control every state · cancelled orders are final |
| **Code quality** | `routes → controllers → models` layering · reusable `utils/` for pagination & filters · 20+ small, descriptive commits |

---

## Other Projects

**[Scrrible — Blog API](https://github.com/singhpiyush31/Post-Application)** <br/>
Posts with comments, draft/published visibility, owner-only edits, cascade delete of comments, and paginated public feed with search/filter/sort. **13 endpoints · 3 models.** <br/>
<sub>Node.js · Express · MongoDB · JWT</sub>

**[Expense Tracker API](https://github.com/singhpiyush31/Expense-Tracker)** <br/>
Per-user expense CRUD with category & payment-method enums, date-range filters, title search, sorting, pagination and a totals endpoint. **9 endpoints.** <br/>
<sub>Node.js · Express · MongoDB · JWT</sub>

**[To-Do Application](https://github.com/singhpiyush31/To-Do-Application)** <br/>
First independent CRUD API — the project where routes, controllers and models first clicked. <br/>
<sub>Node.js · Express · MongoDB</sub>

**[DevTinder](https://github.com/singhpiyush31/DevTinder)** <br/>
Developer-matching backend built while learning Node.js fundamentals — auth, profiles, connection requests. <br/>
<sub>Node.js · Express · MongoDB</sub>

---

## Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=js,nodejs,express,mongodb,git,github,postman,vscode&theme=light&perline=8" alt="JavaScript, Node.js, Express, MongoDB, Git, GitHub, Postman, VS Code"/>
</p>

---

## GitHub Stats

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=singhpiyush31&theme=solarized" width="100%" alt="GitHub profile summary"/>
</div>

<br/>

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=singhpiyush31&theme=solarized" height="200" alt="Top languages by repository"/>
  &nbsp;
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=singhpiyush31&theme=solarized" height="200" alt="Top languages by commits"/>
</div>

<br/>

<div align="center">
  <img src="https://github-readme-streak-stats-eight.vercel.app?user=singhpiyush31&hide_border=false&border=2B2A28&background=F4E9CB&stroke=2B2A28&ring=E5484D&fire=E5484D&currStreakLabel=2B2A28&sideLabels=2B2A28&dates=6b665c" alt="Contribution streak"/>
</div>

<br/>

<div align="center">
  <img src="https://ssr-contributions-svg.vercel.app/_/singhpiyush31?chart=3dbar&gap=0.6&scale=2&flatten=2&animation=wave&format=svg&weeks=16&theme=green" width="600" alt="3D contribution graph"/>
</div>

---

<div align="center">

### Let's Connect

Happy to talk about **REST API design**, **MongoDB modelling**, or the bug that took me a whole evening to find.

[piyushkumarsingh.pks31@gmail.com](mailto:piyushkumarsingh.pks31@gmail.com) · [LinkedIn](https://www.linkedin.com/in/piyush-kumar-singh-935263404/)

<sub><code>git commit -m "make it work, then make it right."</code></sub>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FFE066,50:FFB3C1,100:E5484D&height=100&section=footer" width="100%" />
