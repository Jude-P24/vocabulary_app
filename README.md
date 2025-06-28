# vocabulary_app

A simple web application for managing Japanese vocabulary. You can add, edit and delete words and store them locally in your browser. The vocabulary can also be exported to a JSON file or loaded from a file. Each entry can be tagged with a **theme** which allows the list to be filtered.

This app runs entirely in your browser and does not require Node.js or any server.

## Usage

1. Open `index.html` in a web browser.
2. Fill in the form with the word's details (hiragana, English and theme are required).
3. Provide a **theme** for the entry to categorise it.
4. Click **Add Word** to save the entry.
5. Use the **Filter by Theme** dropdown above the table to show only words from a specific theme.
6. Use **Edit** or **Delete** in the table to modify your list.
7. Use **Save to File** to download your vocabulary as `vocabulary.json`.
8. Use **Load from File** to import a previously saved file.

9. Open `practice.html` to play a quiz game. Select one or more themes before starting.
All data is also stored in the browser's `localStorage` so your vocabulary stays when you reload the page.
