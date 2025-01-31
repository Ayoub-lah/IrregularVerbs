# Verb Conjugation Web Application

## Project Description

This project is a web application designed to display complex verb conjugation data in a structured and user-friendly manner. The application organizes verb forms and their translations into an interactive table, providing features such as filtering, editing, adding, and deleting entries. The interface is divided into two panels: the left panel displays the verb table, and the right panel provides navigation links and additional information.

## Features

### 1. Interactive Two-Panel Layout
- The left panel displays a table of verbs and their translations.
- The right panel contains navigation links corresponding to the first letter of each verb.
- The panels can be swapped by clicking the "◀ ▶" button, and the table header remains visible at all times.

### 2. Dynamic Content Loading
- On page load, a JavaScript function reads the verb data from a predefined JavaScript table and populates the interface.

### 3. Expandable/Collapsible Panels
- Clicking the "▶" button collapses the right panel and expands the left panel to occupy the full width of the page. The button then changes to "◀" to allow reverting to the original layout.

### 4. Verb Management
- **Edit**: Displays a detailed view of the selected verb, including synonyms, example sentences, and images.
- **Update**: Allows updating verb details through a custom dialog box.
- **Delete**: Removes the selected verb from the table.

### 5. Alphabetical Navigation
- Clicking a link in the right panel scrolls the table to the first verb starting with the corresponding letter. The row is highlighted in red.

### 6. Add New Verbs
- Clicking the "Add a Verb" button opens a dialog to insert a new verb. The verb is added in alphabetical order.
- If the corresponding letter link does not exist in the right panel, it is automatically added.
- Empty verb fields are rejected, and rows with missing data are highlighted with a red border.

### 7. Search Functionality
- The "Find" button allows users to search for a verb. If found, the corresponding entry is displayed at the top of the left panel.

### 8. Real-Time Updates
- After any modification (add, edit, delete), the information displayed at the bottom of the right panel is updated dynamically.

---

## How to Use

### 1. **Load the Page**
   - The verb table is automatically populated with data from the JavaScript table when the page loads.

### 2. **Swap Panels**
   - Click the **"◀ ▶"** button to toggle between the expanded and collapsed views of the panels.
   - When the right panel is collapsed, the button changes to **"◀"**, allowing you to revert to the original layout.

### 3. **Navigate Alphabetically**
   - Click a letter link in the right panel to scroll to the first verb starting with that letter. The corresponding row is highlighted in red.

### 4. **Manage Verbs**
   - **Edit**: Click the **"Edit"** button next to a verb to view and modify its details in a custom dialog box.
   - **Update**: Save changes using the **"Update"** button in the edit dialog.
   - **Delete**: Remove a verb by clicking the **"Delete"** button next to it.

### 5. **Add a New Verb**
   - Click the **"Add a Verb"** button to open the add dialog.
   - Fill in the verb details and submit. The verb is added in alphabetical order.
   - If the corresponding letter link does not exist, it is automatically added to the right panel.

### 6. **Search for a Verb**
   - Use the **"Find"** button to search for a specific verb. If found, the table scrolls to the matching entry.

### 7. **View Real-Time Updates**
   - After any modification (add, edit, delete), the information at the bottom of the right panel is updated dynamically.

---

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/verb-conjugation-app.git
   
