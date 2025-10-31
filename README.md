
A simple Node.js web app that generates QR codes instantly from any text or URL you provide!  
Built using **Express.js**, **EJS**, and the **QR Image** library.

Features
- Enter any text or URL to generate a QR code.
- Automatically creates and displays the QR image.
- Saves the generated QR code image locally.
- Clean and beginner-friendly code structure.

 Tech Stack
- **Backend:** Node.js, Express.js  
- **Frontend:** EJS Templates  
- **Library Used:** `qr-image`  

How It Works
1. The user enters a text or URL in the input form.  
2. The server uses the `qr-image` package to generate a QR code.  
3. The QR code is displayed on the page and saved in the project folder.

Run Locally
1. Clone this repository:
   ```bash
   git clone https://github.com/RekhaBiju/qr-code-generator.git
2. Install dependencies:  npm install

3. Run the app:  node index.js

4. Open your browser and visit:  http://localhost:3000


