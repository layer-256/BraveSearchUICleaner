# Brave search UI Cleaner Extension

![Pure CSS](https://img.shields.io/badge/pure%20css-4285F4?style=for-the-badge&logo=css)
![Product](https://img.shields.io/badge/made%20for%20brave-ff4400?style=for-the-badge&logo=brave&logoColor=white)
![Licenced](https://img.shields.io/badge/Licenced-red?style=for-the-badge&logo=creativecommons&logoColor=white)

## Features

<!-- This is a mini extension written only in CSS for [Brave Search](https://search.brave.com/search?q=kittens).
This extension removes not needed stuff from brave search, for example: settings, all tabs except for all and pictures, footer, ai result and bits of not needed info in search results. Also it centers everything out  -->
* **Decluttered Interface**
Removes settings, footers, and redundant UI elements
* **Focused Navigation**
Keeps only the essential tabs (All and Images)
* **AI Free Search**
Removes the AI summary
* **Perfect Center**
Completely centers everything out for a cleaner look
* **Lightweight**
Written entirely in CSS
## Showcase (Before/After)

### All category
<table>
<tr>
<td width="50%"><img src="/showcaseImages/BeforeAll.png" width="100%"/></td>
<td width="50%"><img src="/showcaseImages/AfterAll.png" width="100%"/></td>
</tr>
</table>

### Footer
<table>
<tr>
<td width="50%"><img src="/showcaseImages/BeforeFooter.png" width="100%"/></td>
<td width="50%"><img src="/showcaseImages/AfterFooter.png" width="100%"/></td>
</tr>
</table>

### Pictures
<table>
<tr>
<td width="50%"><img src="/showcaseImages/BeforePics.png" width="100%"/></td>
<td width="50%"><img src="/showcaseImages/AfterPics.png" width="100%"/></td>
</tr>
</table>

### Pictures details
<table>
<tr>
<td width="50%"><img src="/showcaseImages/BeforePicsDetails.png" width="100%"/></td>
<td width="50%"><img src="/showcaseImages/AfterPicsDetails.png" width="100%"/></td>
</tr>
</table>

## How to setup

### Step 1: Prepare the files
1. Download the repository as a ZIP archive.
2. Unzip the downloaded folder to any convenient location on your computer

### Step 2: Enable Developer Mode in your browser
1. Open any Chromium-based browser (Chrome, Edge, Brave, Opera, etc.)
2. Navigate to the Extensions page by going to [chrome://extensions/](chrome://extensions/)
3. In the top-right corner, turn ON the "Developer mode" toggle

### Step 3: Load the extension
1. Click the "Load unpacked" button that appears in the top left corner
2. Select the unzipped repository folder
3. Open the [Brave Search](https://search.brave.com/search?q=kittens) and check out the results

### Step 4...
Enjoy :)

## OR How to setup via Stylus

If you don't want to enable Developer Mode, you can use a custom style manager:
1. Install the [Stylus](https://add0n.com/stylus.html) extension for your browser
2. Create a new style for `search.brave.com`
3. Copy and paste the contents of `changes.css` and `removes.css` files from `./css` directory of this repository

## How to update
If there will be a newer version of this extension:
1. Download and unzip the repository
2. Go to [chrome://extensions/](chrome://extensions/) and delete the old version
3. Click the "Load unpacked" button that appears in the top left corner
4. Select the unzipped repository folder

## Contributing

Brave Search updates its layout from time to time. 
If you notice that something has broken, feel free to open an Issue or submit a Pull Request with updated CSS selectors

## License

Copyright (c) 2026 layer-256

This project is licensed under the [CC BY-NC-SA 4.0](LICENSE) license.
