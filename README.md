# Priyam Pandey — Academic & Research Personal Website

Clean, minimal, high-impact personal research website engineered for academic outreach, faculty review, and portfolio demonstration.

## 🚀 Instant Local Preview (Zero Build Required)

Double-click `index.html` or run any local HTTP server:

```bash
# Python 3
python3 -m http.server 8000

# Or using Node / npx
npx serve .
```
Then visit `http://localhost:8000` in your web browser.

---

## 🌐 Deploy to GitHub Pages (`priyam-pandey-r.github.io`)

### Step 1: Create or Use Your GitHub Repository
1. On GitHub, create a repository named: `priyam-pandey-r.github.io` (or use your preferred repository name).
2. Push the contents of this folder (`website/`) to the repository:

```bash
cd "/Users/priyam/Obsidian Vault/AI_ml_resarch_brain/MY ZONE/website"
git init
git add .
git commit -m "feat: initial academic research website release"
git branch -M main
git remote add origin https://github.com/priyam-pandey-r/priyam-pandey-r.github.io.git
git push -u origin main
```

### Step 2: Enable GitHub Pages
1. Go to your GitHub repository **Settings** &rarr; **Pages**.
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Branch: `main` / folder: `/(root)`.
4. Click **Save**. Within 60 seconds, your website will be live at:
   **`https://priyam-pandey-r.github.io`**

---

## 🗂️ Site Architecture & Routes

| Route | File | Focus |
| :--- | :--- | :--- |
| `/` | `index.html` | 60-second researcher identity, research axis, featured projects |
| `/research` | `research.html` | Deep dives into ProteinFM, Neuronal Morphology, and Thermal Pose |
| `/publications` | `publications.html` | Published articles, manuscripts under review, working papers |
| `/projects` | `projects.html` | Software repositories, geometric pipelines, and benchmarks |
| `/about` | `about.html` | Education at IISER TVM, research philosophy, future exploration |
| `/cv` | `cv.html` | Academic CV summary and 1-click PDF download (`cv.pdf`) |
| `/contact` | `contact.html` | Direct email, Google Scholar, GitHub, LinkedIn, and lab coordinates |

---

## 📄 Updating Your CV PDF
To update your CV on the website, simply save your exported PDF as `cv.pdf` inside this folder. Both the download button and embedded viewer will automatically reflect the latest version!
