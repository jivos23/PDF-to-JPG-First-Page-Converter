# PDF-to-JPG-First-Page-Converter
First Page PDF to JPG Converter converts the first page of each PDF to a high-quality JPG thumbnail image.

This is a simple web-based tool that converts the first page of one or more PDF files into high-quality JPG thumbnail images. It works directly in the browser without any server-side processing. The application allows users to upload or drag-and-drop multiple PDF files, preview the generated images, and download them either individually or in bulk. If the browser supports it, users can also save images directly to a selected local folder.

Features:

- Upload multiple PDF files at once
- Supports drag and drop
- Converts only the first page of each PDF
- Automatically resizes output image to 320 pixels in height
- Produces high-quality JPG output with smoothing
- Displays preview thumbnails for all files
- Allows individual or bulk download of JPG images
- Option to save selected images to a user-selected folder (in supported browsers)
- Built with PDF.js (Mozilla) for fast and accurate rendering

How to Use:

- Open the HTML file in a modern browser (such as Chrome or Edge).
- Upload your PDF files by clicking the file input or dragging them into the drop area.
- The first page of each PDF will be rendered and converted into a JPG thumbnail.
- Thumbnails and filenames will appear in a table.
- Use the checkboxes to select one or more files.
- Click "Download" to save them to your default download location.

Alternatively, click "Save to Folder" to choose a destination folder (only in Chrome-based browsers).
You can also download any image individually by clicking the "Save JPG" button next to it.

Browser Compatibility:

- Fully supported: Chrome, Edge
- Partially supported (without folder saving): Firefox, Safari

Note: The "Save to Folder" option requires support for the File System Access API, available only in Chromium-based browsers

Limitations:

- Only the first page of each PDF is processed
- All processing is client-side; no files are uploaded or stored externally
- Performance may vary depending on file size and system resources

Privacy Note:
This tool works completely offline in your browser. No files are sent to any server. Your data remains on your device.

Technology Used:

- HTML, CSS, JavaScript
- PDF.js (open-source PDF rendering library)

File Structure:

- index.html – contains all HTML, JavaScript, and styling in a single file
- No dependencies except PDF.js via CDN

License:
This project is provided freely and can be modified or used without restrictions: MIT License.
