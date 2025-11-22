# Professional Resume Builder

A lightweight, privacy-focused, single-file resume builder that runs entirely in your browser. Create beautiful, ATS-friendly resumes and export them to PDF or DOCX without signing up or uploading your data to a server.

![Resume Builder Preview](https://via.placeholder.com/800x400?text=Resume+Builder+Preview)

## ✨ Features

* **Real-Time Preview:** See changes instantly as you type.
* **Privacy First:** All data is stored locally in your browser (`localStorage`). No servers, no tracking.
* **Export Options:** Download your resume as a high-quality **PDF** or editable **DOCX** (Word) file.
* **Save & Load:** Auto-saves your progress. Export your data to JSON for backup or transfer.
* **Drag-and-Drop:** Easily reorder resume sections and individual items (jobs, education, etc.).
* **Customizable:** Choose from modern fonts and accent colors to match your personal brand.
* **Smart Formatting:** Automatic bullet point handling and clickable links.
* **Single File:** The entire application is contained in one `index.html` file.

## 🚀 Quick Start

### Option 1: Use Online (GitHub Pages)

[**Click here to open the Resume Builder**](https://yourusername.github.io/your-repo-name/)
*(Replace this link after you enable GitHub Pages)*

### Option 2: Run Locally

1. Download the `index.html` file (or clone this repo).
2. Double-click `index.html` to open it in your web browser.
3. Start building!

## 🛠️ Deployment (GitHub Pages)

You can host this for free on GitHub Pages:

1. Fork or Clone this repository.
2. Go to your repository **Settings**.
3. Navigate to **Pages** (on the left sidebar).
4. Under **Build and deployment** > **Source**, select **Deploy from a branch**.
5. Select `main` (or `master`) branch and `/ (root)` folder.
6. Click **Save**.
7. Wait a minute, and your site will be live at `https://<username>.github.io/<repo-name>/`.

## 📝 Usage Guide

1. **Fill in your details:** Start with personal info, then add experience, education, etc.
2. **Reorder:** Use the `☰` handles to drag and drop sections or items to your preferred order.
3. **Customize:** Use the "Skills & Settings" section to change the accent color and font.
4. **Save:** Your work is auto-saved. Use the "Save" button in the header to download a JSON backup.
5. **Export:** Click "Download PDF" or "Download DOCX" when you are ready.

## 💻 Tech Stack

* **HTML5 / CSS3:** Modern layout using Flexbox and CSS Variables.
* **Vanilla JavaScript:** No heavy frameworks (React/Vue/Angular) required.
* **Libraries (via CDN):**
  * `html2pdf.js` - For PDF generation.
  * `docx.js` - For Word document generation.
  * `FileSaver.js` - For saving files.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

*Built with ❤️ for job seekers everywhere.*
