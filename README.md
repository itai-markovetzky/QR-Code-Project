# QR Code Generator

This Node.js script simplifies the process of generating QR codes from URLs and saving them as PNG images. It also conveniently stores the URL in a text file.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Functionality](#functionality)
- [Dependencies](#dependencies)

## Prerequisites

Make sure you have Node.js installed on your machine. If you don't have it yet, grab it from the [Node.js official website](https://nodejs.org/).

## Installation

1. Clone or download this repository to your local machine.

    ```bash
    git clone https://github.com/itai-markovetzky/QR-Code-Project.git
    ```

2. Navigate to the project directory.

    ```bash
    cd QR-Code-Project
    ```

3. Install the necessary npm packages.

    ```bash
    npm install --save inquirer qr-image
    ```

## Usage

1. Run the script using the following command:

    ```bash
    node index.js
    ```

2. Enter the URL and choose a name for your QR code image when prompted.

3. The script will generate a QR code and save it as a PNG file with your chosen name. Your URL will also be saved in a file named "URL.txt".

## Functionality

- **QR Code Generation**: Generates QR codes from provided URLs using the `qr-image` library.
- **File Handling**: Saves generated QR codes as PNG files and maintains a record of URLs in "URL.txt".

## Dependencies

- [inquirer](https://www.npmjs.com/package/inquirer): Adds interactive prompts for a user-friendly experience.
- [qr-image](https://www.npmjs.com/package/qr-image): Handles the heavy lifting of QR code generation.

~ Itai Markovetzky
