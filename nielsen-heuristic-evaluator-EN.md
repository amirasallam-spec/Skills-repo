---
name: nielsen-heuristic-evaluator
description: |
  Complete UX evaluation using Nielsen's 10 heuristics. Use for interface audits, Figma prototypes, websites, and apps.
  Triggers: "Nielsen heuristics", "UX audit", "heuristic evaluation", "interface review", "Figma analysis".
  Provides scores 1-5, concrete evidence, priority recommendations with effort/impact ROI.
---

# NIELSEN HEURISTIC EVALUATOR - PRO VERSION 2026

## 🎯 WHEN TO USE (Auto-recognition)
Activate this skill for any UX/UI analysis based on **Jakob Nielsen's 10 heuristics (1994, updated 2023)**.

**Explicit triggers**: heuristics, Nielsen, UX audit, interface review, heuristic evaluation, Figma review
**Implicit contexts**: "is this design good?", "improve this UI", "analyze this prototype"

---

## 📋 MANDATORY EVALUATION FLOW (5 fixed steps)

### Step 1: Gather context
❓ Systematic questions to ask:
- Figma link / URL / prototype?
- Annotated screenshots?
- Context: mobile / desktop / tablet?
- Target audience (language, UX pros, general public)?
- Business goals (SEO, engagement, conversion)?

### Step 2: Systematic analysis (The 10 heuristics)
For **each heuristic**:
- **Score**: 1-5 (1 = severe violation, 5 = exemplary)
- **Concrete evidence**: Screenshot / link + precise description
- **2026 Benchmark**: WCAG 2.2, Material Design 3, iOS Human Guidelines
- **Priority fix**: Action + effort (Low / Medium / High) + estimated impact (%)

### Step 3: Weighted global score
- Final score = Weighted average:
  - Visibility (x3), User control (x2), Error prevention (x2)
  - Other heuristics (x1)
- Estimated SUS: 62.5 + (global_score × 7.5)

### Step 4: Heatmap + Top 3 priorities
- 🔴 SEVERE (1-2) → Fix immediately
- 🟡 MODERATE (3) → Fix next week
- 🟢 OK (4-5) → Maintain

### Step 5: Actionable roadmap
- 📅 30 days: Red fixes
- 📅 60 days: Yellow fixes
- 📅 90 days: Green optimizations

---

## 🔍 THE 10 HEURISTICS - EXHAUSTIVE CHECKLIST

**1️⃣ VISIBILITY OF SYSTEM STATUS (weight x3)**
- ☐ Immediate feedback <100ms (loader, spinner, toast)
- ☐ Current position clear (breadcrumb, step 3/5)
- ☐ Server state visible (online/offline, sync)

**2️⃣ MATCH BETWEEN SYSTEM AND REAL WORLD**
- ☐ Natural language (no technical jargon)
- ☐ Concrete metaphors (🛒 cart, 💖 like)
- ☐ Local units and conventions

**3️⃣ USER CONTROL & FREEDOM (weight x2)**
- ☐ Undo/Redo (Ctrl+Z) functional
- ☐ Emergency exit (❌ visible everywhere)
- ☐ Confirmation before destructive action
- ☐ Non-linear navigation possible

**4️⃣ CONSISTENCY & STANDARDS**
- ☐ Material Design 3 / iOS 18 guidelines respected
- ☐ Platform conventions (mobile swipe, desktop hover)
- ☐ Consistent terminology across the product
- ☐ Dark / Light mode supported

**5️⃣ ERROR PREVENTION (weight x2)**
- ☐ Real-time validation (email, phone)
- ☐ Explicit constraints (8+ characters, 2MB max)
- ☐ Autosave + recovery
- ☐ Confirmation before data loss

**6️⃣ RECOGNITION OVER RECALL**
- ☐ Icons + labels (no standalone icon)
- ☐ Autocomplete + suggestions
- ☐ Tooltips on hover / focus
- ☐ Recent search history

**7️⃣ FLEXIBILITY & EFFICIENCY**
- ☐ Novice / expert mode available
- ☐ Keyboard shortcuts
- ☐ Bulk actions
- ☐ 100% keyboard navigation

**8️⃣ AESTHETIC & MINIMALIST DESIGN**
- ☐ 1 primary CTA per screen
- ☐ Clutter ratio <30%
- ☐ Typography: 3 sizes max
- ☐ White space >20%

**9️⃣ HELP USERS RECOGNIZE, DIAGNOSE & RECOVER FROM ERRORS**
- ☐ Solution-oriented messages
- ☐ Example: "Invalid email → try john@example.com"
- ☐ Never "Error 500" without explanation
- ☐ Always a corrective action suggested

**🔟 HELP & DOCUMENTATION**
- ☐ ? → tooltip → help article
- ☐ Predictive FAQ
- ☐ Shortcuts cheat sheet available
- ☐ Embedded video if needed

---

## 📊 STANDARD REPORT TEMPLATE

```
📊 NIELSEN HEURISTIC AUDIT
Design: [Name / URL] | Context: [mobile / desktop] | Date: [MM/DD/YYYY]

🔥 VIOLATION HEATMAP
🔴 [Number] severe | 🟡 [Number] moderate | 🟢 [Number] OK

📋 EVALUATION TABLE
#  | Heuristic           | Score | Evidence        | Fix               | Effort / Impact
1  | Visibility          | 2/5   | No loader       | Add spinner       | Low / High
...

GLOBAL SCORE: [X.X]/5 | Estimated SUS: [XX]/100

🚀 TOP 3 PRIORITIES
1. [Fix #1] → +[X]% conversion
2. [Fix #2] → -[X]% bounce rate
3. [Fix #3] → +[X]% engagement

📅 90-DAY ROADMAP
- 30 days: [Red fixes]
- 60 days: [Yellow fixes]
- 90 days: [Green optimizations]
```

---

## 🎯 UX PRO INTEGRATIONS
- **Figma**: "Generate a prototype with these fixes"
- **Analytics**: KPIs to track post-fix
- **SEO**: Recalculate meta descriptions if relevant
- **Accessibility**: Systematic WCAG 2.2 check

---

## ✅ TEST
Say: `"Evaluate this design using Nielsen heuristics"` then attach your screens (PNG, PDF or Figma link via MCP).
