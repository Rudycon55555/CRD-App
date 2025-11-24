# HOWtoUSE — CRD App

This guide explains how to use the **CRD App** for creating, editing, and exporting Cooking Recipe Data (CRD) recipes.  
The app is a single‑page HTML application with three main tabs: **Editor**, **Cardify**, and **Docs**.

---

## 🔑 Quick Start

1. Download or clone the repository.
2. Open [CRD-App](https://rudycon55555.github.io/CRD-App/) in your browser (Chrome, Firefox, Edge, Brave).
3. Use the tabs at the top to switch between:
   - **CRD Text Editor**
   - **Create Card**
   - **Docs**

---

## 🖊️ CRD Text Editor

The **Editor** tab is where you create or edit CRD XML files.

- Enter a **file name** (without extension).
- Click **Load CRD skeleton** to insert a full XML template.
- Edit the recipe details directly in the CodeMirror editor:
  - Metadata (id, name, author, cuisine, difficulty, etc.)
  - Ingredients (amount, unit, item, preparation, allergen, origin, etc.)
  - Steps (instruction, time, temperature, sensory cues, safety warnings)
  - Serving facts, nutrition, timing, storage, ratings, history, notes
- When finished, click **Download .crd.xml** to save your recipe file.

---

## 📄 Cardify (PDF Generator)

The **Cardify** tab lets you import CRD files and generate printable recipe cards.

- Click **Import CRD file** and select a `.crd.xml`, `.xml`, or `.crd` file.
- The app will preview the raw XML content.
- Click **Cardify** to parse the file into structured JSON.
- Review the parsed recipe in the preview panel.
- Enter a **PDF file name** (optional; defaults to recipe name).
- Click **Download .crd.pdf** to export a formatted recipe card.

---

## 📚 Docs

The **Docs** tab provides reference material:

- **What is CRD?** — Overview of the Cooking Recipe Data format.
- **Authoring guidelines** — Best practices for writing CRD XML:
  - Metadata, ingredients, steps, serving facts, nutrition, timing, storage, history, notes
- **CRD XML skeleton** — A full template you can copy into the editor.
- **Minimal example** — A simple working recipe (Grandma’s Apple Pie).

---

## 🧩 Dependencies

The app uses CDN‑hosted libraries (no installation required):

- [CodeMirror](https://codemirror.net/) — Rich XML editor
- [jsPDF](https://github.com/parallax/jsPDF) — PDF generation

---

## 🥧 Example Workflow

1. Open the **Editor** tab.
2. Load the skeleton and fill in recipe details (e.g., Grandma’s Apple Pie).
3. Download the recipe as `apple-pie.crd.xml`.
4. Switch to the **Cardify** tab.
5. Import `apple-pie.crd.xml`.
6. Click **Cardify** to preview structured data.
7. Download the recipe card as `apple-pie.crd.pdf`.

---

## 📜 Notes

- All functionality runs in the browser — no backend required.
- Recipes can include licensing and provenance metadata.
- CRD is designed to be both **machine‑readable** and **human‑friendly**.

---

## 🙌 Credits

CRD App combines:
- **Editor** — XML authoring
- **Cardify** — PDF recipe cards
- **Docs** — Guidelines and examples
