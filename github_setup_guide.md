# 🚀 GitHub Profile Setup - Complete Guide

## Phase 1: Initial Setup (5 minutes)

### Step 1: Create Special Repo
1. Go to **github.com/new**
2. **Repo name:** `Aman620-tech` (MUST match your GitHub username exactly)
3. **Description:** Full Stack Engineer - System Design & Cloud
4. **Public** (checked)
5. ✅ Add README file
6. Click **Create Repository**

### Step 2: Add the README Content
1. Click on **README.md**
2. Click **Edit** (pencil icon)
3. Paste the complete README from `github_profile_readme.md`
4. Scroll down → Click **Commit changes**
5. Message: "Initial GitHub profile setup"
6. Commit to `main` branch

✅ **Your profile now appears at:** github.com/Aman620-tech

---

## Phase 2: Make Repos Shine (Optional but Important)

### Add README to Your Best Projects

For each major project (BookAnArtist, Cricket Pitch, Multi-Courier, Feature Flags):

**1. Edit each repo's README.md:**
```markdown
# Project Name
**Brief description (1-2 lines)**

## 🎯 Features
- Feature 1
- Feature 2

## 🛠 Tech Stack
- Node.js, NestJS, MongoDB, Redis, etc.

## 📦 Installation
\`\`\`bash
git clone https://github.com/Aman620-tech/project-name
cd project-name
npm install
\`\`\`

## 🚀 Usage
[Add quick usage example]

## 📚 What I Learned
- Key learning 1
- Key learning 2

## 📝 License
MIT
```

**2. Add topics to each repo** (visible on repo page):
- Go to Settings → About
- Add keywords: `nodejs`, `system-design`, `redis`, `microservices`, etc.

---

## Phase 3: Pinned Repositories (Showcase Best Work)

1. Go to your **Profile** → Customize your pins
2. Pin your **4-5 best projects**:
   - ✅ BookAnArtist (or a public version)
   - ✅ Cricket Pitch Booking System
   - ✅ Multi-Courier Integration
   - ✅ Feature Flag Management
   - ✅ Portfolio/Resume repo

**How to pin:**
- Click **"Customize your pins"** on your profile
- Check the boxes for projects you want visible
- Drag to reorder
- Save

---

## Phase 4: Add Dynamic Badges & Advanced Elements

### Option A: Activity Graph (Cool streaks visualization)
Add this to your README somewhere:

```markdown
### 📊 Activity
[![Aman's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=Aman620-tech&theme=react-dark)](https://github.com/ashutosh00710/github-readme-activity-graph)
```

### Option B: GitHub Contributions Snake (Fun animation)
Add at bottom of README:

```markdown
### 🐍 Contributions Snake
![snake gif](https://github.com/Aman620-tech/Aman620-tech/raw/output/github-contribution-grid-snake.svg)
```

Setup:
1. Create `.github/workflows/snake.yml` in your profile repo
2. Paste this code:

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * 0"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2

      - uses: platane/snk@master
        id: snake-svg
        with:
          github_user_login: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake.dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v2.6.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

3. Commit and it auto-runs weekly!

---

## Phase 5: Links & Optimization

### Update Your Links Everywhere
```
GitHub:           github.com/Aman620-tech
LinkedIn:         linkedin.com/in/aman-k-pandey
Email:            pandeyaman997@gmail.com
Portfolio:        amankumarpandey.com
```

### Make Repo Descriptions Stand Out
Instead of generic: "My project"

Use specific, keyword-rich descriptions:
- ✅ "High-throughput notification service with BullMQ, rate limiting & DLQ"
- ✅ "Real-time concurrent booking system using Redis distributed locks"
- ✅ "Microservices architecture with system design patterns"

---

## Phase 6: Best Practices Checklist

- [ ] Profile README created & looks good
- [ ] 4-5 best projects pinned
- [ ] Each major repo has detailed README
- [ ] Topics added to repos (helps discovery)
- [ ] All projects are **Public** (recruiters can't see private)
- [ ] Activity graph or snake animation added (optional but cool)
- [ ] Links updated in bio
- [ ] At least 5-10 quality commits per major project (shows consistency)

---

## Common Mistakes to Avoid

❌ **Empty/minimal READMEs** → Recruiters skip it  
✅ Add context, tech stack, learnings

❌ **All projects private** → Visible only to you  
✅ Make best work public

❌ **Generic descriptions** → "Node.js project"  
✅ Be specific: "Payment processing service with Stripe/Razorpay"

❌ **No recent activity** → Looks abandoned  
✅ Commit something monthly

❌ **Too many projects, no quality** → Overwhelming  
✅ Better to have 4 polished projects than 20 half-baked ones

---

## Quick Win: Update Bio

GitHub Settings → Public profile:
```
🔧 Full Stack Engineer | Node.js | System Design
📍 Indore, India | 🎯 Open to Remote/PAN India
💼 4+ yrs @ BookAnArtist | Building scalable systems
🔗 amankumarpandey.com
```

---

## Testing Your Profile

1. Logout from GitHub
2. Visit: github.com/Aman620-tech
3. View as a recruiter would
4. Check if:
   - ✅ Profile looks attractive
   - ✅ Pinned repos are visible
   - ✅ Bio is clear
   - ✅ Links work
   - ✅ Stats display correctly

---

## Going Further (Advanced)

### Create a Portfolio Repo
```
/portfolio or /resume
├── README.md (Your story)
├── /projects (links to all projects)
├── /resume (PDF version)
└── /certificates (if any)
```

### Host a Portfolio Site
- **Next.js + Vercel** (recommended for you)
- Showcase projects with live demos
- Link from GitHub bio

### Weekly Activity
- Commit once weekly to stay visible
- Even small improvements count
- Helps with GitHub rankings

---

## After Setup: Interview Talking Points

Recruiters will ask about:
1. **"Tell me about BookAnArtist"** → Point to README
2. **"Show me your system design work"** → Link Cricket Pitch or Courier projects
3. **"How do you handle scale?"** → Mention Redis, caching, microservices
4. **"What's your strength?"** → Backend architecture, system design, cloud

---

**Done! Your profile is now recruiter-ready. 🎉**