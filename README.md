<p align="center">
  <img src="assets/hero-banner.svg" alt="Code Anatomy — X-Ray Vision for Web Elements" width="100%" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Ready_to_Install-7DD3FC?style=for-the-badge&logoColor=black" alt="Ready to Install" />
  <img src="https://img.shields.io/badge/No_Build_Required-6EE7B7?style=for-the-badge&logoColor=black" alt="No Build Required" />
  <img src="https://img.shields.io/badge/Manifest_V3-A78BFA?style=for-the-badge&logoColor=black" alt="Manifest V3" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Manifest-V3-7DD3FC?style=flat-square&labelColor=111111" alt="Manifest V3" />
  <img src="https://img.shields.io/badge/AI-Gemini_Flash-6EE7B7?style=flat-square&labelColor=111111" alt="Gemini Flash" />
  <img src="https://img.shields.io/badge/TypeScript-100%25-F9A8D4?style=flat-square&labelColor=111111" alt="TypeScript" />
  <img src="https://img.shields.io/badge/License-MIT-7DD3FC?style=flat-square&labelColor=111111" alt="License" />
</p>

<br/>

> This repository contains **pre-built, ready-to-install** versions of [**Code Anatomy**](https://github.com/Mohammed-Awad-ENG/Code-Anatomy) — the browser extension that gives you X-ray vision for any web page. **No building, no Node.js, no terminal required.** Just download and load.
>
> 🔗 **Looking for the source code?** Visit the [main repository](https://github.com/Mohammed-Awad-ENG/Code-Anatomy).

<br/>

---

<br/>

## 📁 What's Inside

| Folder | Browsers | Manifest | Panel Type |
|--------|----------|----------|------------|
| `chrome/` | Chrome, Edge, Brave, Vivaldi, Opera, Arc | V3 | Side Panel API |
| `firefox/` | Firefox | V3 | Sidebar Action |

<br/>

---

<br/>

## 🚀 Installation

### Step 1: Download

Click the green **"Code"** button at the top of this page → **"Download ZIP"**, then unzip the file.

Or clone with git:

```bash
git clone https://github.com/Mohammed-Awad-ENG/Code-Anatomy-Builds.git
```

### Step 2: Load into Your Browser

Choose your browser below and follow the instructions:

<details>
<summary><strong>🟢 Google Chrome</strong></summary>

1. Open `chrome://extensions` in your address bar
2. Enable **Developer mode** (toggle in the top-right corner)
3. Click **"Load unpacked"**
4. Select the **`chrome/`** folder from this download
5. ✅ The Code Anatomy icon will appear in your toolbar!

</details>

<details>
<summary><strong>🔵 Microsoft Edge</strong></summary>

1. Open `edge://extensions` in your address bar
2. Enable **Developer mode** (toggle in the left sidebar)
3. Click **"Load unpacked"**
4. Select the **`chrome/`** folder from this download (Edge uses the same build as Chrome)
5. ✅ The Code Anatomy icon will appear in your toolbar!

</details>

<details>
<summary><strong>🟠 Brave</strong></summary>

1. Open `brave://extensions` in your address bar
2. Enable **Developer mode** (toggle in the top-right corner)
3. Click **"Load unpacked"**
4. Select the **`chrome/`** folder from this download
5. ✅ The Code Anatomy icon will appear in your toolbar!

> **Note:** If AI features don't work, click the Brave Shield icon on the Code Anatomy page and allow connections to `generativelanguage.googleapis.com`.

</details>

<details>
<summary><strong>🔴 Vivaldi</strong></summary>

1. Open `vivaldi://extensions` in your address bar
2. Enable **Developer mode** (toggle in the top-right corner)
3. Click **"Load unpacked"**
4. Select the **`chrome/`** folder from this download
5. ✅ The Code Anatomy icon will appear in your toolbar!

> **Tip:** You can pin Code Anatomy to Vivaldi's sidebar as a **Web Panel** for quick access.

</details>

<details>
<summary><strong>🔴 Opera / Opera GX</strong></summary>

1. Open `opera://extensions` in your address bar
2. Enable **Developer mode** (toggle in the top-right corner)
3. Click **"Load unpacked"**
4. Select the **`chrome/`** folder from this download
5. ✅ The Code Anatomy icon will appear in your toolbar!

</details>

<details>
<summary><strong>🟠 Firefox</strong></summary>

1. Open `about:debugging#/runtime/this-firefox` in your address bar
2. Click **"Load Temporary Add-on..."**
3. Navigate to the **`firefox/`** folder and select the **`manifest.json`** file
4. ✅ The Code Anatomy icon will appear in your toolbar!

> **⚠️ Important:** Firefox temporary add-ons are removed when Firefox closes. You will need to reload the extension each time you restart Firefox.

</details>

<details>
<summary><strong>⚪ Safari</strong></summary>

**Not supported.** Safari requires extensions to be converted with Xcode and distributed through the Mac App Store. We recommend using Chrome, Edge, Brave, or Firefox instead.

</details>

<br/>

---

<br/>

## 🔑 Setting Up AI Features (Optional)

The HTML, CSS, and JavaScript panels work **out of the box** — no setup needed. But for AI-powered explanations, you'll need a free API key:

<table>
<tr>
<td width="50">

**1**

</td>
<td>

Go to [**aistudio.google.com**](https://aistudio.google.com/) and sign in with your Google account

</td>
</tr>
<tr>
<td width="50">

**2**

</td>
<td>

Click **"Get API Key"** → **"Create API key"** → select any project

</td>
</tr>
<tr>
<td width="50">

**3**

</td>
<td>

Copy the key (looks like `AIzaSy...`)

</td>
</tr>
<tr>
<td width="50">

**4**

</td>
<td>

In Code Anatomy's side panel → **Settings** → paste the key → **Save**

</td>
</tr>
</table>

> **Free tier** — no credit card required. Your key stays local in your browser.

<br/>

---

<br/>

## 🛠 How to Use

1. **Activate** — Click the Code Anatomy toolbar icon, press `Alt + C`, or right-click any element → *"Inspect with Code Anatomy"*
2. **Select** — Hover over elements (they highlight in blue) and click one
3. **Explore** — The side panel opens with 4 tabs:

| Panel | What You Get |
|-------|-------------|
| **HTML** | Full outer HTML, syntax-highlighting, and full-component Export to Sandbox |
| **CSS** | Matched rules, inline styles, computed styles, pseudo-class forcing |
| **JavaScript** | Event listeners, DOM queries, manipulations, React props |
| **AI ✦** | One-click AI summary + follow-up chat about any element |

<br/>

---

<br/>

## 🔄 Which Folder for Which Browser?

| Your Browser | Use This Folder |
|-------------|----------------|
| Google Chrome | `chrome/` |
| Microsoft Edge | `chrome/` |
| Brave | `chrome/` |
| Vivaldi | `chrome/` |
| Opera / Opera GX | `chrome/` |
| Arc | `chrome/` |
| Firefox | `firefox/` |
| Safari | ❌ Not supported |

> **Rule of thumb:** If your browser is based on Chromium, use `chrome/`. If it's Firefox, use `firefox/`.

<br/>

---

<br/>

## 🔗 Links

- 📦 **Source Code:** [github.com/Mohammed-Awad-ENG/Code-Anatomy](https://github.com/Mohammed-Awad-ENG/Code-Anatomy)
- 🐛 **Report Issues:** [github.com/Mohammed-Awad-ENG/Code-Anatomy/issues](https://github.com/Mohammed-Awad-ENG/Code-Anatomy/issues)
- 🔑 **Get API Key:** [aistudio.google.com](https://aistudio.google.com/)

<br/>

---

<br/>

<p align="center">
  <sub>Built with 🩻 by <a href="https://github.com/Mohammed-Awad-ENG">Mohammed Awad</a></sub><br/>
  <sub>Code Anatomy — See what others can't.</sub>
</p>
