# SpendWise Dashboard Shell

## Project Description

SpendWise is a personal finance dashboard designed to help
users view and understand their spending across different
financial categories.

This project is the foundation of the capstone project.
Week 4 focuses on creating the visual dashboard structure
using modern CSS layout techniques.

The dashboard currently contains static information only.
No JavaScript functionality has been added.

---

## Project Files

### index.html

The `index.html` file contains the structure of the
SpendWise Dashboard.

It includes:

- A sidebar navigation menu.
- A dashboard header.
- A welcome message.
- User information.
- Six financial category cards.
- Food spending information.
- Transport spending information.
- Rent spending information.
- Entertainment spending information.
- Savings information.
- Utilities information.
- Summary cards for total expenses, savings, and budget.
- A dashboard footer.

---

### style.css

The `style.css` file controls the complete visual
appearance and layout of the dashboard.

It includes:

- CSS Grid for the main dashboard layout.
- CSS Grid for the category cards.
- Flexbox for the sidebar navigation.
- Flexbox for the dashboard header.
- Flexbox for the content inside each dashboard card.
- CSS custom properties for the application theme.
- Responsive design.
- Card hover effects.
- Keyboard focus effects.
- Dark theme support.

---

## CSS Grid

CSS Grid is used to create the overall dashboard structure.

The main layout contains:

- A sidebar.
- A main content area.

CSS Grid is also used to arrange the six financial
category cards into three columns on larger screens.

---

## Flexbox

Flexbox is used for:

- Sidebar navigation.
- Dashboard header.
- User information.
- Card content.
- Card icons.
- Responsive navigation.

This makes the dashboard flexible and easier to organize.

---

## CSS Custom Properties

The project uses CSS variables inside the `:root`
selector.

Examples include:

```css
--brand-color
--accent-color
--background-color
--surface-color
--primary-text
--secondary-text
