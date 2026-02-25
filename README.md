Compare PDF

A high-fidelity, browser-based tool for visually comparing two PDF documents. This application performs a pixel-by-pixel analysis to highlight differences in layout, text, and imagery, making it ideal for legal, design, and engineering document audits.

🚀 Key Features

Pixel-Perfect Comparison: Detects even the slightest movements in text, margins, or image placement.

Visual Highlighting: Differences are highlighted in a distinct red overlay on top of the original document.

Flexible Comparison Modes:

Sequential Mode: Automatically pairs pages (Page 1 vs Page 1, etc.).

Manual Mode: Compare any page from Document A with any page from Document B.

Local Processing: Your files never leave your browser. All rendering and pixel math are performed client-side for maximum privacy.

PDF Export: Download the comparison results as a new PDF with differences highlighted.

🛠️ Technology Stack

HTML5/Tailwind CSS: For a clean, responsive user interface.

PDF.js: Mozilla's library for high-fidelity PDF rendering to canvas.

jsPDF: For generating the final comparison report.

Vanilla JavaScript: Lightweight and fast pixel manipulation logic.

📖 How to Use

Upload: Select or drag-and-drop your "Original" and "Modified" PDFs into the designated zones.

Compare: Click "Load & Start".

Inspect:

Scroll through the side-by-side view.

Use the Manual Mode toggle if you need to compare specific pages out of order (e.g., comparing Page 3 of a new draft to Page 5 of an old one).

Export: Use the "Download Result" button to save a copy of the visual differences.

🔒 Privacy

This tool is designed with security in mind. It uses the FileReader API and Canvas API to process documents entirely on your machine. No server-side storage or processing is involved.



