# SheetLock — Your Data. Your Rules.

SheetLock is a **private, offline-first spreadsheet app** for Android. It gives you the full power of a spreadsheet — formulas, formatting, charts — combined with device-level security so your sensitive data never leaves your phone.

No account required. No cloud. No tracking. Just a padlock on your spreadsheets.

---

## Why SheetLock?

Google Sheets has no password protection. SheetLock is the spreadsheet app that puts **your privacy first**. Whether you manage staff salaries, track household expenses, or store any data you'd rather keep to yourself, SheetLock keeps it locked down.

---

## Key Features

### Security & Privacy

- **PIN Lock** — 6-digit PIN protects the entire app. No one opens SheetLock without it.
- **Biometric Unlock** — Use fingerprint or face recognition for quick access.
- **Fake PIN (Decoy Mode)** — Set a second PIN that opens an empty, decoy version of the app. If someone forces you to unlock, they see nothing. *(Pro)*
- **Workbook-Level Lock** — Give individual workbooks their own separate PIN, independent of the app PIN. *(Pro)*
- **Auto-Lock** — Automatically locks when you switch apps. Choose from Immediately, 30 seconds, 1 minute, 5 minutes, or 10 minutes.
- **Screenshot Prevention** — Block screenshots and hide the app from the recent-apps thumbnail. *(Pro)*
- **Encryption at Rest** — All data is encrypted on your device using SQLCipher (AES-256). Preferences use Android EncryptedSharedPreferences.
- **Fully Offline** — Your spreadsheet data never touches a server. Everything stays on your device.

### Spreadsheet Editor

- **Canvas-Rendered Grid** — Smooth, high-performance scrolling at 60fps with up to 1,000 rows and 52 columns per sheet.
- **Formula Bar** — View and edit formulas in a dedicated bar. Tap the cell reference to jump to any cell.
- **Cell Editing** — Double-tap to edit. Type a value or start with `=` to enter a formula with autocomplete suggestions.
- **Multi-Sheet Workbooks** — Organize data across multiple sheet tabs within a single workbook.
- **Undo & Redo** — Up to 50 levels of undo for cell edits, formatting, row/column changes, and paste operations.
- **Copy, Cut & Paste** — Supports single-cell and multi-cell operations with automatic reference adjustment. Cross-sheet paste supported.
- **Column & Row Resizing** — Drag borders to resize, or double-tap to auto-fit content.
- **Freeze Panes** — Freeze the top row, first column, or multiple rows/columns to keep headers visible while scrolling.
- **Pinch to Zoom** — Scale the grid from 0.5× to 2.0× for comfortable viewing.
- **Search & Replace** — Find text across the active sheet with options for case-sensitive, whole-cell, regex, and formula search. Replace one match or all at once.

### 40+ Formulas

SheetLock supports a full formula engine with autocomplete, cell references (relative, absolute, mixed, cross-sheet), and standard error handling (`#DIV/0!`, `#REF!`, `#NAME?`, `#VALUE!`).

| Category | Formulas |
|---|---|
| **Math & Stats** | SUM, AVERAGE, COUNT, COUNTA, MAX, MIN, ROUND, ABS, SQRT, POWER, MOD, INT, CEILING, FLOOR |
| **Logical** | IF, AND, OR, NOT, IFERROR, IFS |
| **Text** | CONCAT, LEFT, RIGHT, MID, LEN, UPPER, LOWER, TRIM, SUBSTITUTE, TEXT |
| **Lookup** | VLOOKUP, HLOOKUP, INDEX, MATCH |
| **Conditional** | SUMIF, COUNTIF, AVERAGEIF |
| **Date & Time** | TODAY, NOW, DATE, DAY, MONTH, YEAR, DATEDIF, DAYS |

Free users get the basics (SUM, AVERAGE, COUNT, IF). Pro unlocks all 40+ formulas.

### Cell Formatting

- **Text Styles** — Bold, italic, underline, strikethrough, and 12 font sizes.
- **Colors** — 16 preset text and background colors, plus custom hex color picker.
- **Alignment** — Left, center, right horizontal alignment.
- **Number Formats** — General, Number (with thousands separator), Currency (INR ₹ / USD $), Percentage, Date, and custom formats.
- **Borders** — All borders, outer border, bottom border, with multiple styles (thin, medium, thick, dashed, dotted) and colors.
- **Conditional Formatting** — Automatically highlight cells based on rules: greater than, less than, between, equal to, text contains, duplicates, top N, or empty cells. *(Pro)*
- **Format Painter** — Copy formatting from one cell to another with a single tap.
- **Cell Merge** — Merge and unmerge cells for cleaner layouts.

### Charts & Graphs *(Pro)*

Create visual charts directly from your data:
- **Bar Chart** — Compare categories side by side.
- **Line Chart** — Visualize trends over time.
- **Pie Chart** — Show percentage distributions.

Charts update automatically when the underlying data changes.

### Data Tools

- **Sorting** — Sort rows A→Z or Z→A by any column. Multi-column sorting supported.
- **Filters** — Filter rows by text, number, or date conditions. Filter arrows appear in header rows.
- **Data Validation** — Restrict cell input with rules: number range, text length, dropdown list, date range, or custom formula. Show errors or warnings on invalid input.
- **Cell Notes** — Attach notes to any cell. A small triangle indicator shows which cells have notes.
- **Hidden Rows & Columns** — Hide sensitive rows or columns. Hidden data still participates in formulas. *(Pro)*

### Import & Export

- **Import** — Open `.xlsx`, `.xls`, `.csv`, and `.tsv` files. Import from the file picker, or receive files directly from Gmail, WhatsApp, Google Drive, or any app via the Android share menu.
- **Export to Excel** — Save your workbook as `.xlsx` with all sheets, values, and formatting.
- **Export to CSV** — Export the active sheet as a `.csv` file.
- **Export to PDF** — Export as a formatted A4 landscape PDF with borders, colors, and page numbers. Pro users can export all sheets as a multi-page PDF.
- **Share** — Send exported files via WhatsApp, email, Google Drive, or any sharing app.

### Templates

Get started quickly with ready-made templates:

| Template | Category |
|---|---|
| Monthly Budget | Finance |
| Staff Attendance | Business |
| Grocery List | Personal |
| Invoice | Business *(Pro)* |
| EMI Calculator | Finance *(Pro)* |
| Expense Tracker | Finance *(Pro)* |
| Salary Sheet | Business *(Pro)* |
| Study Timetable | Personal *(Pro)* |
| Stock Inventory | Business *(Pro)* |
| Workout Log | Personal *(Pro)* |

All templates are fully editable. Formulas recalculate automatically as you fill in your own data.

### Cloud Backup *(Pro)*

- **Encrypted Backup** — Back up all workbooks to your own Google Drive, encrypted with AES-256 before upload. The encryption key never leaves your device.
- **Restore** — Restore from any previous backup with a few taps.
- **Auto Backup** — Schedule daily or weekly backups. Runs on WiFi only, keeps the last 3 backups.

### Autosave

Every change is automatically saved to the local encrypted database. You'll see a "Saved ✓" indicator in the editor — no manual saving needed.

---

## Free vs Pro

SheetLock is free to use with generous limits. Upgrade to **SheetLock Pro** for the full experience.

| | Free | Pro |
|---|---|---|
| Workbooks | 3 | Unlimited |
| Sheets per workbook | 3 | Unlimited |
| Basic formulas | Yes | Yes |
| All 40+ formulas | — | Yes |
| Import (XLSX, CSV) | Yes | Yes |
| Export (XLSX, CSV, PDF) | Single sheet | All sheets |
| Templates | 3 free | All 10 |
| Basic formatting | Yes | Yes |
| Conditional formatting | — | Yes |
| Charts & graphs | — | Yes |
| Workbook PIN lock | — | Yes |
| Hidden rows/columns | — | Yes |
| Fake PIN decoy | — | Yes |
| Screenshot prevention | — | Yes |
| Google Drive backup | — | Yes |
| Ad-free | — | Yes |

**SheetLock Pro** is a **one-time purchase** — no subscription, no recurring fees. Pay once, use forever.

---

## Works Offline

SheetLock is designed to work without an internet connection. Creating workbooks, editing cells, running formulas, importing and exporting files, templates — everything works offline. The only features that need internet are cloud backup, purchasing Pro, and displaying ads.

---

## Accessibility

- Minimum 48dp tap targets for all interactive elements
- Full TalkBack / screen reader support
- Text scales with system font size
- High contrast (4.5:1 minimum)
- External keyboard navigation
- RTL layout support

---

## Links

- [Privacy Policy](https://sheetlock.github.io/privacy-policy.html)
- [Terms & Conditions](https://sheetlock.github.io/terms.html)
- [Contact Support](mailto:nagaraju.chitimilla@gmail.com)

---

*SheetLock — Your data. Your rules.*
