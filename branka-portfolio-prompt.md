# Prompt: Branka Ćirić — Performance Marketing Portfolio

Build a single-page, responsive personal portfolio website for Branka Ćirić, a Performance Marketing Manager specializing in e-commerce growth (paid social, Google Ads, creative testing, campaign optimization).

## Design direction
- Modern, editorial, content-first — NOT a generic template, NOT an over-designed "agency" landing page.
- Background: warm off-white (not pure white, e.g. #FAFAF8), near-black text (not pure #000).
- One accent color used deliberately (lavender/purple family — exact shade TBD, keep it easy to swap via a CSS variable).
- Alternate light and dark (navy/near-black) sections to break up the scroll rhythm.
- Typography-led design: large, bold type for numbers and headlines; small caps/labels for context. Numbers (KPIs) should feel like hero visual elements, not stuffed into small boxed cards.
- Avoid: drop-shadow cards everywhere, rounded-corner boxes for everything, animated number counters, decorative icons, stock illustrations, gradients.
- Use thin divider lines and generous whitespace instead of boxed cards.
- Subtle scroll-based fade-ins and clean hover effects only — no heavy animation.
- Logo/wordmark: just the text "branka" (lowercase), with the accent color used on one character or the trailing period, e.g. "branka." — no icon/graphic mark.
- Fully responsive (desktop + mobile).

## Content — use ONLY the information below. Do not invent clients, results, percentages, or numbers not listed here.

### Hero
- BRANKA ĆIRIĆ
- Performance Marketing Manager
- Subheadline: E-commerce Growth • Paid Media • Creative Strategy • Optimization
- Short line: "I build, test and optimize performance marketing campaigns with a focus on sustainable e-commerce growth."
- Buttons: "View Case Studies" (anchor to Results section), "View Creative Work" (anchor to Creative section)
- Contact icons/links: LinkedIn, Email (see Contact section)
- No photo for now — leave a clearly marked placeholder spot for a future headshot.

### About
Short paragraph:
"I'm a performance marketing and e-commerce professional with experience across paid advertising, campaign strategy, creative testing, optimization and team collaboration. My approach combines data, creativity and commercial thinking — understanding what drives performance, testing new ideas, and improving campaigns based on real results."

3 short pillars (compact, not big separate blocks):
- Data-Driven — uses performance data and insights to guide decisions
- Growth-Focused — focused on profitable growth, not vanity metrics
- Strategic + Hands-On — works across strategy, execution, testing and optimization

### Results (single strong section — dark background)
Lead metric, large and prominent:
**+70% Product Sales Growth** — "Increased product sales through campaign optimization, strategic budget allocation, creative testing and continuous performance analysis."

Two performance snapshots, clearly labeled as separate periods (do NOT present as before/after comparison — add a note that reporting periods differ and shouldn't be read as period-over-period improvement):

**Period A — Last 3 months**
- Conversions: 24,830
- ROAS: 3.40
- Conversion Rate: 3.26%
- CPO: €6.66

**Period B — Last 2.5 months**
- Conversions: 62,462
- ROAS: 3.29
- Conversion Rate: 3.35%
- CPO: €6.81

Small disclaimer text: "Performance metrics reflect campaigns managed and optimized by me. Reporting periods shown are different and should not be interpreted as a direct period-over-period comparison."

### Creative Work
Intro line: "Creative is one of the strongest performance levers in e-commerce. I test different creative angles to understand which messages, hooks and product presentations generate stronger engagement and conversion potential."

2x2 grid of video cards, each with thumbnail, centered play button, title, category, short description, and a "Watch Video" action that opens the linked video (external link/embed — video URLs will be provided separately and should be easy to swap in):

1. **GLOWLIFT** — Product Demonstration / Beauty
2. **ROLE** — Product Demonstration / Lifestyle
3. **CELUBYE** — Product Demonstration / Problem → Solution
4. **HOGCOUNT** — Educational / Product Demonstration

Do not claim any one video is "best performing" — no individual creative-level stats provided.

### Skills & Tools (compact, two columns, no icons)
**Performance Marketing:** Paid Social, Meta Ads, Google Ads, Campaign Optimization, Budget Allocation, ROAS Optimization, CPO Optimization

**E-commerce:** E-commerce Strategy, Conversion Optimization, Customer Acquisition, Product Performance, Growth Strategy

**Creative & Testing:** Creative Testing, UGC, Product Demonstration, Hooks, Offers, A/B Testing

**Analytics:** Performance Reporting, KPI Analysis, Google Analytics, Data-driven Decision Making

**Tools:** Meta Ads Manager, Google Ads, Google Analytics, Shopify, Figma, Canva, Adobe Creative Cloud, Jira, Excel/Google Sheets, WordPress

### Contact / Final CTA (dark section)
- Headline: "Let's grow something great."
- Copy: "I'm open to opportunities in performance marketing, e-commerce growth, account management and digital strategy."
- Buttons: "Get in Touch" (mailto), "LinkedIn"
- Email: ciricbranka55@gmail.com
- LinkedIn: https://www.linkedin.com/in/branka-ciric/

## Technical notes
- Single HTML file (or clean component structure if using React) — clean, semantic markup.
- Smooth scroll between sections.
- Make the accent color a single easily-editable variable (CSS custom property) since the exact shade is not finalized.
- Keep copy exactly as provided above — do not add taglines, testimonials, client logos, awards, or certifications that aren't listed.
