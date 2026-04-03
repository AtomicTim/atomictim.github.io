# 🏛️ ClearGov – Plain English Helper
### A Chrome Extension that explains government forms in plain English using AI

---

## ⚡ Getting Started

1. Install ClearGov from the Chrome Web Store
2. Go to any `.gov` or `.edu` website
3. Click the ClearGov icon in your Chrome toolbar to open the panel
4. Create a free account or sign in with Google
5. Click any form field to get an instant plain-English explanation

---

## ✨ Features

- **Plain English explanations** — every form field explained at a reading level anyone can understand
- **Key term definitions** — click any highlighted term for an instant definition
- **What to have ready** — specific documents to grab before you start filling out the field
- **Common mistake warnings** — the most frequent error for each field and how to avoid it
- **Agreement summaries** — plain-English bullet points of what you're agreeing to before you click Accept
- **Smart examples** — real calculations for financial fields like net worth, AGI, and assets
- **Explore all options** — see every dropdown choice explained before you pick one
- **Works on dropdowns, radio buttons, checkboxes, and text fields**

---

## 💰 Pricing

- **Free** — 20 explanations per month
- **ClearGov Pro** — $7/month for unlimited explanations

---

## 🌐 Supported Sites

- FAFSA (studentaid.gov)
- US Visa Applications / DS-160 (ceac.state.gov)
- Social Security Administration (ssa.gov)
- VA.gov — veterans benefits and GI Bill
- USCIS forms — I-90, N-400, and more (uscis.gov)
- HealthCare.gov — ACA marketplace enrollment
- IRS forms and tax filing (irs.gov)
- Any `.gov` or `.edu` website

---

## 🔒 Privacy

- ClearGov reads form field **labels and page context only** — never what you type
- Your SSN, passwords, and personal answers are never read or transmitted
- Field context is sent to our secure backend to generate explanations
- See our full privacy policy at [atomictim.github.io/privacy-policy.html](https://atomictim.github.io/privacy-policy.html)

---

## 📁 File Structure

```
cleargov-extension/
├── manifest.json    ← Extension configuration
├── background.js    ← Background logic (opens the side panel)
├── content.js       ← Runs on .gov pages, detects form fields
├── sidebar.html     ← The visual panel
├── sidebar.js       ← App logic, auth, and API calls
└── README.md        ← This file
```

---

## 🚀 Coming Soon

- 🇪🇸 Spanish language support
- 📄 Document checklist exports
- 👥 Family/household plans
- 🏢 Enterprise plans for organizations
