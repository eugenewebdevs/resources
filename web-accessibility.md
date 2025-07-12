# 🌐 Web Accessibility Audit Guide

**Contributed by Joel Southall for the Eugene Web Devs community**  
_Last updated: 2025-07-01_

---

## 📣 Why Accessibility Matters

Web accessibility ensures that websites are usable by **everyone**, including people with visual, auditory, cognitive, and motor disabilities. Making accessible websites:

- Improves **usability** for all users
- Enhances **SEO** and **performance**
- Reduces legal risk (e.g., ADA compliance)
- Promotes **equity**, **inclusion**, and **respect**

> Accessibility is not a feature — it’s foundational to ethical and professional web development.

---

## 🛠️ Tool #1: Google Lighthouse

**Lighthouse** is a free, open-source auditing tool built into Google Chrome. It runs a series of automated tests on a webpage and generates a report with suggestions for improvement — including accessibility.

---

### ✅ How to Run a Lighthouse Accessibility Audit

1. Open the website in **Google Chrome**
2. Right-click anywhere → Click **“Inspect”** (to open DevTools)
3. Navigate to the **“Lighthouse”** tab
4. Under **Categories**, check only **“Accessibility”**
5. Choose either **Mobile** or **Desktop**
6. Click **“Analyze page load”** or **“Generate report”**

---

### 🔍 What Lighthouse Tests For

Lighthouse automatically checks for issues such as:

- **Color contrast** problems
- **Missing alt text** on images
- **Improper label associations** for form inputs
- **Keyboard focusability**
- Use of semantic **landmarks** and ARIA roles

These are common and crucial issues that impact screen reader users and keyboard-only users.

---

### 🧠 How to Read the Results

- Reports are scored from **0–100**
- Each issue includes:
  - A **description**
  - **HTML snippet** where it occurs
  - A **link to documentation** for remediation

Click “Learn more” under each issue to get guidance on how to fix it.

---

### 💾 Saving the Report

- After generation, click the **“Export”** button
- Save as **HTML** or **JSON** to keep a copy
- You can attach the file in an issue or accessibility audit report

---

### ⚠️ Reminder: Lighthouse Isn’t Everything

While Lighthouse is a good starting point, it only catches around **30–40%** of real-world accessibility issues. Manual testing and use of assistive technologies (like screen readers) are still needed for a full audit.
We will be building this out to be more expansive.

---

## 📦 Coming Next

Future updates to this guide will include:

- **axe DevTools** for deeper automated checks
- **WAVE** for visual issue overlays
- **Accessibility Insights** for guided manual testing
- **Screen reader testing basics** using NVDA and VoiceOver

---

## 💬 Contribute

Have accessibility tools or tips you use? Found a resource that helped you learn?  
We welcome contributions — fork this repo and submit a pull request!

