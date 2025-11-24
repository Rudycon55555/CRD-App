
Everything is contained in one HTML file with embedded CSS and JavaScript.

---

## 🚀 Getting Started

1. Clone or download this repository.
2. Open `[CRD-App](https://rudycon55555.github.io/CRD-App/)` in any modern browser (Chrome, Firefox, Edge, Brave).
3. Use the tabs at the top to switch between:
   - **CRD Text Editor**
   - **Create Card**
   - **Docs**

---

## 🖊️ Usage

### Editor
- Enter a recipe file name.
- Click **Load CRD skeleton** to start with a template.
- Edit recipe details in the CodeMirror editor.
- Click **Download .crd.xml** to save your recipe.

### Cardify
- Import an existing `.crd.xml`, `.xml`, or `.crd` file.
- Click **Cardify** to parse and preview recipe data.
- Click **Download .crd.pdf** to export a printable recipe card.

### Docs
- Read about CRD format and authoring guidelines.
- Copy the XML skeleton or minimal example to start writing recipes.

---

## 🧩 Dependencies

The app uses CDN‑hosted libraries:
- [CodeMirror](https://codemirror.net/) — XML editor
- [jsPDF](https://github.com/parallax/jsPDF) — PDF generation

No installation required.

---

## 📖 CRD XML Skeleton

A full skeleton is provided in the app. Example excerpt:

```xml
<recipe>
  <metadata>
    <id>[unique recipe identifier]</id>
    <name>[recipe name]</name>
    <author>
      <name>[author name]</name>
      <profile-url>[author profile link]</profile-url>
      <contributor-role>[chef/home cook/blogger]</contributor-role>
      <location>[author location]</location>
    </author>
    <difficulty>[easy/medium/hard]</difficulty>
    <culture>[origin or inspiration]</culture>
    <cuisine-type>[Italian/Fusion/Vegan/etc]</cuisine-type>
    <tags>
      <tag>[keyword]</tag>
    </tags>
    <version>[recipe version number]</version>
    <last-updated>[ISO date]</last-updated>
    <license>[CC-BY/All Rights Reserved/etc]</license>
    <provenance>[blockchain hash or source reference]</provenance>
  </metadata>
  <!-- ingredients, equipment, steps, serving-facts, nutrition, timing, storage, ratings, history, notes, etc -->
</recipe>
