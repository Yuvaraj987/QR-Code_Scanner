# QR Code Scanner

A simple web-based QR Code scanner built using JavaScript, HTML, and CSS. This project allows users to scan QR codes directly from their browser using their device's camera.

## Features

- **Scan QR Codes**: Uses your device's camera to scan and decode QR codes in real time.
- **Instant Feedback**: Displays the scanned QR code content via an alert.
- **Responsive UI**: Clean and responsive user interface styled with CSS.

## Technologies Used

- **HTML5** and **CSS3** for structure and styling
- **JavaScript** for logic and scanner integration
- [html5-qrcode](https://unpkg.com/html5-qrcode@2.3.8/html5-qrcode.min.js) library for QR code scanning functionality

## Usage

1. **Clone or Download the Repository**

   ```bash
   git clone https://github.com/Yuvaraj987/QR-Code_Scanner.git
   cd QR-Code_Scanner
   ```

2. **Open `index.html` in your web browser**

   You do not need to run a server; simply open the file directly.

3. **Grant Camera Access**

   When prompted, allow the browser to access your camera.

4. **Scan a QR Code**

   Point your device's camera at a QR code. The decoded text will be shown in an alert dialog.

## Project Structure

- `index.html` — Main HTML page for the scanner.
- `style.css` — Styling for the page and scanner UI.
- `script.js` — JavaScript for initializing and handling the QR code scanner.

## Credits

- Built by [Yuvaraj987](https://github.com/Yuvaraj987)
- QR scanning powered by [html5-qrcode](https://github.com/mebjas/html5-qrcode)

## License

This project is open source. See the repository for details.
