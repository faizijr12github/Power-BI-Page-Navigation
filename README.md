# Power BI Page Navigation UI/UX — Bookmarks & Selection Pane

> *Transforming a static Power BI dashboard into a dynamic, app-like experience with a slide-out navigation panel.*

---

## Overview

This project demonstrates a **modern and interactive Page Navigation system** in Power BI, built using **Bookmarks** and the **Selection Pane**.

The goal was to enhance user experience by creating a **dynamic slide-out navigation panel** — similar to modern web applications — while maximizing the dashboard canvas space available for data visualization.

---

## Objectives

-  Create a **dynamic navigation experience** inside Power BI
-  **Optimize report canvas space** by hiding navigation when not needed
-  Implement **modern UI/UX design patterns** within BI constraints
-  Master the use of **Bookmarks & Selection Pane** for interactive state control

---

##  Tools & Technologies

| Tool / Feature | Purpose |
|---|---|
| **Power BI Desktop** | Report development and design |
| **Bookmarks** | Capturing and switching between UI states |
| **Selection Pane** | Managing element visibility and layer order |
| **Action Buttons** | Triggering bookmark state changes on click |

---

##  Key Features

###  1. Dynamic Slide-Out Navigation Panel
A custom side panel slides in and out on demand, providing access to:

| Page | Description |
|---|---|
|  Summary Page | High-level KPI overview |
|  Customer Detail Page | Customer-level breakdown |
|  Product Detail Page | Product performance analysis |

Navigation is triggered via a **hamburger menu icon** — a familiar, intuitive interaction pattern borrowed from modern web design.

>  Provides a centralized navigation hub without cluttering the report canvas.

---

###  2. Canvas Space Optimization
- Navigation panel is **hidden by default**
- Full canvas width is available for visuals when navigation is closed
- Particularly effective for layouts that require:
  - Large, detailed tables
  - Wide, complex charts

>  Ensures a focus-driven, distraction-free data analysis experience.

---

###  3. Technical Implementation

####  Bookmark States

| State | Behavior |
|---|---|
| **Panel Open** | Navigation panel is visible |
| **Panel Closed** | Navigation panel is hidden |

####  How It Works

```
Selection Pane      →   Controls element visibility and layer order
        ↓
Bookmarks           →   Capture the visible/hidden state of each element
        ↓
Action Buttons      →   Trigger bookmark transitions on user click
        ↓
Result              →   Smooth toggle effect, identical to web app behavior
```

>  No custom visuals or external tools needed — built entirely with native Power BI features.

---

###  4. Seamless One-Click Interaction
- **Single click** on the hamburger icon toggles the panel open or closed
- **Instant page switching** without relying on default Power BI tab navigation
- Zero learning curve for end users

>  Delivers a professional, app-like experience inside a BI report.

---

###  5. Visual Design Language

| Design Element | Choice |
|---|---|
| **Layout** | Clean and minimal — data stays front and center |
| **Side Panel** | Subtle grey background for clear separation |
| **Visuals** | Rounded corners for a modern, soft aesthetic |
| **Active Page Indicator** | Purple/blue highlight to show current location |
| **Style Inspiration** | Glassmorphism — frosted, layered UI aesthetics |

>  Inspired by modern UI/UX trends while staying within Power BI's native capabilities.

---

## 💡 Benefits

| Benefit | Description |
|---|---|
|  **Improved Usability** | Users navigate intuitively without training |
|  **Easy Page Access** | All pages reachable from one consistent location |
|  **Better Screen Real Estate** | Canvas fully utilized for data when nav is hidden |
|  **Faster Experience** | Instant transitions with no page reload |
|  **Data-First Focus** | Navigation stays out of the way until needed |

---

##  Key Learnings

- Advanced use of **Bookmarks** to manage UI state in Power BI
- Managing element **layers and visibility** using the Selection Pane
- Designing **interactive, app-like dashboards** within native Power BI features
- Applying **UI/UX principles** (hierarchy, focus, familiarity) to BI report design

---

##  Use Cases

This technique is ideal for:

-  **Interactive dashboards** with multiple sections or pages
-  **Executive-level reports** requiring a polished, professional feel
-  Reports with **3+ pages** that need intuitive navigation
-  Any scenario where **maximizing canvas space** is a priority

---

##  Outcome

-  Built a **modern, slide-out navigation system** using only native Power BI features
-  Delivered a **clean, interactive, and user-friendly** reporting experience
-  Transformed a static dashboard into a **dynamic BI application**

---

##  Screenshots

### Navigation Panel — Open State
![Navigation Panel Open](https://github.com/user-attachments/assets/3ababc59-d1e1-4376-ab64-351585c601d7)

*The slide-out panel reveals page links with the active page highlighted — triggered by the hamburger menu.*

---

### Navigation Panel — Closed State
![Navigation Panel Closed](https://github.com/user-attachments/assets/7753b546-4fd9-46f9-9a7e-1942325576ff)

*Panel hidden — the full canvas is reclaimed for data visualization.*

---

##  Project Structure

```
 powerbi-navigation-ux
 ┣  PowerBI_Navigation_UX.pbix        # Main Power BI report file
 ┣  screenshots/                       # Open and closed state previews
 ┗  README.md                          # Project documentation
```

---

##  Connect

If you found this project useful or have suggestions, feel free to open an **Issue** or submit a **Pull Request**.
