# Personal Budget & Expense Tracker

# Project Description

This project is a simple **Personal Budget & Expense Tracker** built using HTML and CSS. It allows users to enter expense information and view sample expenses in a structured table.

The project was developed by building on the Week 1 Budget Tracker project and adding forms, tables, multimedia, interactive elements, and advanced CSS selectors.

# Project Files

# 1. index.html

The `index.html` file contains the structure and content of the Budget Tracker.

It includes:

* A main heading called **My Budget Tracker**
* A logo image using the `<img>` element
* An **Add Expense** form
* Input fields for expense name, amount, and date
* A category dropdown containing:

  * Food
  * Transport
  * Rent
  * Entertainment
  * Other
* An **Add Expense** button
* An expense table containing Name, Amount, Category, and Date
* Five sample expense records
* A collapsible **How to use this tracker** section using `<details>` and `<summary>`
* An embedded YouTube budgeting video using `<iframe>`

# 2. style.css

The `style.css` file controls the appearance of the Budget Tracker.

It includes:

* Page background and font styling
* Heading and paragraph styling
* Form and input styling
* Button styling
* Table borders and spacing
* A colored table header
* Alternating table row colors using `tr:nth-child(even)`
* A hover effect on table rows
* Focus effects for input fields
* Styling for the details section
* Styling for the embedded video

# Advanced CSS Selectors

The project uses several advanced CSS selectors, including:

# Descendant Selector

.expenses-section td

This targets table data cells inside the expenses section.

### Direct Child Selector

```css
.add-expense-section > h2
```

This targets the heading that is a direct child of the Add Expense section.

### Position Pseudo-Class

```css
tr:nth-child(even)
```

This gives alternating background colors to even table rows.

### Negation Pseudo-Class

```css
input:not([type="date"])
```

This targets inputs except date inputs.

### Focus Pseudo-Class

```css
input:focus,
select:focus
```

This changes the appearance of an input or dropdown when the user clicks or focuses on it.

## Multimedia

The project includes:

* An image logo using the `<img>` element.
* A YouTube budgeting video embedded using an `<iframe>`.

# Interactive Elements

A `<details>` and `<summary>` element was added to create a collapsible section explaining how to use the tracker.

The table also has a hover effect that changes the background color when the mouse moves over a row.

The Add Expense button uses `cursor: pointer` to show that it can be clicked.

# Future Improvements

In future weeks, JavaScript can be added to make the Budget Tracker functional. The Add Expense button can then add new expenses to the table automatically, calculate totals, and allow users to manage their expenses.

# Technologies Used

* HTML5
* CSS3
* YouTube iframe
* Visual Studio Code
* GitHub
