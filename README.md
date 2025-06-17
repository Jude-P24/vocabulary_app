# vocabulary_app

A simple web application for managing Japanese vocabulary. You can add, edit and delete words and store them locally in your browser. The vocabulary can also be exported to a JSON file or loaded from a file.

This app runs entirely in your browser and does not require Node.js or any server.

## Usage

1. Open `index.html` in a web browser.
2. Fill in the form with the word's details (hiragana and English are required).
3. Click **Add Word** to save the entry.
4. Use **Edit** or **Delete** in the table to modify your list.
5. Use **Save to File** to download your vocabulary as `vocabulary.json`.
6. Use **Load from File** to import a previously saved file.

All data is also stored in the browser's `localStorage` so your vocabulary stays when you reload the page.
