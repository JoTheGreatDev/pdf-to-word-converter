# PDF to Word Converter

A small pet project for converting PDF files to Word documents directly in the
browser. The conversion uses the bundled WebAssembly assets, so the selected
document is handled locally by the browser.

## Run it

1. Install dependencies:

   ```sh
   npm install
   ```

2. Start the server:

   ```sh
   npm start
   ```

3. Open the root page in a browser: [http://localhost:3000/](http://localhost:3000/).

   If you set the `PORT` environment variable, use that port instead.

## Use it

1. Select a PDF file.
2. Optionally enter a name for the converted document.
3. Click **Convert Document** and download the finished file when it is ready.
