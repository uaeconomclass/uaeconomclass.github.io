# Valentyn Moroz

**WordPress / WooCommerce / React**  
**Full-Stack Developer**

📍 Vinnytsia, Ukraine  
📧 morozvalentyn777@gmail.com   
🔗 Upwork Profile: https://www.upwork.com/freelancers/~013563a358160baa29  
🐙 GitHub: https://github.com/uaeconomclass  
🌐 Resume: https://uaeconomclass.github.io/

---

## Profile

Full-Stack **WordPress / WooCommerce / React Developer** with **18+ years of professional experience**.  
I specialize in **Figma-to-WordPress builds (Elementor, Bricks, Gutenberg)**, **custom plugins**, **WooCommerce extensions**, **API integrations**, and **React / Next.js applications**.

My core strength is working with **real production systems**: stabilizing legacy code, performance and security rescue, WCAG 2.2 accessibility, fixing critical issues without downtime, and building solutions that fit existing business workflows instead of breaking them.

Consistently positive feedback from clients in **USA, Europe, and Australia**.

---

## Key Metrics

- **18+ years** of experience  
- **100% Job Success Score**, **Top Rated** (Upwork)  
- **95 Upwork jobs**, **2,025+ hours**  
- **5.0 rating**

---

## Tech Stack

### Backend
- PHP, WordPress Core, Hooks & Filters  
- WooCommerce Extensions  
- Elementor, Bricks, ACF  
- Next.js, Prisma, PostgreSQL  
- REST API, GraphQL, WP-CLI  
- MySQL, Custom Plugins

### Frontend
- JavaScript, TypeScript, React  
- Vite, Gutenberg Blocks  
- Firebase / Firestore  
- HTML5, SCSS, Tailwind, GSAP

### Integrations
- Stripe, PayPal, WooPayments  
- JobAdder, Billbee, SendGrid  
- GA4, GTM, Google Merchant Center  
- OpenAI API, Shopify

### DevOps
- Git, GitHub Actions  
- Docker, Linux, nginx, SSH  
- Vercel, Cloudflare Pages

### Quality & Automation
- WCAG 2.2, axe-core  
- Playwright, Puppeteer

---

## Languages

- **Ukrainian** — Native  
- **Russian** — Native  
- **English** — B2 (Professional working proficiency)

---

## Client Review

> *"Valentin is one of the few developers who actually understands the business logic behind the code. He fixes problems without breaking production and communicates clearly."*

---

## Key Projects

### Recruitment Site + JobAdder Integration (oak-tree.tech)  
**Figma | Elementor | Vite | PHP | JobAdder API | OAuth 2.0**

Figma-to-Elementor build with JobAdder integration: job ads synced into a CPT with AJAX filters, site applications pushed to JobAdder as candidates with screening answers and attachments. Same flow shipped the AudioVS WooCommerce store and Kane Exceleris.

---

### Multi-Tenant CRM (SaaS)  
**Next.js | TypeScript | Prisma | PostgreSQL RLS | Vercel**

CRM in production for a veterinary clinic: tenant isolation via Row-Level Security with boundary tests, industry modules, invoicing and usage metering, email provider failover, business sites on subdomains, CI on every push.

---

### Divi → Bricks Migration + WCAG 2.2 Auditor  
**Bricks | Docker | Playwright | axe-core | WordPress Abilities API**

Migrated the Wyoming State Treasurer's Office site to Bricks with WCAG 2.2 remediation. Built an external auditor (axe-core, keyboard/reflow checks, PDF validation) and a plugin that maps findings to Bricks elements.

---

### WooCommerce VAT, Voucher & Billbee Fixes  
**WooCommerce | Billbee API | Reverse-Charge VAT | Production Fix**

Fixed voucher/cart totals and intra-Community reverse-charge orders (net shipping, 0% discount mapping in Billbee) on a live German store without downtime, verified end to end in Billbee.

---

## Work Experience

### PHP / WordPress / React Developer  
**Dec 2025 – Present**  
**oak-tree.tech**

- Figma → Vite/BEM → WordPress/Elementor builds for an Australian agency (AudioVS, TLR Contracting, Kane Exceleris)  
- Integrations: JobAdder API (OAuth, jobs sync, applications), WooCommerce catalogs, GA4/GTM, Instagram feed  
- React + Vite + Firebase/Firestore: Networking Executives admin dashboard and user platform (review queues, audit trail, CSV export, SEO prerender)  
- WordPress plugins: LibCal calendar (OAuth API), Gutenberg blocks, member directory moderation, REST deploy endpoints

---

### WordPress & Shopify Developer  
**2023 – 2025**  
**Catecut | AI Fashion Tech**

- Built AI-powered WordPress plugin for personalized clothing recommendations using OpenAI API  
- Developed Shopify app with custom Liquid templates and GraphQL API integration  
- Implemented JSON-based decision engine for product matching  
- Created admin dashboard for AI parameters and analytics

---

### WordPress Developer  
**2020 – 2023**  
**YellowFever LLC.**

- Delivered 30+ custom WordPress projects (themes, plugins, WooCommerce extensions)  
- Built headless WordPress setups with React/Next.js frontends  
- Integrated Stripe, PayPal, WooPayments with custom checkout flows  
- Connected third-party services: SendGrid, Twilio, CRMs  
- Production debugging, performance optimization, safe refactoring of legacy code  
- Developed custom Gutenberg blocks and FSE themes

---

### WordPress Developer & Project Manager  
**2016 – 2020**  
**APN Coders**

- Led a remote team of 5 developers  
- Architected scalable WooCommerce solutions (10K+ daily visitors)  
- Managed sprints, timelines, and deliverables (Agile)  
- Direct client communication (USA, EU, Australia)  
- Code reviews and mentoring junior developers

---

### IT Specialist  
**2014 – 2016**  
**Armed Forces of Ukraine — 30th Mechanized Brigade (ATO Veteran)**

- Ensured secure communications for tank battalion during active operations

---

### WordPress Developer  
**2008 – 2014**  
**Private Entrepreneur | Medical & Healthcare**

- Built custom appointment booking systems with SMS/email notifications  
- Developed patient portals with secure data handling  
- Created a network of 15+ medical websites  
- Implemented multilingual support, WCAG accessibility, SEO optimization  
- Managed hosting, SSL, backups, and security

---

## Generating the CV PDF

The `valentyn-moroz-cv.pdf` is generated from `index.html` using Playwright (Chromium headless).

**Prerequisites:** Node.js, `@playwright/mcp` installed globally (`npm install -g @playwright/mcp`).

**Command:**

```js
// Save as gen-pdf.js and run: node gen-pdf.js
const { chromium } = require('C:/Users/User/AppData/Roaming/npm/node_modules/@playwright/mcp/node_modules/playwright');

(async () => {
  const browser = await chromium.launch({ channel: 'chrome' });
  const page = await browser.newPage();
  await page.goto('file:///C:/GIT/uaeconomclass.github.io/index.html');
  await page.waitForLoadState('networkidle');
  await page.pdf({
    path: 'C:/GIT/uaeconomclass.github.io/valentyn-moroz-cv.pdf',
    format: 'A4',
    printBackground: true,
    margin: { top: '0', right: '0', bottom: '0', left: '0' }
  });
  await browser.close();
  console.log('PDF generated successfully');
})();
```

> After generating, commit the updated PDF: `git add valentyn-moroz-cv.pdf && git commit -m "docs: regenerate CV PDF"`

---

## Education

**Master of Science in Computer Engineering**  
Vinnytsia National Technical University  
**2008**  
Thesis: *Fingerprint Recognition Algorithm*
