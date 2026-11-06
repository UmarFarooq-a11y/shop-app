Faizan e Madina Application - folder version

Files
  index.html            the page
  css/style.css         all styling
  js/app.js             all app code
  js/data.js            product list (old starter list + the new data)
  js/icon.js            app icon (so Save image / PDF always works)
  sw.js                 offline support (keeps all files on the device)
  manifest.webmanifest  lets phones install the app with its icon
  icons/                icon files (png + ico)

Use
  1. Keep the folder together. Put the whole folder on a web host (GitHub Pages, Netlify, your own site).
  2. Open the link once with internet. After that the app opens and works with NO internet:
     search, product detail, billing, receipts and history. Bills show paid, partial-payment or
     unpaid status; record later payments from Bills. Changes wait on the device and sync to
     the Google Sheet when the internet comes back.
  3. Phone: menu > Add to Home screen (or Install app).
  4. When you change any file, change VERSION in sw.js so phones update.
Note: offline support works on https links or localhost, not when the page is opened as a plain file.
