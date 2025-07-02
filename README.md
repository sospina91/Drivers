# Driver Management Web App (Command Alkon API)

This is a lightweight web app built with HTML, CSS, and JavaScript to manage drivers using the Command Alkon Cloud Dispatch API.

✅ Features:
- Input and store API credentials (Entity Ref, API Key, Bearer Token)
- Create or update drivers via POST
- Fetch all drivers and display them in a table
- Edit driver info directly from the list
- Delete drivers with a single click
- Hosted on [Netlify](https://www.netlify.com/) for easy deployment

---

## 🚀 How to Use

1. **Enter your credentials** in the left panel:
   - Entity Reference
   - API Key
   - Bearer Token (access_token)

2. **Create or update a driver**:
   - Fill in Driver ID, First Name, and Last Name
   - Click “Create or Update Driver”

3. **Fetch drivers**:
   - Click the “Fetch Drivers” button to retrieve all active drivers

4. **Edit or Delete**:
   - Click “Edit” to load a driver’s info into the form
   - Click “Delete” to remove a driver from the system

---

## 🛠 Tech Stack

- HTML5 / CSS3
- Vanilla JavaScript
- [Command Alkon Cloud API](https://developer.commandalkon.io/)
- Netlify for hosting

---

## 🔐 Authentication

The app requires the following credentials:
- `entityRef`: Provided by Command Alkon
- `x-api-key`: API key for your site
- `access_token`: Generated from your `refresh_token` (can be automated in future version)

Tokens are used in HTTP headers for authenticated API requests.

---

## 📦 To Deploy on Netlify

1. Clone this repo or create a new one with the provided `index.html`
2. Push to GitHub
3. Go to [Netlify](https://app.netlify.com/) → “New Site from Git”
4. Link your repo → Click “Deploy”

That’s it! You’ll have a public web app to manage your drivers.

---

## 📋 License

MIT — Free to use, modify, and share.
