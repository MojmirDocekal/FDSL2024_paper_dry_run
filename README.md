# Working on your article in this repository

This repository is used for writing and revising your TeX article (`main.tex`) together with editor feedback through GitHub Issues.

## 1) Edit `main.tex`

### Option A (recommended for quick edits): directly on GitHub
1. Open the repository in your browser.
2. In the file list, **click `main.tex`**.
3. Click the **pencil icon (Edit this file)** in the top-right.
4. Make your small changes and save by committing (see section 3).

### Option B (recommended for bigger edits): online VS Code (`github.dev`)
1. Open the repository page.
2. Press **`.` (dot)** on your keyboard, or change `github.com` in the URL to `github.dev`.
3. In the left Explorer panel, **click `main.tex`** and edit.

### Option C (for experienced users)
If you normally work locally with `git pull` / `git push`, you can use your standard workflow.

---

## 2) In `github.dev`, install a LaTeX extension (helpful)

In online VS Code:
1. Open the **Extensions** panel (left sidebar, square icon).
2. Search for **LaTeX Workshop**.
3. Click **Install**.

Why this helps:
- better TeX syntax highlighting,
- command/intellisense support,
- easier navigation in larger `.tex` files.

(Preview/build features may be limited in browser VS Code, but editing support is still very useful.)

---

## 3) Commit and push your changes (important)

After editing, your changes must be committed so editors can see them and PDF recompilation can start.

### On GitHub web editor
1. Click **Commit changes…** (top-right).
2. Write a short commit message (e.g., `Fix typo in section 2`).
3. Choose **Commit directly to the main branch** (unless instructed otherwise).
4. Click **Commit changes**.

### In `github.dev`
1. Open the **Source Control** panel (branch icon on the left).
2. Review changed files.
3. Enter a commit message in the message box.
4. Click **Commit**.
5. Click **Sync Changes** / **Push** (if prompted, confirm).

---

## 4) Use Issues for requested corrections

- Open the **Issues** tab to see what needs to be fixed.
- Each Issue describes a requested correction from editors.
- You can discuss details in the Issue comments (ask questions, clarify wording, etc.).
- Most importantly: **apply the correction in `main.tex`, then commit and push** as described above.
- Repeat until all assigned/open issues are resolved.

---

## 5) Find the compiled PDF in GitHub Actions

Each push triggers automatic compilation of the PDF.

To download it:
1. Open the **Actions** tab.
2. Click the **most recent workflow run**.
3. Scroll to **Artifacts**.
4. Download **`compiled-pdf`** (ZIP file).

Notes:
- Compilation is not immediate; it usually takes about **6 minutes**.
- If you don’t see the artifact yet, wait a bit and refresh the run page.

---

If anything is unclear, ask in the relevant Issue and tag the editors.
