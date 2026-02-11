# AGENTS.md — Portfolio Strategy & Mandate

## The Mandate

**Target Career Outcome:** Secure opportunities at game studios, VR companies, and creative tech firms as an **Artist-Programmer** combining creative and technical skills.

**Job Titles:** Game Developer, VR Developer, Creative Technologist, 3D Technical Artist, Web Developer (Creative Focus)

**Geographic Focus:** NJIT student targeting NJ/NY tech hubs and remote positions

**Differentiation:** Rare hybrid skill set (artist + programmer + VR experience) positions Denise as a premium candidate in creative tech space where most competitors are either pure artists or pure developers.

---

## The Tech Stack

### Frontend
- **HTML5** — Semantic markup for SEO and accessibility
- **CSS3** — Modern Grid/Flexbox, animations, responsive design
- **Vanilla JavaScript** — No frameworks; demonstrates core fundamentals and performance efficiency

### Hosting & Deployment
- **GitHub Pages** — Free, built-in, shows Git proficiency
- **Custom Domain Ready** — Can point adventurecode.dev or similar

### Why This Stack?

✅ **Zero Dependencies** — No npm bloat, instant load times, demonstrating clean engineering  
✅ **Performance First** — Sub-1s load on 4G, better Lighthouse scores than framework-heavy sites  
✅ **Shows Fundamentals** — Game studios value developers who understand core web concepts  
✅ **Maintenance** — Single developer can maintain; no build pipeline headaches  
✅ **SEO Advantage** — Semantic HTML + fast load = better rankings for "NJ game developer"  
✅ **Credibility** — Recruiters see: "This person knows what they're doing" not "This person uses a framework"

---

## The Sitemap

### Page Structure (Single-Page Application)

```
denisepayumo.github.io/
├── Home / Hero
├── Work (Case Studies)
├── Art Gallery
├── About
├── Contact / Lead-Gen
└── (Future: Blog for devlogs)
```

### Section Breakdown

#### 1. Hero Section
- **Purpose:** Immediate brand clarity
- **Content:** 
  - Name + Tagline: "Artist-Programmer | Game Dev & VR"
  - One-liner: [Brief value prop]
  - CTAs: "View My Work" + "Get In Touch"
- **Visual:** Gradient orb animation, premium feel
- **Mobile:** Full height, readable tagline

#### 2. Work Section (Case Studies)
- **Purpose:** Demonstrate professional execution
- **Projects Showcased:**
  1. **Adventure Catalyst** (Primary — featured case study)
     - Problem: Minecraft mod had no professional presentation
     - Solution: Designed website + created 3D renders
     - Result: Professional visual impact, showcased team's work
     - Tech: HTML/CSS, JavaScript, Vue 3, Tailwind CSS, Vite, 3D Renders, UI/UX Design
     - Link: https://adventurecatalyst.net/
  
  2. **Parasomnia** (Secondary)
     - Short horror/rhythm game with wario-ware-like micro games
     - Developed game mechanics, UI assets, and level design
     - Tech: Unity, C#, Procreate
     - Link: https://legit-studios.itch.io/parasomnia
  
  3. **QA Intern | Transfr Inc.** (Tertiary)
     - VR simulations for career preparation
     - QA testing, bug documentation, immersive environments
     - Tech: QA Testing, Bug Documentation

#### 3. Art Gallery Section
- **Purpose:** Showcase creative output
- **Content:**
  - Embedded Instagram feed (@dpdigitals)
  - 3D modeling in Blender & Nomadsculpt. Digital art in Procreate.
  - Link to Instagram for follow-through
- **Messaging:** 3D art, digital art, character design, environmental work

#### 4. About Section
- **Purpose:** Build trust & establish narrative
- **Content:**
  - Tagline: "Artist-Programmer combining creativity with technical skill. In teams, I stay adaptable and fill gaps wherever needed."
  - Skills: JavaScript, HTML/CSS, C#, PHP, Unity, Blender, Nomadsculpt, Game Design, VR Testing, Web Development
  - Experience: VR Internship (Transfr Inc.), Adventure Catalyst, Game Development, 3D Modeling
  - "Why Hire Me" sidebar highlighting unique value
  - Target Roles: Creative Technologist, Web Developer (Creative Focus), 3D Technical Artist, Game Developer

#### 5. Contact / Lead-Gen Section
- **Purpose:** Capture recruiter interest & generate leads
- **Primary CTA:** "Get In Touch" email button (denise.payumo@njit.edu)
- **Secondary Links:** LinkedIn, Instagram (no GitHub, no Itch.io)
- **Copy:** "Let's work together"
- **Form:** Direct mailto (no backend required for MVP)

---

## Non-Negotiables

### 1. Mobile Responsiveness ✅
- **Breakpoints:** 480px, 768px, 1024px, 1920px+
- **Navigation:** Hamburger menu on mobile with smooth animations
- **Images:** Responsive heights (200px desktop → 120px mobile)
- **Testing:** Verified on iPhone, iPad, Android devices
- **Standard:** Every section readable and usable on small screens

### 2. SEO Optimization (NJ/NY Focus) ✅
- **Keywords to Target:**
  - "Game developer NJ"
  - "VR developer New York"
  - "Artist-programmer"
  - "Game development portfolio"
  - "Creative technologist"
  - "NJIT student developer"
  - "Web developer NJ"
  - "3D technical artist"

- **Implementation:**
  - Semantic HTML (`<header>`, `<section>`, `<article>`, etc.)
  - Meta descriptions on each major section
  - Open Graph tags for social sharing
  - Clean URL structure
  - Fast load time (Lighthouse 95+)

- **Content Hierarchy:**
  - H1: Page title (Denise Payumo - Artist-Programmer)
  - H2: Major sections (Work, Art, About, Contact)
  - H3: Subsections (project names, skill categories)

- **Local SEO:**
  - Mention NJIT prominently
  - Link to NJ tech communities
  - Include location in footer if desired

### 3. Specific Call-to-Action (CTA) ✅

**Primary CTA:** "Get In Touch"
- **Location:** Hero section (above fold)
- **Location:** Contact section (bottom)
- **Action:** Direct email to denise.payumo@njit.edu
- **Copy:** Clear, simple, low-friction
- **Visual:** Gradient button with hover animation

**Secondary CTAs:**
- "View My Work" → Scrolls to case studies
- "@dpdigitals" → Instagram engagement
- LinkedIn → Professional network connection

**CTA Principles:**
- One primary action per section
- Clear visual hierarchy (primary button more prominent)
- Mobile-friendly touch targets (48px minimum)
- Hover states to indicate interactivity
- No friction — mailto: vs form submission

---

## Deployment & Maintenance

### Deployment (GitHub Pages)
```bash
cd portfolio
git init
git add .
git commit -m "Initial portfolio"
git remote add origin https://github.com/denisepayumo/denisepayumo.github.io.git
git push -u origin main
# Enable GitHub Pages in Settings → Pages
```

**Live at:** https://denisepayumo.github.io

### Update Cycle
- **Weekly:** Check analytics (if added)
- **Monthly:** Add new projects or case studies
- **Quarterly:** SEO audit (keywords, rankings)
- **As-needed:** Respond to recruiter inquiries

### Content Updates
- Add new game projects to Work section
- Update Instagram feed auto-embeds
- Link new blog posts (devlogs) to create organic SEO
- Refresh case study descriptions as needed

---

## Success Metrics

✅ **Recruiter Engagement** — Portfolio as primary point of discovery  
✅ **Mobile Traffic** — 60%+ traffic from mobile devices  
✅ **Conversion** — Email clicks from portfolio to Denise's inbox  
✅ **Rankings** — Top 3 results for "game developer NJ" in 6 months  
✅ **Social Integration** — Instagram followers, LinkedIn connections  
✅ **Interview Pipeline** — Portfolio leads to phone screens/interviews

---

## Next Actions (Post-Deploy)

1. **Share & Amplify**
   - Add GitHub Pages link to LinkedIn, resume, email signature
   - Share portfolio launch on LinkedIn (post, not just link)
   - Update bio everywhere to include link

2. **SEO Boost**
   - Submit to Google Search Console
   - Monitor rankings for target keywords
   - Create backlinks (dev blogs, game studios, etc.)

3. **Content Expansion**
   - Monthly devlog posts (blog section coming soon)
   - Case study deep-dives on each game project
   - Technical write-ups on 3D art pipeline

4. **Recruitment Outreach**
   - Email links to studios/VR companies
   - Use portfolio in cold outreach messages
   - Highlight during informational interviews

---

## Mandate Summary

**We are building a professional, performance-optimized portfolio that positions Denise as a rare Artist-Programmer hybrid, optimized for discovery by NJ/NY game studios and VR companies, with a clear path to recruiter engagement through email CTAs and social integration.**

**Tech Stack:** HTML5 + CSS3 + Vanilla JS + GitHub Pages  
**Audience:** Game Studios, VR Companies, Creative Tech Firms (NJ/NY focus)  
**Differentiator:** Artist-Programmer with VR experience  
**Success:** Recruiter inbound through portfolio discovery  

---

*Last Updated: February 11, 2026*
