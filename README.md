# Chrome Midnight Blue Theme

- Alhamdulillah 

Welcome to the **Chrome Midnight Blue Theme** repository! This theme gives your Chrome browser a sleek, professional look with a midnight blue color palette. Customize the colors of your theme easily to suit your preferences.

Thanks to **[AndrewGDX](https://chromewebstore.google.com/detail/midnight-white/clkfnlehhgaafnehkdcfejlapchmdicn)** for the inspiration and original creation of the Midnight White theme. This theme builds upon AndrewGDX's work and offers a variation with a midnight blue palette.



## Table of Contents

1. [Installation](#installation)
2. [How to Use](#how-to-use)
3. [How to Customize the Theme Colors](#how-to-customize-the-theme-colors)
4. [How to Add a Background Image](#how-to-add-a-background-image)
5. [License](#license)

---

## Installation

To install the **Chrome Midnight Blue Theme** on your browser, follow these steps:

1. **Download or Clone the Repository**  
   First, download or clone this repository to your local machine.

2. **Open Chrome Extensions Page**  
   Open **Google Chrome**, and go to the **Extensions page** by entering `chrome://extensions/` in the address bar and hitting **Enter**.

3. **Enable Developer Mode**  
   In the top-right corner of the Extensions page, toggle the switch to enable **Developer Mode**.

4. **Load the Theme**  
   Click the **Load unpacked** button. In the file dialog, navigate to the folder where you downloaded or cloned the theme repository, and select the folder containing the `manifest.json` file.

5. **Theme Installed**  
   After loading the theme, the **Midnight Blue Theme** will be active on your Chrome browser, and you’ll see a fresh, dark blue interface.

---

## How to Use

Once the theme is installed, it will automatically apply to your browser. Here's what you can expect:

- **Dark Midnight Blue Toolbar**: A sleek and modern toolbar with midnight blue accents.
- **New Tab Page (NTP)**: The background will feature a dark blue color with contrasting white text for easy reading.
- **Tab Text**: White text on tabs for better visibility.

You don’t need to do anything further to use the theme. Just install it and enjoy!

---

## How to Customize the Theme Colors

If you want to personalize the theme or change the colors, you can easily modify the `manifest.json` file. Here's how to do it:

### 1. **Locate the `manifest.json` File**

The `manifest.json` file contains all the color settings for your theme. Open it in any text editor (e.g., Notepad, VSCode, Sublime Text).

### 2. **Find the `theme` Section**

Inside the `manifest.json` file, look for the `"theme"` object. You'll see the `"colors"` field that defines the colors for different parts of the browser.

For example:

```json
"theme": {
  "colors": {
    "frame": [43, 53, 60],  // Dark blue frame color
    "toolbar": [72, 86, 95], // Midnight blue toolbar color
    "tab_text": [255, 255, 255], // White text on tabs
    "ntp_background": [44, 53, 59], // Dark blue New Tab page background
    "ntp_text": [255, 255, 255], // White text on New Tab page
    "button_background": [45, 53, 59, 0.01] // Transparent button background
  },
  "tints": {
    "buttons": [0, 0, 1], // Blue tint for buttons
    "frame_inactive": [0.5, 0.5, 0.4] // Lighter inactive frame color
  }
}
