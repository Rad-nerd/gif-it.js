<img src="logo.png" width="300px" alt="gif-it.js Logo - Stylized GIF icon with motion blur and text 'gif-it.js'"/>

## Put GIFs in Your Web-Pages Favicon

`gif-it.js` is a lightweight, single-file JavaScript solution that allows you to easily animate your website's favicon using a GIF, providing a dynamic and engaging visual for your browser tabs. It gracefully handles GIF frame extraction and animation, with built-in compatibility for different browser behaviors.

### ✨ Features

* **Single File:** All the necessary code for animated favicons (including the `SuperGif` library) is bundled into one convenient `gif-it.js` file.
* **Flexible GIF Sourcing:** Use GIFs hosted locally on your server or from external URLs.
* **Automatic Favicon Animation:** Handles frame extraction and updates the favicon dynamically.
* **Firefox Compatibility:** Automatically bypasses the animation for Firefox browsers, setting the GIF as a static favicon due to its lack of support for animated favicons via Data URLs.
* **Simple API:** Integrate with a single line of JavaScript in your HTML.
* **Hidden Processing:** GIF processing occurs in a hidden DOM element, preventing visual artifacts on your page.

### 🚀 Usage

Follow these simple steps to add an animated favicon to your web page:

#### 1. Download `gif-it.js`

First, download the `gif-it.js` file from its raw source on GitHub. You'll typically find it in your project's `main` branch:

<a href="https://raw.githubusercontent.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME/main/gif-it.js" download>Download gif-it.js</a>

Save this file into your web project directory (e.g., in a `js/` folder, or directly in your root).

#### 2. Link `gif-it.js` in Your HTML

Place the `<script>` tag for `gif-it.js` within the `<head>` or just before the closing `</body>` tag of your `index.html` (or relevant HTML file). If you plan to host it directly from GitHub Raw, use the direct link:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Awesome Page</title>
    <link id="faviconLink" rel="icon" href="data:," type="image/png">
    
    <script src="[https://raw.githubusercontent.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME/main/gif-it.js](https://raw.githubusercontent.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME/main/gif-it.js)"></script>
    
    </head>
<body>
    </body>
</html>
