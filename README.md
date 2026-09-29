
# Personal Budget & Expense Tracker

## Project Description

The Personal Budget & Expense Tracker is a beginner-friendly
web project built using HTML5 and CSS3. It demonstrates how
to organize expense information and present it through a
clean, consistent, and user-friendly interface.

This project builds on the work completed in Weeks 1 and 2.
Week 3 focuses on visual design, typography, colors, table
styling, form styling, and the CSS Box Model.

## Project Files

### 1. index.html

The `index.html` file provides the structure and content
of the application.

It contains:

- A page heading and budget tracker logo.
- An Add Expense form.
- Input fields for expense name, amount, and date.
- A category dropdown with Food, Transport, Rent,
  Entertainment, and Other.
- An Add Expense button.
- An expense table with Name, Amount, Category, and Date.
- Five sample expense records.
- A collapsible How to Use section.
- An embedded YouTube budgeting video.
- A footer identifying the project and week.

### 2. style.css

The `style.css` file controls the appearance and layout
of the application.

It includes:

- A consistent green, white, and light-gray color palette.
- Google Fonts for headings and body text.
- Card layouts for the heading, form, and expense table.
- Styled input fields, dropdowns, and buttons.
- Table borders, cell padding, and a colored header.
- Alternating table row colors.
- Table hover and form focus effects.
- Rounded corners, margins, padding, and borders.
- A responsive layout for smaller screens.

### 3. README.md

This file documents the project, explains the purpose
of each file, and describes the technologies and styling
techniques used.

## Color Palette

The project uses a consistent palette:

- Primary green: #176B45
- Dark green: #104B32
- Light green: #E5F4EB
- Background: #F3F7F4
- White: #FFFFFF

The colors provide a consistent appearance across headings,
buttons, table headers, and interface cards.

## Typography

Google Fonts are used to improve readability:

- Poppins is used for headings.
- DM Sans is used for body text, labels, inputs, buttons,
  and general content.

## CSS Box Model

The project uses:

- Margin to separate sections.
- Padding to create space inside cards and table cells.
- Borders to define sections and table cells.
- Border radius to create rounded corners.
- Box sizing to make element dimensions easier to manage.

## Advanced CSS Selectors

The stylesheet uses several advanced selectors:

- `.add-expense-section > h2` — direct child selector.
- `.expenses-section td` — descendant selector.
- `input:not([type="date"])` — negation pseudo-class.
- `input:focus` and `select:focus` — focus pseudo-classes.
- `tbody tr:nth-child(even)` — position pseudo-class.

## Technologies Used

- HTML5
- CSS3
- Google Fonts
- Visual Studio Code
- Git and GitHub

## Current Limitations

The expense table contains hardcoded sample data.
The Add Expense button is not functional yet because
JavaScript has not been implemented.

## Future Improvements

Future versions can include JavaScript to add expenses
dynamically, calculate totals, validate form entries,
and store expense records.

## How to Run

1. Download or clone the repository.
2. Open the project folder.
3. Open `index.html` in a web browser.
4. Ensure that `style.css` is in the same folder.
5. Connect to the internet for Google Fonts and the
   external logo and video to load.
