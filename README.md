# VTM5 Thin-blood (Duskborn) Character Generator

A browser-based web app for creating **Vampire: The Masquerade 5th Edition** Thin-blood (aka Duskborn) characters. It supports point-buy attributes/skills, **V5 dice rolling with Hunger**, Thin-blood-specific **Merits & Flaws**, and **exporting a fillable PDF** character sheet—right from your browser.

---

## Features

* **Thin-blood/Duskborn focus**

  * Identity block (Ambition, Desire, Touchstones, etc.)
  * Thin-blood Merits & Flaws selectors
  * Thin-Blood Alchemy notes area
* **Attribute & Skill assignment**

  * Point-buy budgets with **Primary/Secondary/Tertiary** presets
  * One-click **Auto-assign** (balanced or physical/social/mental leaning)
  * Manual dot editing (1–5 for attributes; 0–5 for skills)
* **Dice roller (V5 rules)**

  * Handles successes (6–9), 10s as crits, **Messy Critical** (Hunger 10s), and **Bestial Failure** (Hunger 1 + no successes)
* **Export to fillable PDF**

  * Generates a clean, one-page **PDF with form fields** you can edit later
  * Includes attributes, skills table, merits, flaws, alchemy, and notes
* **Save / Load**

  * Export character to **JSON**; re-import later to continue editing
* **One file** (`index.html`)

  * Uses CDN scripts (`jsPDF`, `jsPDF-Autotable`, `jspdf-forms`)—no build tooling required
* **Responsive & aesthetically clean UI**

---

## How to Use

1. **Identity**
   Fill in character basics (Name, Archetype, Ambition, Desire, etc.).

2. **Merits & Flaws**
   Select any Thin-blood-specific Merits/Flaws that match your concept.

3. **Attributes**

   * Adjust **Primary/Secondary/Tertiary** budgets under **Settings**.
   * Click **Auto-assign** to distribute dots, then tweak manually.
   * Attributes are 1–5 (min 1).

4. **Skills**

   * Set budgets under **Settings**.
   * Click **Auto-assign** (uses a light heuristic based on archetype), then tweak manually.
   * Skills are 0–5.

5. **Thin-blood Info**
   Set **Hunger** (0–5), and optionally **Health/Willpower** (derived at your table). Add **Alchemy** notes and other advantages/banes.

6. **Dice Roller**

   * Enter **Dice Pool** and **Hunger**.
   * Click **Roll** to see results, success count, crit pairs, **Messy**, or **Bestial** flags.

7. **Save/Load**

   * **Save JSON** to download your current character as a `.json` file.
   * **Load JSON** to resume editing.

8. **Download Fillable PDF**

   * Click **Download Fillable PDF** to generate a one-page form-fillable sheet.
   * Open and edit in any PDF reader that supports form fields.

---

## Configuration

Open **Settings** in the app:

* **Attribute Budgets:** Primary / Secondary / Tertiary (default 6/4/3)
* **Skill Budgets:** Primary / Secondary / Tertiary (default 11/7/4)
* **Auto-assign Lean:** balanced, physical, social, or mental

> These budgets are configurable to match your Storyteller’s creation method. Manual edits are always allowed.

---

## Contributing

PRs and issues are welcome! If you add new options or presets, please:

* Keep the **single-file** ethos (or clearly propose a split).
* Avoid quoting proprietary text verbatim.
* Add brief UI labels and inline comments.

---

## Legal / Attribution

* **Vampire: The Masquerade**, **World of Darkness**, and related terms are trademarks of their respective owners.
* This tool is a **fan-made, non-commercial** character helper. It does **not** include rules text or proprietary excerpts; it assumes you own and use the official books at your table.
* Please support the creators by purchasing the official rulebooks.

---

## License

* **MIT** (permissive; good for open-source contributions)
---

## Acknowledgments

* Community resources and official books used at the table for reference and validation.
* jsPDF, jsPDF-AutoTable, and jspdf-forms authors for great client-side PDF tooling.



