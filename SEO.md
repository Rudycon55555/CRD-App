# SEO.md — Optimizing CRD App for Search and Social Reach

This guide explains how to make the **CRD App** discoverable by search engines and attractive when shared on social media.

---

## 📖 Why SEO Matters

- **Search engines** need clear metadata to index your site properly.
- **Social platforms** (Twitter, Facebook, LinkedIn, etc.) use Open Graph and Twitter Card tags to generate previews.
- **Users** benefit from descriptive titles and summaries that make your app stand out.

---

## 🧩 Essential `<meta>` Tags

Add these tags inside the `<head>` of your `index.html`:

```html
<!-- Basic SEO -->
<title>CRD App — Cooking Recipe Data Editor, Cardify, Docs</title>
<meta name="description" content="CRD App is an all-in-one Cooking Recipe Data tool. Create, edit, and export recipes in structured XML and printable PDF cards. No backend required.">
<meta name="keywords" content="Cooking Recipe Data, CRD, recipe XML, recipe PDF, structured recipes, food metadata, nutrition tracking">

<!-- Open Graph (Facebook, LinkedIn, etc.) -->
<meta property="og:title" content="CRD App — Cooking Recipe Data Editor, Cardify, Docs">
<meta property="og:description" content="Create, edit, and export recipes in structured XML and printable PDF cards.">
<meta property="og:type" content="website">
<meta property="og:url" content="https://rudycon55555.github.io/CRD-App/">

<!-- Twitter Card -->
<meta name="twitter:card" content="summary">
<meta name="twitter:title" content="CRD App — Cooking Recipe Data Editor, Cardify, Docs">
<meta name="twitter:description" content="Create, edit, and export recipes in structured XML and printable PDF cards.">
