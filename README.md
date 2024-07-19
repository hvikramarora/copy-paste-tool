## Copy Paste Tool
This is a simple web-based tool that allows users to store text in multiple text areas and copy the text to the clipboard with the click of a button. It is designed to be easy to use and modify, providing a quick way to manage and copy snippets of text.

### Features
- Multiple text areas for storing different pieces of text.
- Copy text to clipboard functionality for each text area.
- Easy to add more text areas by editing the HTML.

### Usage
1. Open the `copy-paste-tool.html` file in a web browser.
2. Identify the text block that you want to copy.
3. Click the "Copy to Clipboard" button to copy the text from the corresponding text area.

### Adding More Text Areas
To add more text areas, follow these steps:
1. Copy the following HTML snippet:
   ```html
   <div class="textarea-container">
       <textarea id="textAreaX" placeholder="Enter your text here...">Sample Text X</textarea>
       <button onclick="copyToClipboard('textAreaX')">Copy to Clipboard</button>
   </div>
A sample HTML snippet is also given in the html file. You can copy and edit it to add more blocks.
