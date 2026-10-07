# 💌 Will You Be My Valentine? (Interactive Web App)

A lightweight, fully customizable, self-contained HTML web application designed to ask someone special to be your Valentine. It features a playful UI with a shrinking/moving "No" button, a growing "Yes" button, custom images/GIFs, falling confetti, and an **automatic email notification system** via Formspree so you know immediately when they say "Yes" without needing them to manually click send on WhatsApp!

---

## ✨ Features

- **Interactive Experience:** When they try to click "No", the text changes playfully and the "Yes" button grows bigger.
- **Instant Email Alert (Formspree Integration):** The moment they click "Yes", a background request triggers a silent notification straight to your email inbox (no manual WhatsApp sharing required).
- **Customizable Fields:** Easily customize their name, your name, custom opening lines, hesitation prompts, and the final success message.
- **Photo Support:** Paste an image URL or upload a photo directly from your device.
- **Single File Portability:** Generates a clean, standalone HTML file that you can share, email, or send via AirDrop.

---

## 🚀 How to Set Up & Use

### Step 1: Get Your Formspree Endpoint (For Email Notifications)
To receive an email notification when she clicks "Yes":
1. Go to [Formspree](https://formspree.io/) and sign up for a free account.
2. Create a new form and copy your unique **Endpoint URL** (it looks like `https://formspree.io/f/your-form-id`).

### Step 2: Configure the Code
Open the `will-you-be-my-valentine.html` file in any text editor (like Notepad, VS Code, etc.) and find this line inside the JavaScript section:

```javascript
fetch('[https://formspree.io/f/YOUR_FORMSPREE_ENDPOINT_HERE](https://formspree.io/f/YOUR_FORMSPREE_ENDPOINT_HERE)', {

Replace 'YOUR_FORMSPREE_ENDPOINT_HERE' with your actual Formspree endpoint URL:
fetch('[https://formspree.io/f/mqkopwza](https://formspree.io/f/mqkopwza)', {

Step 3: Run or Deploy
 * Open the HTML file in any modern web browser to use the builder.
 * Fill in her name, custom messages, and upload/link a cute photo.
 * Click "💌 Create my link" or "Download HTML".
 * Send the generated link or downloaded .html file to your special someone!
🛠️ Built With
 * HTML5 / CSS3: Responsive design optimized for mobile and desktop screens.
 * Vanilla JavaScript: Clean client-side logic with zero external framework dependencies.
 * Formspree API: Seamless background form submissions for instant email alerts.
📌 Note
Nothing entered into the builder is stored on an external server — everything is safely encoded directly into the shareable link or bundled inside the downloaded HTML file.

