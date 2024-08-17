# Image Compression with JavaScript

Welcome to the **Image Compression with JavaScript** project! 🎉

This repository contains the source code for a tutorial that shows you how to compress images directly in the browser using JavaScript. The project was developed as part of the EgiPegi YouTube channel's tutorial series.

## Overview

In this project, you will learn how to:

- Accept image files via an HTML input.
- Scale the image to fit within specified maximum dimensions.
- Compress the image to a specified maximum file size.
- Display the compressed image on the web page.

## Features

- **Responsive Image Handling**: Automatically resizes images based on their dimensions.
- **Efficient Compression**: Uses a binary search approach to find the optimal quality setting for image compression.
- **Browser-Based**: No need for server-side processing—everything is handled client-side.

## Getting Started

### Prerequisites

To run this project, you'll need:

- A modern web browser (e.g., Chrome, Firefox, Edge).
- Basic knowledge of HTML, CSS, and JavaScript.

### Usage

- Select an image using the file input.
- The image will be automatically resized and compressed.
- The compressed image will be displayed on the page.

### Code Structure

- `index.html` - The main HTML file that includes the layout and structure of the page.
- `styles.css` - Optional: The CSS file for styling the page.
- `script.js` - Contains the JavaScript logic for image compression.

### Customization

You can adjust the maximum width, height, and file size by modifying these values in the JavaScript code:

```javascript
const MAX_WIDTH = 1920;
const MAX_HEIGHT = 1920;
const MAX_SIZE = 95000; // in bytes
```
