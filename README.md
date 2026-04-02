# Norry QR Studio 📱✨

**Live Demo:** [https://qr-studio-eqqa.onrender.com](https://qr-studio-eqqa.onrender.com)

A sophisticated, beautifully designed, completely client-side QR Code generator. Built specifically with an elegant UI, featuring a dynamic glowing glassmorphism aesthetic and a premium user experience. 

## ✨ Features

- **Blazing Fast API-free Generation:** Leverages `qrcode.js` to render QR codes purely in the browser. Zero reliance on external backend servers.
- **Glassmorphism Aesthetic:** A stunning UI consisting of dynamic animated desktop & mobile-optimized glowing oceanic orbs against a deep dark background.
- **URL & Text Mode:** Quickly translate any standard web URLs or plain text blobs into a responsive QR code.
- **Wi-Fi Network Mode:** Instantly generate specialized QR codes that authenticate devices into your home or office Wi-Fi network without typing a password. Displays your security keys elegantly on the printed design!
- **Download Ready:** Generates high-resolution PNGs tailored to user-specified sizes (160px – 320px) ready for 1-click download.
- **Adjustable Error Correction:** Customize QR density (L, M, Q, H) to optimize how easy it is to scan at varying screen sizes.
- **Mobile Optimized:** Completely responsive and beautifully translates the glass UI to portrait orientation devices.

## 🚀 Usage

Since the app doesn't require a backend, you can literally run it locally:

1. Clone or download the repository to your machine.
2. Double-click the `norry_qr_generator.html` file to open it in any modern browser.
3. Select your QR type (Text/URL vs. Wi-Fi).
4. Enter your details and press **Generate**. 
5. Download and share!

## 🛠️ Technology Stack

- **HTML5 & Vanilla CSS:** No frontend frameworks. Pure CSS utilizing `backdrop-filter`, CSS Variables, and native `@keyframes` animations.
- **Vanilla JavaScript:** Simple, lightweight script managing the UI state and generation logic.
- **WebGL:** Ambient shader functionality integrated directly into the visual layout (embedded seamlessly into the design).
- **qrcode.js:** A robust cross-browser QR rendering library.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
