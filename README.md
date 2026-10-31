# LogicMinds | Premium Web Templates Vault 🚀

An ultra-sleek, high-performance, and fully installable Progressive Web App (PWA) storefront template vault built for **LogicMinds**. This platform distributes engineered website layouts, blog frameworks, landing pages, and funnel blueprints while automatically capturing user leads directly into a real-time cloud database.

---

## 🎨 Design Token Specifications
The platform enforces a strict, premium 3-color architectural theme engineered for prolonged human focus and high click attribution:
*   **Primary Background:** Pitch Black (`#000000`)
*   **Branding & Highlights:** Vibrant Tangerine (`#FF6600`)
*   **Typography & Copy:** Readability Ash Gray (`#B3B3B3`)

---

## ⚡ Core Operational Features
*   **Full PWA Installability:** Includes a dynamic native app installation interceptor linked to `manifest.json` and `sw.js`. Runs as a standalone app on iOS, Android, and Desktop, stripping away browser search boxes.
*   **Interactive Digital Hero Grid:** A self-contained canvas vector graphic engine that calculates layout nodes and animates trace wires fluidly in the background.
*   **On-The-Fly Blueprint Compilation:** Eliminates server bloat or `.zip` storage dependencies. Generates fully functioning single-file HTML layout structures directly within the browser client memory utilizing sandboxed Data URIs.
*   **Automated Lead Acquisition Tunnel:** Prompts an elegant pitch-black and tangerine lead validation modal to capture names, emails, and phone nodes securely before initiating document transfers.
*   **Real-Time Google Sheets Database:** Fully integrated with a secure, zero-cost Google Apps Script Webhook pipeline to stream visitor parameters instantly into private spreadsheets.
*   **Notebook Format Utility Modals:** Interactive footer navigational trays (About Us, Contact Us, FAQ) configured as stylized scrollable notebook panels with left-side tangerine bounding lines.

---

## 📂 Repository File Scaffolding
```text
├── index.html        # Core platform layout, embedded templates, animation, and logic controllers
├── manifest.json     # PWA app signature configs, icons, theme tokens, and launch rules
├── sw.js             # Background service worker caching app structures for full offline access
└── README.md         # Documentation schema (This file)
```

---

## 🚀 Deployment & Installation Blueprint

### 1. Connecting Your Personal Database (Google Sheet)
To maintain the real-time submission tracking engine:
1. Create a Google Sheet containing column headers: `Timestamp | Name | Email | Phone | Template`.
2. Open **Extensions** → **Apps Script**, wipe the default code, paste the server tracker engine, and select **Deploy as Web App**.
3. Ensure you set access rules to: *Execute as: Me* and *Who has access: Anyone*.
4. Copy the generated Web App URL, open `index.html` in a code editor, locate the `processLeadDownload(event)` function, and replace the `GOOGLE_WEBHOOK_URL` string placeholder:
   ```javascript
   const GOOGLE_WEBHOOK_URL = "https://google.com";
   ```

### 2. Publishing via GitHub Pages
Because PWAs require an encrypted `https://` connection layer to initialize service workers, hosting this repository on GitHub Pages is highly recommended:
1. Push `index.html`, `manifest.json`, and `sw.js` directly up to your GitHub repository.
2. Navigate to your repository **Settings** → **Pages** section tab.
3. Under the **Build and deployment** area, change the source branch field to `main` (or `/root`) and click **Save**.
4. GitHub will instantly publish your operational workspace live on a secure production domain!

---

## 💻 Custom Customization Rules
To alter the structural layouts your customers download from your vault cards, locate **Part 3** of the JavaScript tags inside `index.html` and modify the pure HTML strings wrapped inside the backtick configurations (`const websiteTemplate`, `const blogTemplate`, etc.).

---

## 🛡️ License & Attrib
Designed, coded, and engineered by **the FOUNDER** for the LogicMinds Ecosystem. All baseline wireframe layout blue prints are free for open distribution and deployment loops.
