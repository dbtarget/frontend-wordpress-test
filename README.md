# 🧪 Frontend + WordPress Developer

## Overview
- **Duration:** `90` minutes
- **Stack:** WordPress (`Gutenberg`) + Next.js v15.3+|
- **Focus:** Custom Blocks, React Server Components (RSC), Responsive Design
- **Goal:** Build a Case Study page in both WordPress and Next.js

---

## Part 1 – WordPress (45 min)

Build a **page template** titled `Case Study Page` with two custom `Gutenberg` blocks.

1. **Hero Block** → Title, Subtitle, Background Image.
2. **Case Study Item Block** → Project Title, Description, Image, Link.

- Assemble a Case Study Page with **at least 2 case studies**.
- Ensure **responsive design** and **semantic HTML**.

---

## Part 2 – Next.js (45 min)

Create a `/case-studies` page in **Next.js**.

- Fetch and render **mock JSON data** (provided [below](#mock-data)).
- Display case studies in a **responsive grid**.
- Use **RSC** for data fetching (no client-side fetch for the main list).
- Add a **client-side search bar** to filter by title.
- Style as a **responsive grid**

## Bonus Challenge (Optional)

Expose the `Gutenberg` Case Study data via the `WordPress REST API` and
fetch it in Next.js instead of mock JSON.

## Mock Data

Download from [case-studies.json](api/case-studies.json)
