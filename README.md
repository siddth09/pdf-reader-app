# 📖 PDF Page Reader with Text-to-Speech

A single-file, browser-based web application that lets you upload, view, and listen to PDF pages through your browser's built-in text-to-speech (TTS) capabilities.

---

## 🚀 Features

* **PDF Upload:** Load any PDF file from your local computer.
* **PDF Viewing:** Renders PDF pages in high-quality using a canvas element.
* **Page Navigation:** Simple "Previous" and "Next" buttons to move through the document.
* **Text-to-Speech:** Click “Read This Page” to extract and read aloud the current page.
* **Stop & Resume:** Pause reading anytime and resume from where you left off.
* **Female Voice Selection:** Automatically picks a high-quality English female voice (if available).
* **Fully Client-Side:** Runs entirely in your browser — no server uploads, ensuring privacy.
* **Responsive Design:** Built with Tailwind CSS for seamless use on desktop and mobile devices.

---

## 💡 How to Use

1. **Open the Application:**
   Open `pdf-reader.html` in any modern browser (Chrome, Firefox, Edge, etc.).

2. **Upload PDF:**
   Click the “Upload PDF” button to select a PDF file from your device.

3. **View & Navigate:**
   The first page will appear. Use “Prev” and “Next” to navigate pages.

4. **Read Aloud:**
   Click “Read This Page” — the app extracts text and starts reading aloud.
   The button will disable, and “Stop Reading” becomes active.

5. **Stop Reading:**
   Click “Stop Reading” to pause the speech. “Read This Page” becomes available again.

6. **Resume Reading:**
   Clicking “Read This Page” again resumes from where you paused.
   Navigating to a new page starts fresh from that page.

---

## 🌐 How to Host (Deploy)

Since this is a single, self-contained HTML file, hosting is simple.

### 🔹 Local Use

* Just double-click `pdf-reader.html` to open it in your browser — no server needed.

### 🔹 GitHub Pages

1. Create a new **public repository** on GitHub.
2. Upload this file and rename it to `index.html` for convenience.
3. Go to **Settings → Pages**, and select your main branch as the source.
4. Your app will be live at:

   ```
   https://<your-username>.github.io/<your-repo-name>/
   ```

---

## 🛠️ Technologies Used

* **HTML5:** Page structure and layout.
* **Tailwind CSS:** Styling and responsiveness (via CDN).
* **JavaScript (ES6+):** Application logic and interactivity.
* **PDF.js:** Mozilla’s library for rendering PDFs in the browser (via CDN).
* **Web Speech API (SpeechSynthesis):** Browser-native text-to-speech functionality.

---

### 📜 License

This project is open-source and free to use for educational or personal projects.
