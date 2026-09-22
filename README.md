# ⏱️ PSP Copilot

**Focus on execution.**
A single-file web time management tool designed to supercharge your daily time management, effort tracking, and daily report generation.

(Based on the PSP (Personal Software Process) philosophy, it supports continuous improvement of your plans and actuals).

## ✨ Features

*   **Visual Timeline Management:** Arrange "Plan" and "Actual" side-by-side to visually grasp the gap between what you intended and what actually happened.
*   **Automatic Color Coding by Project:** Simply prefix task names like `[Project A]` to automatically group them by color. Plans are displayed in pastel tones, while actuals are vivid—making comparison intuitive.
*   **Intuitive Drag & Drop:** Move blocks by dragging their center, or resize their duration by pulling the top/bottom edges (snaps smoothly to 15-minute intervals).
*   **Fully Responsive (Mobile/Tablet Optimized):** Designed to work comfortably even on smartphones. Touch operations like dragging and resizing are fully supported.
*   **Smart Copy & Past Data Reuse:** Easily copy plans/actuals from yesterday, last week, or any specific date. The "Sync" button instantly copies today's plans directly to your actuals.
*   **Real-time Tracking:** Start and stop tasks with a single click. A ghost block shows the estimated duration while the task is running.
*   **Project & Task Aggregation:** Automatically sums up your daily actual hours by project. Also features an "All-Time Task Summary" to filter and search historical task hours across any date range.
*   **Auto-generate Markdown Daily Reports:** With a single click, generate and copy a structured daily report (Markdown) including project summaries, detailed task logs, Issues, Discoveries (W), and Next Actions (T).

## 🚀 How to Use

No backend server or installation required.
Just save the HTML file locally and double-click it.

1.  Download `psp_copilot.html`.
2.  Double-click the file to open it in your modern browser (Chrome, Edge, Safari, Firefox, etc.).
3.  **To sync across devices (Optional):** Save the file in a cloud storage folder (like Google Drive or Dropbox) to easily open and use it from your smartphone or tablet.

## 🔒 Security & Privacy

*   **Offline Operation:** All entered data is saved exclusively inside your browser's `localStorage`. No data is sent to external servers.
*   **Data Backup:** Use the "Export" button in the top right to download all your data as a JSON file. Use the "Import" button to restore or transfer your data to another browser/device.

## 🛠️ Technology Stack

*   **Framework:** Vue.js 3 (via CDN)
*   **Styling:** Tailwind CSS (via CDN)
*   **Icons:** Phosphor Icons
*   **Interactions:** interact.js (Drag & Drop / Resize)
*   **Data Storage:** Browser `localStorage` (JSON format)

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 💖 Support

If you find this project useful and would like to support its development, consider sponsoring me!

* [![GitHub Sponsors](https://img.shields.io/badge/Sponsor-%F0%9F%92%96-ea4aaa?style=flat-square&logo=githubsponsors&logoColor=white)](https://github.com/sponsors/yamagile)

Thank you for your support! 🙏