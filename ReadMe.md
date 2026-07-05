# Kigali Pacific College — Admissions Page

A simple one-page website that helps **Kigali parents** find school information quickly and **call or visit** Kigali Pacific College with the details they need.

---

## Tech Stack

| Tool | Used for |
|------|----------|
| **HTML** | Page structure and content |
| **CSS** | Layout, colors, fonts, and styling |
| **Google Fonts** | Montserrat (headings) and Inter (body text) |

No JavaScript, no frameworks, no backend — just HTML and CSS.

---

## Purpose

This page gives parents everything they need before contacting the school:

- Admissions dates and a quick way to **call**
- **Location**, **programs**, and **school hours**
- **Registration** requirements and how to apply
- **School fees** and what is included
- **Payment** partner banks

Parents can read the information at their own pace and tap **Call** when they are ready to visit or ask more questions.

---

## Colors Used

| Color | Hex | Where it is used |
|-------|-----|------------------|
| White background | `#ffffff` | Main page background |
| Black text | `#000000` | Headings, body text, button labels |
| Yellow accent | `#d4d900` | Year text, card borders, Call buttons |

---

## How to Learn It

If you are new to web development, study the project in this order:

1. **Open `index.html`** — see how sections are built with tags like `<header>`, `<section>`, `<article>`, and `<a>`.
2. **Open `style.css`** — see how colors, fonts, and spacing are controlled.
3. **Change one thing** — try updating a color in `:root` and refresh the browser.
4. **Use browser DevTools** — right-click the page → Inspect to see which CSS rule styles each element.
5. **Learn the basics** — [MDN HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) and [MDN CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) are free and beginner-friendly.

### Key concepts in this project

- **Flexbox & Grid** — arranges cards and bank logos in rows
- **CSS variables** — stores colors and fonts in one place (`:root`)
- **Google Fonts** — loads Montserrat and Inter from the web
- **`tel:` links** — makes Call buttons open the phone dialer on mobile

---

## User Flow


```
1. Land on page
   └── See "Admissions Now Open! 2026 - 2027"

2. Check basic info
   ├── Located   → school address
   ├── Programs  → age groups offered
   └── School Hours → when the school is open

3. Read registration details
   ├── Imyanya      → available spots
   ├── Ibisabwa     → required documents
   └── How to apply → steps to register
   └── Tap "Call" if they need help

4. Review school fees
   ├── First Term fee
   ├── Application fee
   └── Uniform cost

5. Check payment options
   └── See partner banks (BK, I&M, Equity)

6. Take action
   └── Tap "Call" to contact the school
```

---

## How to View the Page

1. Open the project folder
2. Double-click `index.html`, or
3. Right-click `index.html` → Open with → your browser

---

## Project Files

```
├── index.html      # Page content
├── style.css       # All styling
├── images/         # Bank logos
└── Figma_UI_UX/    # Original design reference
```
