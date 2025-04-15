# Offline ID Card Generator 🪪

A simple, serverless ID card generator built entirely within a single HTML file. Create, manage, preview, and print ID cards directly in your browser, completely offline. Ideal for small organizations, events, or temporary needs where a quick, local solution is required.

## ✨ Key Features

* **Single File Operation:** Runs entirely from one `.html` file. No installation or internet connection needed after loading.
* **Offline First:** Designed for complete offline use.
* **Person Entry:** Add individuals with details like:
    * Full Name
    * Role/Position
    * Department (Optional)
    * ID Number (Manual or Auto-Generated)
    * Photo Upload (Local file, stored temporarily in the browser)
    * QR Code Text (Optional, displays text on the card)
* **Customizable Design:**
    * Upload your organization's logo.
    * Set organization name, address, and footer text.
    * Adjust ID card size: Badge, Card (Credit Card), or Custom Dimensions (px).
* **Live Preview:** See changes to the ID card design instantly as you edit details or settings.
* **Batch View & Print:**
    * View all generated ID cards in a grid layout.
    * Print multiple cards per page (formatted for A4).
    * Use browser's `Print` function to print physical cards or save as PDF.
* **Data Management:**
    * Save all entries to a `.json` file for backup or transfer.
    * Load entries from a previously saved `.json` file.
    * Clear all data from the current session.
* **Responsive UI:** Clean interface usable on desktops and tablets.

## 🚀 How to Use

1.  **Download:** Get the `id_card_generator.html` file (or whatever you name it).
2.  **Open:** Double-click the file to open it in your preferred modern web browser (like Chrome, Firefox, Edge, Safari).
3.  **Configure (Optional):** Go to the **Settings** tab to upload your logo and set organization details. Click **Save Settings**.
4.  **Add People:** Use the **Person Entry & Preview** tab to add individuals and see a live preview. Click **Add Person**.
5.  **View & Print:** Switch to the **Batch View & Print** tab to see all cards. Click **Print / Save as PDF** and use your browser's print dialog.
6.  **Save/Load Data:** Use the **Data Management** tab to export your entries to a JSON file or import them later.

## 💻 Technology Stack

* **HTML:** Structure and content.
* **CSS (Tailwind CSS):** Styling and layout. *Note: Uses the Tailwind CDN by default.*
* **JavaScript (Vanilla):** Application logic, DOM manipulation, data handling (localStorage for settings, in-memory for entries).

## 🔌 Offline Usage Note

This application uses Tailwind CSS loaded from a CDN (`https://cdn.tailwindcss.com`) for styling convenience. For **true, guaranteed offline use from the source file**, you have two options:

1.  **Save the Rendered Page:** Once the page is loaded in your browser, use `File > Save Page As...` (or similar) and choose "Webpage, Complete". This saved version will include the necessary CSS and work fully offline.
2.  **Download Tailwind CSS:** Download the standalone Tailwind CSS file and replace the `<script src="https://cdn.tailwindcss.com"></script>` line with a `<link rel="stylesheet" href="path/to/your/local/tailwind.css">`.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check [issues page](link-to-issues) (if you create one).

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.md](link-to-license) file for details (if you add one).
