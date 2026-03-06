# Band Activity Tracker — User Guide

Welcome to the **Band Activity Tracker**! This app helps your band manage your song repertoire and keep track of gigs and setlists — all in one place. Here's everything you need to know to get started.

---

## Getting Started

When you first open the app, you'll see a sign-in screen.

- **Sign in** with your email and password to unlock full editing capabilities.
- **Continue in Read-Only Mode** if you just want to browse the repertoire and gigs without making changes. No account needed!
- Once you're signed in, you can **Lock** the app at any time using the lock button in the top-right corner.

---

## The Two Main Tabs

The app is organized into two sections, accessible via the tabs at the top:

| Tab | What it's for |
|-----|--------------|
| **Repertoire** | Manage your full song library |
| **Gigs & Setlists** | Track upcoming and past gigs and build setlists |

---

## Repertoire Tab

This is your band's master song library.

### Viewing Songs

- **Cards view** — Shows each song as a visual card with all its details.
- **Spreadsheet view** — A compact table layout, great for scanning a large library.

Switch between views using the **Cards / Spreadsheet** toggle in the top-right of the tab.

### Searching & Sorting

- Use the **Search** bar to filter songs by title, artist, genre, composer, or key — all at once.
- Use the **Sort** dropdown to order your list by Title, Artist, Genre, Key, or Date Added.

### Adding a Song (signed in only)

1. Click **+ Add Song** to open the Add Song form.
2. Fill in any of the following fields:
   - **Song Title** *(required)*
   - Artist / Original
   - Genre *(autocomplete suggestions from existing songs)*
   - Composers *(autocomplete suggestions from existing songs)*
   - Voicing
   - Key
   - Duration
   - Notes
3. Click **Save** to add the song to your repertoire.

> **Tip:** The Genre and Composers fields offer smart autocomplete — start typing and matching values from your existing songs will appear as suggestions. Use the arrow keys to navigate and Enter to select.

### Editing a Song (signed in only)

Click the **edit (pencil) icon** on any song card or row to make changes. Save when done.

### Deleting Songs (signed in only)

- Select one or more songs using their **checkboxes**, then click **Delete Selected**.
- You'll be asked to confirm before anything is permanently removed.

### Importing Songs via CSV (signed in only)

Have a spreadsheet of songs? You can import them all at once!

1. Click **Import CSV**.
2. Select a `.csv` (or `.xlsx` / `.xls`) file from your computer.
3. The app will match columns automatically. Supported column names include:
   `title`, `artist`, `duration`, `key`, `genre`, `composers`, `voicing`, `notes`
   *(case-insensitive)*

### Exporting Your Repertoire

Click **Export CSV** to download your full song library as a CSV file. Great for backups or sharing with bandmates.

---

## Gigs & Setlists Tab

Keep track of every gig — past and future — and build the perfect setlist for each one.

### Viewing Gigs

Each gig appears as a card showing its name, venue, date, and time. Click a gig to **expand** it and see its setlist. Click again to **collapse** it.

Use the **Expand All / Collapse All** buttons to quickly show or hide all gig details at once.

### Searching & Sorting Gigs

- Use the **Search** bar to filter gigs by name, venue, or notes.
- Use the **Sort** dropdown to order by Date, Name, or Venue.

### Adding a Gig (signed in only)

1. Click **+ Add Gig** to open the Add Gig form.
2. Fill in:
   - **Gig Name** *(required)*
   - Venue
   - Date
   - Time
   - Notes
3. Click **Save** to create the gig.

### Building a Setlist (signed in only)

Once a gig is created and expanded:

1. Use the **search box** inside the gig card to find songs from your repertoire.
2. Click a result to **add it to the setlist**.
3. **Reorder songs** by dragging and dropping them, or using the **up/down arrow buttons**.
4. Click the **✕** button next to a song to remove it from the setlist.

### Sharing a Setlist

Each gig has a **Copy Link** button that generates a shareable URL. Anyone with the link can open the app and jump directly to that gig's setlist — no login required.

### Importing Gigs via CSV (signed in only)

You can import multiple gigs at once using a CSV file. The supported columns are:

| Column | Description |
|--------|------------|
| `name` | Gig name *(required)* |
| `venue` | Venue name |
| `date` | Date (e.g. `2026-07-04`) |
| `time` | Time (e.g. `8:00 PM`) |
| `notes` | Any extra notes |
| `setlist` | Song titles separated by semicolons (e.g. `Song A; Song B; Song C`) |

### Exporting Gigs

Click **Export CSV** to download all your gigs and their setlists as a CSV file.

---

## Tips & Tricks

- **Read-only mode** is perfect for performers on stage who just need to view setlists — no accidental edits possible.
- The **deep-link setlist URL** is handy for sharing the night's setlist with bandmates before a gig.
- The app **syncs automatically** with the cloud, so all band members see the same data in real time.
- Song fields like Genre and Composers **remember your past entries** and offer autocomplete — keeping your data consistent.

---

## Keyboard Shortcuts

| Action | Shortcut |
|--------|---------|
| Navigate autocomplete suggestions | `↑` / `↓` arrow keys |
| Accept a suggestion | `Enter` |
| Dismiss suggestions | `Escape` |
| Submit sign-in form | `Enter` (in password field) |

---

*Happy performing! 🎶*
