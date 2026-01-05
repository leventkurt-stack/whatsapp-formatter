# WhatsApp Phone Number Formatter

A simple web application that formats Turkish phone numbers and opens WhatsApp chats directly from your browser.

## 🌐 Live Demo

Visit the live application: [https://leventkurt-stack.github.io/whatsapp-formatter/](https://leventkurt-stack.github.io/whatsapp-formatter/)

## ✨ Features

- **Automatic Formatting**: Converts Turkish phone numbers to international format (+90)
- **Multiple Input Formats**: Handles various input patterns:
  - 10-digit numbers (5551234567) → +905551234567
  - 11-digit with leading 0 (05551234567) → +905551234567
  - 12-digit starting with 90 (905551234567) → +905551234567
  - 13-digit starting with 90 (9005551234567) → +9005551234567
- **Input Validation**: Only allows digits, +, (), and spaces
- **Real-time Preview**: See the formatted number as you type
- **Direct WhatsApp Integration**: Opens WhatsApp chat with one click

## 🚀 Usage

1. Enter a phone number in any supported format
2. The formatted number appears below the input field
3. Click "Submit" to open a WhatsApp chat with that number

## 💻 Technology

- Pure HTML, CSS, and JavaScript
- No dependencies or frameworks required
- Works on desktop and mobile browsers

## 📝 How It Works

The application uses the WhatsApp `wa.me` API to open chats. When you submit a formatted phone number, it redirects to `https://wa.me/[number]`, which opens WhatsApp Web (desktop) or the WhatsApp app (mobile).

## 🤝 Contributing

Feel free to fork this repository and submit pull requests for any improvements.

## 📄 License

This project is open source and available for anyone to use and modify.
