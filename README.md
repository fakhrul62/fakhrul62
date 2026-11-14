<!-- Custom artwork lives in ./assets. Commit the README and assets together. -->
<picture>
  <source media="(max-width: 600px) and (prefers-reduced-motion: reduce)" srcset="./assets/hero-mobile-still.svg" />
  <source media="(prefers-reduced-motion: reduce)" srcset="./assets/hero-still.svg" />
  <source media="(max-width: 600px)" srcset="./assets/hero-mobile.svg" />
  <img src="./assets/hero.svg" width="100%" alt="Md. Fakhrul Alam Shuvo, full-stack developer in Dhaka. An animated diagram traces a browser request through a Next.js API to PostgreSQL." />
</picture>

<p align="center">
  <a href="https://fakhrul.codechronic.com/"><img src="./assets/link-portfolio.svg" height="40" alt="Visit my portfolio" /></a>
  <a href="https://www.linkedin.com/in/md-fakhrul-alam-shuvo/"><img src="./assets/link-linkedin.svg" height="40" alt="Connect on LinkedIn" /></a>
  <a href="https://profiles.wordpress.org/fakhrulalam16/"><img src="./assets/link-wordpress.svg" height="40" alt="Explore my WordPress plugins" /></a>
  <a href="mailto:fakhrul20.alam@gmail.com"><img src="./assets/link-email.svg" height="40" alt="Email Fakhrul" /></a>
</p>

I’m **Fakhrul**, a full-stack web developer in Dhaka. My projects include a public API for Bangladesh, a civic complaint portal, and an AI trip planner. I also build WordPress plugins and WooCommerce integrations for clients.

<picture>
  <source media="(max-width: 600px)" srcset="./assets/projects-mobile.svg" />
  <img src="./assets/projects.svg" width="100%" alt="Things I build" />
</picture>

### BDApi4All · Try a request

I built a public REST API for Bangladesh data. Open a route below for a sample result, or run it against the live API. On a cache miss, the Next.js district handler queries PostgreSQL through Prisma.

<details>
<summary><b>GET /districts</b> · Inspect response</summary>

<picture>
  <source media="(prefers-reduced-motion: reduce)" srcset="./assets/districts-still.svg" />
  <img src="./assets/districts.svg" width="640" alt="Sample from GET /districts — HTTP 200, first English name Comilla." />
</picture>

[Run this request](https://bdapi4all.vercel.app/api/v1/districts) · [Read the route handler](https://github.com/fakhrul62/bdapi4all/blob/main/src/app/api/v1/districts/route.ts)

</details>

<details>
<summary><b>GET /divisions</b> · Inspect response</summary>

<picture>
  <source media="(prefers-reduced-motion: reduce)" srcset="./assets/divisions-still.svg" />
  <img src="./assets/divisions.svg" width="640" alt="Sample from GET /divisions — HTTP 200, first English name Chattogram." />
</picture>

[Run this request](https://bdapi4all.vercel.app/api/v1/divisions) · [Read the route handler](https://github.com/fakhrul62/bdapi4all/blob/main/src/app/api/v1/divisions/route.ts)

</details>

[Open the interactive API playground](https://bdapi4all.vercel.app/playground) · [Browse the source](https://github.com/fakhrul62/bdapi4all)

### CivicDesk · From complaint form to ticket

A citizen submits a complaint in the web app. A Next.js server action validates the form and creates a ticket in PostgreSQL through Prisma. Agents and supervisors can track it through review and resolution.

[Read the ticket actions](https://github.com/fakhrul62/civicdesk/blob/main/actions/tickets.ts) · [Explore the data model](https://github.com/fakhrul62/civicdesk/blob/main/prisma/schema.prisma)

### AI Travel Planner · From preferences to itinerary

I built a React and Next.js dashboard that turns travel preferences into a personalised itinerary using Gemini and MongoDB.

[Try the planner](https://travel-ai-dashboard-k3pt.vercel.app/) · [Browse the source](https://github.com/fakhrul62/travel-ai-dashboard)

<picture>
  <source media="(max-width: 600px)" srcset="./assets/stack-mobile.svg" />
  <img src="./assets/stack.svg" width="100%" alt="The toolbox" />
</picture>

### Frontend & web applications

Responsive web development, with React and Next.js experience through personal projects.

<img src="./assets/tech-html.svg" alt="HTML5" height="33" /> <img src="./assets/tech-css.svg" alt="CSS3" height="33" /> <img src="./assets/tech-javascript.svg" alt="JavaScript" height="33" /> <img src="./assets/tech-react.svg" alt="React" height="33" /> <img src="./assets/tech-nextjs.svg" alt="Next.js" height="33" /> <img src="./assets/tech-tailwind.svg" alt="Tailwind CSS" height="33" /> <img src="./assets/tech-bootstrap.svg" alt="Bootstrap" height="33" />

### Backend & data

APIs, integrations, and database-backed applications across client work and personal projects.

<img src="./assets/tech-nodejs.svg" alt="Node.js" height="33" /> <img src="./assets/tech-express.svg" alt="Express.js" height="33" /> <img src="./assets/tech-rest.svg" alt="REST APIs" height="33" /> <img src="./assets/tech-mysql.svg" alt="MySQL" height="33" /> <img src="./assets/tech-mongodb.svg" alt="MongoDB" height="33" />

### AI application projects

Hands-on exploration through projects such as an AI travel planner and Hungry Bangla AI. I use AI-assisted development with human review and validation.

<img src="./assets/tech-python.svg" alt="Python" height="33" /> <img src="./assets/tech-fastapi.svg" alt="FastAPI" height="33" /> <img src="./assets/tech-gemini.svg" alt="Gemini API" height="33" /> <img src="./assets/tech-ai-assisted.svg" alt="AI-assisted development" height="33" />

### Newer additions

Growing familiarity through practice and personal projects.

<img src="./assets/tech-nestjs.svg" alt="NestJS" height="33" /> <img src="./assets/tech-postgresql.svg" alt="PostgreSQL" height="33" /> <img src="./assets/tech-typescript.svg" alt="TypeScript" height="33" /> <img src="./assets/tech-postman.svg" alt="Postman" height="33" />

### WordPress & website platforms

My client work covers custom plugins, structured content, e-commerce, and integrations. [Published WordPress plugins](https://profiles.wordpress.org/fakhrulalam16/) · [Apiro Free Icon Picker](https://free-awesome.vercel.app/)

<img src="./assets/tech-wordpress.svg" alt="WordPress" height="33" /> <img src="./assets/tech-woocommerce.svg" alt="WooCommerce" height="33" /> <img src="./assets/tech-elementor.svg" alt="Elementor Pro" height="33" /> <img src="./assets/tech-acf.svg" alt="ACF" height="33" /> <img src="./assets/tech-php.svg" alt="PHP" height="33" /> <img src="./assets/tech-webflow.svg" alt="Webflow" height="33" />

### Design & delivery

<img src="./assets/tech-git.svg" alt="Git / GitHub" height="33" /> <img src="./assets/tech-figma.svg" alt="Figma" height="33" /> <img src="./assets/tech-photoshop.svg" alt="Photoshop" height="33" /> <img src="./assets/tech-canva.svg" alt="Canva" height="33" />

**Also in my workflow:** responsive QA, debugging, performance optimisation, technical SEO, hosting/DNS, and client collaboration.

<details>
<summary><b>More tools I've worked with</b></summary>

Supabase, Firebase, Context API, plus foundational exposure to Shopify, Wix, and Odoo.

</details>

<picture>
  <source media="(max-width: 600px)" srcset="./assets/learning-mobile.svg" />
  <img src="./assets/learning.svg" width="100%" alt="Still leveling up" />
</picture>

I'm deepening my backend skills and exploring how AI integrations can make everyday software more useful.

| Training & education | Focus |
| :-- | :-- |
| **OpenAI** · 2026 | AI Foundations, Applied AI Foundations, Agents and Workflows |
| **Anthropic Education** · 2026 | Claude 101 |
| **Programming Hero** · 2024 | Complete Web Development |
| **BSc in Computer Science & Engineering** · 2025 | Prime University, Dhaka |

<picture>
  <source media="(max-width: 600px)" srcset="./assets/connect-mobile.svg" />
  <img src="./assets/connect.svg" width="100%" alt="Let's build something" />
</picture>

Have a website to improve, an integration to untangle, or an idea worth building? I'm open to collaboration and open-source contributions.

**[Portfolio](https://fakhrul.codechronic.com/) · [LinkedIn](https://www.linkedin.com/in/md-fakhrul-alam-shuvo/) · [Email](mailto:fakhrul20.alam@gmail.com)**

```console
fakhrul@workspace:~$ make something useful
```
