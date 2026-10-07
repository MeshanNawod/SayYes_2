# Will you be my Valentine? 💌

A single HTML file. No server, no domain, no accounts. You fill in a form, download a personalised copy, send it on WhatsApp, and get notified when she says **Yes**.

## How it works

1. Open `will-you-be-my-valentine.html` in your browser (this is the **builder**).
2. Fill in the form and click **Create my link**.
3. Click **Download HTML**. This gives you a personalised copy named `will-you-be-my-valentine.html`.
4. Send that downloaded file to her on WhatsApp (as a document).
5. She opens it, taps **Yes**, and you find out.

## Getting notified (two ways, use both)

### Option A: WhatsApp message (she taps Send)

- Enter your WhatsApp number in the form: country code + number, no `+` or spaces. Example for Sri Lanka: `94771234567` (drop the leading 0).
- After she taps Yes, a green **Tell him 💬** button appears. It opens WhatsApp with a ready message to you. She only has to tap Send.
- Browsers cannot send WhatsApp messages or emails silently, so this needs her tap.

### Option B: Instant automatic alert (ntfy.sh)

This one needs no tap from her.

1. Install the free **ntfy** app on your phone (Android or iOS).
2. Tap **+** and subscribe to a secret name, for example `kasun-valentine-7392`. Make it random and hard to guess.
3. Type the **same name** into the "Secret alert name" field in the form.
4. When she taps Yes, her phone sends a message to that name and your phone pings right away.

Notes:
- She needs internet when she taps Yes.
- Anyone who knows your secret name can read or send alerts on it, so do not use something obvious like your own name.
- Only letters, numbers, `_` and `-` are kept in the name.

## Test it first

Before sending it to her:

1. Create your personalised file with your own name as "Their name".
2. Open the downloaded file on your phone or computer.
3. Click No a few times, then Yes.
4. Check that the ntfy alert arrives and that the WhatsApp button opens a chat with your number.

## Photos

- **Image link:** paste a link to a hosted photo. Keeps things small.
- **Upload:** the photo is cropped to a small square and stored inside the file. This works best with the downloaded file.

## Tips for sending

- Send it as a **document** on WhatsApp. On Android she can tap it and choose Chrome to open it. On iPhone, the file preview may not run the page, so tell her to use the share icon and open in Safari or Chrome, or use a free host such as Netlify Drop (drag the file onto it, you get a link).
- If the page opens inside WhatsApp's own viewer and buttons do not work, ask her to open it in a normal browser.

## Privacy

Nothing you type is uploaded anywhere while building. Everything lives inside the file. The only network call is the optional ntfy alert sent when she taps Yes.

## Files

- `will-you-be-my-valentine.html`: builder and the page she sees, in one file.
- `README.md`: this guide.
