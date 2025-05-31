# IMG Background Remover

A simple web application for removing the background from images using the [bg.remove API](https://www.bgremove.com/). Built with pure **HTML**, **CSS**, and **JavaScript** — no frameworks required!

## 🚀 Features

- **Upload Images:** Easily select and upload your images directly from your device.
- **Background Removal:** Instantly remove the background from your images using the bg.remove API.
- **Preview Result:** View the processed image with the background removed right in your browser.
- **Download Output:** Save your new, background-free image with a single click.
- **Responsive Design:** Clean and simple interface that works seamlessly on both desktop and mobile devices.

## 🛠️ Technologies Used

- **HTML**
- **CSS**
- **JavaScript**
- **bg.remove API**

## 📸 How It Works

1. **Upload your image** (JPG, PNG, etc.).
2. The app sends your image to the bg.remove API.
3. The background is automatically removed.
4. Preview and **download** your new image!

## 🔧 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Kumarkodi/IMG-Background_Remover.git
cd IMG-Background_Remover
```

### 2. Open `index.html`

Simply open the `index.html` file in your browser — no build steps required!

### 3. Set Up API Key

- Sign up at [bg.remove](https://www.bgremove.com/) to get your API key.
- Replace the placeholder in the JavaScript file (e.g. `main.js` or `script.js`) with your API key:
    ```js
    const API_KEY = 'YOUR_API_KEY_HERE';
    ```
- Save the file and refresh your browser.

## 📂 Project Structure

```
IMG-Background_Remover/
├── index.html
├── style.css
├── script.js
└── README.md
```

- **index.html**: Main HTML file.
- **style.css**: Styles for the web page.
- **script.js**: JavaScript logic for handling uploads, API calls, and downloads.

## ✨ Demo

You can see a live demo (if deployed) or run locally by opening `index.html`.
https://img-background-remover-ten.vercel.app/

## 📝 Notes

- This project uses **only HTML, CSS, and JavaScript** — no frameworks or libraries.
- Make sure to keep your API key secure and within usage limits as specified by bg.remove.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

Made with ❤️ by [Kumarkodi](https://github.com/Kumarkodi)
