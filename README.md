🎓 Certificate Studio

A powerful, zero-dependency, single-file online certificate generator.

Certificate Studio is a client-side web application designed to create high-quality, printable certificates and exam result sheets instantly. It is built as a single HTML file, making it incredibly easy to deploy, share, and use without any server setup or installation.

It specifically caters to educational institutions, Madrassas, and corporate training programs, offering specialized templates for Quranic studies, Tajweed, Language courses, and Exam reporting.

✨ Key Features

🎨 Design & Customization

16 Professional Templates: Choose from a wide range of styles including Imperial Gold, Corporate Blue, Art Deco, Vintage Parchment, and the exclusive SVG-based Luxury Gold design.

Slide Navigation: Easily cycle through designs using intuitive Left/Right slide buttons.

Deep Styling: Customize border colors, background tints, and fonts to match your organization's branding.

Logo Support: Upload your organization's logo (PNG/JPG), resize it, and position it anywhere on the canvas.

📜 Specialized Templates

The tool comes pre-loaded with 7 smart templates tailored for specific use cases:

Quran Certificate: Includes dropdowns for:

Full Hifz Completion

15 Juz (Half) Completion

Noorani Qaida: For fundamental Quranic education.

Tajweed: Certifying proficiency in recitation rules.

Arabic Language: For language course completion.

Madrassa Leaving: Official school transfer/graduation certificates.

Appreciation: General purpose recognition.

Exam Marks Sheet: A specialized template with a dynamic results table.

🛠️ Advanced Editor

Drag & Drop: Freely move any text element on the canvas.

Smart Sidebar:

Text Editor: Edit text content on the left, see changes live.

Style Controls: Adjust font family (10+ Google Fonts), size, weight, and color.

Dynamic Tables: The Marks Sheet features a smart grid system:

Auto-Layout: Columns resize automatically to fit the page width.

Keyboard Support: Press Tab in the last cell to instantly add a new row.

Add/Remove Controls: Dedicated buttons to manage rows and columns via the sidebar.

🚀 Getting Started

Since Certificate Studio is a Single File Application (SFA), there is no build process, no npm install, and no database required.

📥 Installation

Clone the repository:

git clone [https://github.com/your-username/certificate-studio.git](https://github.com/your-username/certificate-studio.git)


Or Download: Simply download the index.html (or certificate_generator.html) file.

▶️ Usage

Open the file: Double-click the HTML file to open it in any modern web browser (Chrome, Edge, Firefox, Safari).

Select Template: Use the top navigation bar to select the type of certificate you need. Hover over "Quran Certificate" to see specific sub-options.

Select Design: Click the arrows on the left/right of the canvas to choose a visual style.

Edit Details:

Click on any text in the certificate to select it.

Use the sidebar on the left to change the text, font, or color.

Drag the text on the canvas to adjust positioning.

Customize: Go to the "Design & Borders" tab in the sidebar to upload your logo or change theme colors.

Download: Click the Download button in the top-right corner to save the high-resolution PNG file.

💻 Technical Details

This project is built with simplicity and portability in mind.

HTML5 Canvas: Used for all graphics rendering, ensuring high-performance drawing of complex borders, gradients, and text.

Tailwind CSS (CDN): Used for the UI layout (Sidebar, Navbar, Buttons). It is loaded via CDN, so an internet connection is required for the UI styling (the certificate generation logic works offline if fonts are cached).

Vanilla JavaScript: Zero external JS frameworks. All logic for drag-and-drop, state management, and canvas drawing is contained within the single file.

Lucide Icons: Used for the clean, modern interface icons.

🤝 Contributing

Contributions are welcome! If you have ideas for new border designs or features:

Fork the repository.

Create your feature branch (git checkout -b feature/AmazingFeature).

Commit your changes (git commit -m 'Add some AmazingFeature').

Push to the branch (git push origin feature/AmazingFeature).

Open a Pull Request.

📄 License

Distributed under the MIT License. See LICENSE for more information.

<p align="center">
Made with ❤️ for Educators and Developers
</p>