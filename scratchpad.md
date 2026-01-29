# Project: 美国斩杀线生存指南 (US Financial Survival Guide)

## Background and Motivation

**Project Goal**: Create a comprehensive GitHub repository serving as a financial survival guide for Chinese international students in the US, covering critical topics that mainstream LLMs avoid but are essential for real-world survival.

**Target Audience**:
- Primary: Chinese international students in the US
- Secondary: All international students, Americans interested in financial defense strategies

**Core Concept**: "斩杀线" (Survival Cutoff Line) - the critical threshold where financial reserves, mental support, and survival resources drop below a point triggering irreversible cascading collapse and system "elimination"

**User's Personal Context**:
- Nearly fell below the cutoff line 2 years ago due to medical expenses
- Used GPT to negotiate medical bills down significantly
- Now financially stable with investment capacity
- Wants to help others avoid similar situations

**Content Focus Areas**:
1. Medical bill negotiation and dispute
2. Credit card rights protection and dispute resolution
3. Financial defense strategies
4. Rights protection (维权) and "battle" tactics
5. Emergency financial planning
6. Practical content that LLMs typically won't provide

---

## Key Challenges and Analysis

### Challenge 1: Content Sensitivity
- Large language models avoid giving specific advice on financial disputes, negotiation tactics, and aggressive rights protection
- Need to balance being helpful vs. being legally/ethically sound
- Solution: Focus on education, documented cases, template letters, and process guides rather than specific legal advice

### Challenge 2: Bilingual SEO
- Must be searchable by both Chinese speakers (小红书, WeChat) and English speakers (Google, GitHub)
- Need proper repo structure with both languages
- **UPDATE**: User decided Chinese-only README is sufficient

### Challenge 3: Verification and Credibility
- Financial/legal information must be accurate and up-to-date
- Need to cite sources and include disclaimers
- Consider community contribution model for verification

### Challenge 4: Scope Definition
- Too broad: Becomes generic financial advice
- Too narrow: Misses critical survival scenarios
- Need to focus on "斩杀线" scenarios: emergency medical bills, debt disputes, eviction defense, employment issues

---

## High-Level Task Breakdown

### Phase 1: Repository Foundation
- [x] **Task 1.1**: Choose final repository name
  - **Success Criteria**: User approved `US-Financial-Survival-Guide`

- [x] **Task 1.2**: Initialize GitHub repository with proper structure
  - **Success Criteria**:
    - Repo created with proper .gitignore, LICENSE (CC BY-NC-SA 4.0)
    - Chinese-only README.md with clear mission statement
    - Folder structure defined and created
    - Initial commit ready

- [ ] **Task 1.3**: Define content taxonomy and categorization
  - **Success Criteria**:
    - Categories list created and approved
    - Folder structure reflects categories
    - Template files created for each content type

### Phase 2: Core Content Development
- [ ] **Task 2.1**: Medical Bill Negotiation Guide
  - **Success Criteria**:
    - Comprehensive guide with step-by-step process
    - Template letters included
    - Real case studies (anonymized)
    - Resources and contact information

- [ ] **Task 2.2**: Credit Card Dispute & Rights Protection
  - **Success Criteria**:
    - Dispute process documented
    - Template dispute letters
    - Timeline and escalation paths
    - Common scenarios covered

- [ ] **Task 2.3**: Financial Emergency Playbook
  - **Success Criteria**:
    - Decision trees for different emergency scenarios
    - Resource lists (legal aid, financial assistance, etc.)
    - Budget templates and calculators

- [ ] **Task 2.4**: Rights Protection Battle Tactics (维权)
  - **Success Criteria**:
    - Legal framework education
    - Communication strategies
    - Documentation requirements
    - When to escalate vs. negotiate

### Phase 3: Community & Discoverability
- [ ] **Task 3.1**: SEO Optimization
  - **Success Criteria**:
    - Keywords research completed
    - README optimized for GitHub search
    - Topics/tags added to repo
    - External link building strategy

- [ ] **Task 3.2**: Small Red Book (小红书) Integration
  - **Success Criteria**:
    - Content adapted for 小红书 format
    - Initial posts published with repo links
    - Engagement strategy defined

- [ ] **Task 3.3**: Community Contribution Guidelines
  - **Success Criteria**:
    - CONTRIBUTING.md created
    - Issue templates
    - PR templates
    - Code of conduct

### Phase 4: Legal & Compliance
- [ ] **Task 4.1**: Legal Disclaimer
  - **Success Criteria**:
    - Comprehensive disclaimer reviewed
    - Placed prominently in README and relevant sections

- [ ] **Task 4.2**: Source Verification
  - **Success Criteria**:
    - All factual claims cited
    - Links to official resources
    - Last updated dates on all content

---

## Project Status Board

### Current Phase: Phase 1 - Repository Foundation

#### Completed Tasks:
- [x] User approved repository name: `US-Financial-Survival-Guide`
- [x] Created repository directory at /Users/kw35262/Documents/dev/US-Financial-Survival-Guide
- [x] Initialized git repository
- [x] Moved scratchpad.md to new repository
- [x] Set up initial folder structure:
  - `docs/` with subdirectories: medical-bills, credit-cards, emergency-finance, rights-protection, case-studies
  - `guides/`
  - `templates/`
  - `resources/`
- [x] Create .gitignore with appropriate rules
- [x] Add LICENSE file (CC BY-NC-SA 4.0 - user added directly)
- [x] Create Chinese-only README.md (user decided single language)
- [x] Fixed UTF-8 encoding issues in README.md and scratchpad.md

#### Completed:
- [x] Make initial git commit (commit: 8b50e5d)
  - 4 files changed, 901 insertions(+)
  - LICENSE, README.md, .gitignore, scratchpad.md

#### Website Development Phase - COMPLETED:
- [x] Choose website template/framework (Docsify)
- [x] Set up website structure
- [x] Create comprehensive medical bills guide
- [x] Create placeholder pages for all sections
- [x] Test locally (successful at http://localhost:3000)
- [x] Git commit (commit: a7466e4)
  - 12 files changed, 974 insertions(+)

#### GitHub Deployment Phase - IN PROGRESS:
- [x] Update all YOUR_USERNAME placeholders to ktwu01
- [x] Update email placeholder in about.md
- [x] Push commits to GitHub (commits: 8b50e5d, a7466e4, 1ec1997, 7136737)
- [x] All code successfully on GitHub at https://github.com/ktwu01/US-Financial-Survival-Guide
- [ ] **USER ACTION REQUIRED**: Enable GitHub Pages in repository settings
  - Go to Settings → Pages
  - Set Source: Branch main, Folder /docs
  - Click Save
- [ ] Test live website at https://ktwu01.github.io/US-Financial-Survival-Guide/

---

## Executor's Feedback or Assistance Requests

### 2025-01-29 - UTF-8 Encoding Fixed

**Issue Identified**: Both README.md and scratchpad.md had binary encoding issues causing Chinese characters to display as garbled text.

**Resolution**:
- Removed corrupted files
- Recreated README.md with proper UTF-8 encoding
- Recreated scratchpad.md with proper UTF-8 encoding

**Verification**:
```bash
file -I README.md scratchpad.md
```

**Current Status**:
All foundational files are ready with proper encoding:
- LICENSE (UTF-8)
- README.md (UTF-8, Chinese)
- .gitignore (ASCII)
- scratchpad.md (UTF-8, mixed English/Chinese)

**Awaiting**: User approval to make initial git commit

---

### 2025-01-29 - Initial Repository Setup Complete

**Completed Milestone**: Repository foundation has been successfully established.

**Repository Structure**:
```
US-Financial-Survival-Guide/
├── .git/
├── .gitignore
├── LICENSE (CC BY-NC-SA 4.0)
├── README.md (Chinese)
├── scratchpad.md (project planning document)
├── docs/
│   ├── medical-bills/
│   ├── credit-cards/
│   ├── emergency-finance/
│   ├── rights-protection/
│   └── case-studies/
├── guides/
├── templates/
└── resources/
```

**Questions for User**:
1. Should I proceed with the initial git commit now that encoding is fixed?
2. Would you like to review the files before committing?
3. Should we move to content development next, or switch to [Planner] mode for detailed content strategy?

**Waiting for**: User input on next steps

---

### 2025-01-29 - Docsify Website Complete & Deployed to GitHub

**Completed Milestone**: Full Docsify documentation website built and pushed to GitHub.

**What Was Built**:
- ✅ Docsify configuration (index.html) with Chinese language support
- ✅ Full-text search, pagination, copy code, emoji support
- ✅ Sidebar navigation with all sections
- ✅ Comprehensive medical bills guide (2000+ words)
- ✅ Placeholder pages for credit cards, emergency finance, rights protection, case studies
- ✅ FAQ, About, and supporting pages
- ✅ All files properly UTF-8 encoded
- ✅ Username updated from YOUR_USERNAME to ktwu01
- ✅ Tested locally at http://localhost:3000 - successful

**Git Commits**:
- `8b50e5d` - Initial repository foundation
- `a7466e4` - Docsify documentation website (12 files, 974 lines)
- `1ec1997` - Scratchpad update
- `7136737` - Update GitHub username to ktwu01

**Repository URL**: https://github.com/ktwu01/US-Financial-Survival-Guide

**Current Status**: All code pushed to GitHub successfully. Ready for GitHub Pages deployment.

**How Docsify Works** (for user understanding):
- Docsify is a **no-build** static site generator
- It runs entirely in the browser (client-side rendering)
- GitHub Pages serves the docs/ folder directly
- No build process, CI/CD, or configuration needed on GitHub
- Browser loads index.html → loads Docsify from CDN → Docsify reads .md files → renders beautiful site

**Next Action Required**: User must enable GitHub Pages:
1. Go to repository Settings → Pages
2. Set Source: Branch main, Folder /docs
3. Click Save
4. Wait 1-2 minutes for deployment
5. Visit: https://ktwu01.github.io/US-Financial-Survival-Guide/

**Waiting for**: User to enable GitHub Pages and confirm site is live

---

## Lessons Learned

### Project-Specific Lessons:
1. **Research shows gap in market**: No comprehensive Chinese-language financial survival guide for US students exists on GitHub (as of 2025-01-29 search)
2. **Medical bill negotiation is viable**: Multiple sources confirm 30-50% reduction possible with negotiation
3. **Credit card payment is trap**: Should NOT pay medical bills with credit cards (lose negotiation leverage, incur interest)
4. **Dollar For and CFPB are key resources**: These organizations provide free templates and guidance

### Technical Lessons:
1. **UTF-8 encoding critical for Chinese content**: Files created via Write tool initially showed binary encoding, requiring recreation to ensure proper UTF-8 handling
2. **File encoding verification**: Use `file -I filename` to check encoding before committing bilingual content
3. **Docsify is perfect for no-build documentation**: No npm dependencies, no build process, no CI/CD needed - just HTML + Markdown
4. **Client-side rendering works great for docs**: Docsify loads markdown files in the browser, making deployment trivial
5. **GitHub Pages with /docs folder**: Setting source to /docs folder keeps main repo clean and separates source from site files

---

## Notes & References

### Research Sources:
- Dollar For: Medical bill negotiation and charity care resources
- Consumer Financial Protection Bureau: Dispute templates and guidance
- NPR Life Kit: Medical bill negotiation strategies
- Multiple sources confirm lack of comprehensive guides targeting Chinese students specifically

### User Requirements:
- Must be Chinese-only (user decided against bilingual)
- Must cover content LLMs typically avoid
- Must be practical and actionable
- Must include 维权 (rights protection) strategies
- Must be searchable by both Chinese and American audiences (via keywords/tags)
- License: CC BY-NC-SA 4.0

---

**Last Updated**: 2025-01-29 by [Executor]
**Status**: UTF-8 encoding fixed. Ready for initial commit. Awaiting user approval.
