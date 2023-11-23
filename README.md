<h1 align="center"><a href="https://alialmasi.github.io/newtab/" target="_blank">New Tab (to preview now, click here)</a></h1>

## Installation

### 1. Download

Download the `index.html` file from [the releases page *(recommended)*](https://github.com/AliAlmasi/newtab/releases/latest) (or download it directly from the repository).
Once you have downloaded the file, move the `index.html` file to the folder where you want to store it.

### 2. Install *New Tab Override* extension

Install the extension based on your browser.

> Tip: On Chrome it's titled 'New Tab Redirect', on Firefox it's titled 'New Tab Override'

You can install the extension on your browser by selecting your browser below.

<a href="https://addons.mozilla.org/en-US/firefox/addon/new-tab-override/"><img src="https://user-images.githubusercontent.com/74229780/211720609-6ed494f5-cabe-412a-9a8a-c1be9be58c5c.png" width="24px"></a>
<a href="https://chrome.google.com/webstore/detail/new-tab-redirect/icpgjfneehieebagbmdbhnlpiopdcmna"><img src="https://user-images.githubusercontent.com/74229780/211722577-be8f1689-1883-4ab2-be85-7d938f34997f.png" width="24px"></a>

> Note: If your browser is not Chrome or Firefox either, you should search and see what your browser is based on. *Brave is based on Chrome so the Chrome extension will install successfully in Brave.*

### 3. Config the *New Tab Override* extension

<details>
<summary>Chrome</summary>

1. Open the extensions by typing `chrome://extensions/` in the address bar.
2. Find the "New Tab Redirect" extension and click the "Details" button.
3. Click the "Extension Options" button.
4. Go to the "URL" tab.
5. Paste the path to the index file you unzipped earlier into the "Redirect URL" field.
6. Then click the "Save" button.

</details>

<details>
  <summary>FireFox</summary>


1. Open the extensions by typing `about:addons` in the address bar.
2. Go to the "Extensions" tab.
3. Find the "New Tab Override" extension, click the three-dot button, and select options.
4. Set "Option" to "local file".
5. Click "Browse" and select the index file you unzipped earlier.

</details>

### 4. Set focus to built-in search bar *(optional)*

First, you need to set up Nginx (or any other web server. *for example, I use Xampp on Linux, and Wamp on Windows*) based on [this wiki](https://github.com/jimschubert/NewTab-Redirect/wiki#page-focus-on-file-redirects). Then you have to do the following:

<details>
<summary>Chrome</summary>

1. Go to the "Extension Options" page as you did before.
2. Go to the "URL" tab.
3. Paste `http://localhost` into the "Redirect URL" field.
4. Click the "Save" button.

</details>

<details>
  <summary>FireFox</summary>


1. Go to the "New Tab Override" settings as you did before.
2. Set "Option" to "custom URL".
3. Paste `http://localhost` into the "URL" field.
4. Check the "Set focus to the web page instead of the address bar" checkbox.

</details>
