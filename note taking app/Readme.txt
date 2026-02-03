# Note Taking App

A simple, clean note taking web app built using plain HTML, CSS, and JavaScript. Notes are saved locally in the browser, so your data stays even after refreshing or closing the tab.

---

## Features

* Create, edit, and delete notes
* Notes are stored using browser LocalStorage
* Dark mode and light mode toggle
* Responsive grid layout for notes
* Clean dialog based UI for adding and editing notes
* No backend, no frameworks

---

## Project Structure

```
├── index.html   # Main HTML structure
├── style.css    # Styling and themes (light & dark)
├── app.js       # Application logic
└── README.md
```

---

## How It Works

### 1. Notes Storage

* Notes are stored in `localStorage` under the key `quickNotes`
* Each note has:

  * `id` (generated using timestamp)
  * `title`
  * `content`

### 2. Adding a Note

* Click **Add Note**
* A dialog opens
* Enter title and content
* On save, the note is added to the top of the list

### 3. Editing a Note

* Click the edit icon on a note
* The same dialog opens in edit mode
* Existing data is pre-filled
* Saving updates the note instead of creating a new one

### 4. Deleting a Note

* Click the delete icon on a note
* The note is removed instantly

### 5. Theme Toggle

* Click the moon/sun button in the header
* Theme preference is saved in `localStorage`
* Automatically applied on page reload

---

## Technologies Used

* HTML5
* CSS3 (CSS variables, grid, dialog)
* Vanilla JavaScript (DOM, LocalStorage)

---

## How to Run

1. Download or clone the project
2. Open `index.html` in any modern browser
3. Start creating notes

No server or installation required.

---

## Browser Support

* Works in all modern browsers
* Uses `<dialog>` element (recommended: Chrome, Edge, Firefox latest)

---

## Possible Improvements

* Search notes
* Pin important notes
* Categories or tags
* Export notes as text or JSON
* Sync using backend or cloud

---

## Author

Adwait Pote

---

Simple, fast, and distraction free note taking.
