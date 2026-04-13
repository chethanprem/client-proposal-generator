# 📄 Client Proposal Generator

A professional, no-backend client proposal builder for freelancers and small businesses. Create stunning proposals, export to PDF, and share via link — all from a single HTML file.

---

## 🌐 Live Demo

**[chethanprem.github.io/client-proposal-generator](https://chethanprem.github.io/client-proposal-generator)**

---

## ✨ Features

### 🗂 Proposal Dashboard
- View all saved proposals at a glance
- See client name, proposal number, total amount, and status
- Edit, duplicate, preview, or delete any proposal

### ✍️ Proposal Builder
Full section-by-section builder with toggle on/off for each section:

| Section | What it includes |
|---|---|
| Cover Page | Title, tagline, client name, date, valid until |
| About Us | Company introduction |
| Services Offered | Icon + title + description per service |
| Why Choose Us | 2-column highlight grid |
| Scope of Work | Numbered deliverables with details |
| Project Timeline | Phase → milestone → duration |
| Pricing | Qty × Rate auto-calculation with grand total |
| Terms & Conditions | Multi-line terms, pre-fills from company profile |
| Signature Block | Auto-populated from company profile |
| Custom Sections | Add unlimited custom sections |

### 👁 Live Preview
- Full rendered proposal before export
- Corporate design with Deep Burgundy & Champagne Gold theme

### 📤 Export Options
- **PDF Download** — A4 portrait, print-ready with full styling
- **Copy Shareable Link** — encodes entire proposal into a URL to share with clients

### ⚙️ Company Profile
- Set your company name, contact, email, phone, GST, address, and default terms once
- Auto-fills on every new proposal

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| UI | HTML5, CSS3 (CSS Variables) |
| Logic | Vanilla JavaScript (ES6+) |
| Storage | `localStorage` — persists on refresh |
| PDF Export | [jsPDF](https://github.com/parallax/jsPDF) |
| Fonts | Playfair Display + Source Sans 3 + Source Serif 4 |

---

## 🚀 Getting Started

No install needed.

1. Download `index.html`
2. Open in any modern browser
3. Go to **Company Profile** → fill in your details
4. Click **New Proposal** and start building

---

## 📁 Project Structure

```
client-proposal-generator/
└── index.html    # Everything in one file — UI, logic, styles
```

---

## 💼 Perfect For

- Freelance developers, designers & consultants
- Digital marketing agencies
- IT service providers
- Any business sending client proposals regularly

---

## 📌 Notes

- All data stored in browser `localStorage` — nothing sent to any server
- Shareable link encodes the full proposal into the URL (works best for short proposals)
- Clearing browser data will reset saved proposals

---

## 👨‍💻 Built By

**Chethan Prem** — [github.com/chethanprem](https://github.com/chethanprem)

Part of a series of free, no-backend business tools built for freelancers and small businesses.

---

## 📄 License

MIT — free to use, modify, and share.
