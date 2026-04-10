# Excel Skills Quiz

An interactive quiz covering **Basics**, **Formulas**, and **IF Statements** — built as a single HTML file, no server or dependencies needed.

## Features
- 12 multiple-choice questions with instant feedback
- Students enter their name before starting
- All results saved automatically in the browser (localStorage)
- Lecturer dashboard (password protected) shows all submissions
- Export results to CSV

## Lecturer password
```
lecturer123
```

## How to deploy on GitHub Pages

1. Create a new repository on GitHub (e.g. `excel-quiz`)
2. Upload `index.html` to the repository
3. Go to **Settings → Pages**
4. Under **Source**, select `main` branch and `/ (root)` folder
5. Click **Save**
6. Your quiz will be live at:
   ```
   https://YOUR-USERNAME.github.io/excel-quiz/
   ```
   (takes 1–2 minutes to go live after saving)

## Sharing with students
Send students the GitHub Pages URL above. They open it, enter their name, and take the quiz. You visit the same URL, click **Lecturer login**, and enter the password to see all results.

> **Note:** Because this uses `localStorage`, results are stored in each student's browser — not a shared server. Each device stores only its own submissions. For shared results across all students, you would need a backend (e.g. Firebase or Google Sheets).
