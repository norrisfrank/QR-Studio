# Norry QR Studio

**Live Environment:** [qr-studio-eqqa.onrender.com](https://qr-studio-eqqa.onrender.com)

Norry QR Studio is a dedicated client-side utility for generating high-fidelity QR codes. Engineered to prioritize data privacy and execution speed, the application performs all encoding and image rendering within the user's browser environment, completely bypassing the need for external processing or server interactions.

## System Capabilities

* **Local Generation:** Utilizes `qrcode.js` for immediate in-browser rendering. This architecture guarantees data privacy by preventing any transmission of user input to external services.
* **Multi-Format Support:** Accommodates standard text strings, web URLs, and specialized Wi-Fi credential encoding for automated network authentication.
* **Configurable Density and Scaling:** Provides granular control over error correction levels (L, M, Q, H) and output dimensions (160px to 320px), ensuring reliable scannability across diverse print and digital mediums.
* **Direct Asset Export:** Facilitates immediate download of generated QR codes as high-resolution PNG files.
* **Responsive Architecture:** Features a fluid interface constructed with modern CSS properties, guaranteeing a consistent user experience across desktop, tablet, and mobile form factors.

## Technical Foundation

* **Presentation Layer:** HTML5 and Vanilla CSS, leveraging native keyframe animations and custom properties without reliance on CSS frameworks.
* **Application Logic:** Vanilla JavaScript for state management and DOM manipulation, maintaining a minimal execution footprint.
* **Rendering Subsystems:** `qrcode.js` handles matrix generation, while WebGL powers the ambient background shaders.

## Local Deployment

As a fully static application, Norry QR Studio requires no build pipeline or server-side runtime.

1. Clone the repository to the local filesystem.
2. Initialize a local development server or open `norry_qr_generator.html` directly in a modern web browser.
3. Select the desired encoding format via the user interface.
4. Input the necessary parameters and initiate generation.
5. Adjust dimensions as required and export the generated PNG asset.

## License

This project is distributed under the [MIT License](LICENSE).
