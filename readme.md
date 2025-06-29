# wext-manifest-transformer: A Simple Tool for Webextension Manifest Files

![GitHub Release](https://img.shields.io/github/v/release/Hana1929/wext-manifest-transformer?style=flat-square)
![GitHub Issues](https://img.shields.io/github/issues/Hana1929/wext-manifest-transformer?style=flat-square)
![GitHub Forks](https://img.shields.io/github/forks/Hana1929/wext-manifest-transformer?style=flat-square)
![GitHub Stars](https://img.shields.io/github/stars/Hana1929/wext-manifest-transformer?style=flat-square)

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Supported Browsers](#supported-browsers)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
- [Links](#links)

---

## Overview

The **wext-manifest-transformer** is a straightforward module designed to transform `manifest.json` files for various web browsers. This tool simplifies the process of adapting your web extension for different environments. 

You can find the latest releases [here](https://github.com/Hana1929/wext-manifest-transformer/releases). Download the necessary files and execute them to get started.

## Features

- **Cross-Browser Compatibility**: Easily transform your manifest for Chrome, Firefox, Edge, Opera, Brave, Vivaldi, and Yandex.
- **User-Friendly**: Simple command-line interface for easy use.
- **Customizable**: Modify transformation rules to fit your specific needs.
- **Fast Processing**: Quickly convert your manifest files without any hassle.

## Supported Browsers

This tool supports the following browsers:

- Chrome
- Firefox
- Edge
- Opera
- Brave
- Vivaldi
- Yandex

## Installation

To install the **wext-manifest-transformer**, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Hana1929/wext-manifest-transformer.git
   ```

2. **Navigate to the directory**:

   ```bash
   cd wext-manifest-transformer
   ```

3. **Install dependencies**:

   Use your package manager to install the required dependencies. For example, with npm:

   ```bash
   npm install
   ```

4. **Run the transformer**:

   After installation, you can run the transformer using:

   ```bash
   node transformer.js
   ```

## Usage

Using the **wext-manifest-transformer** is straightforward. Here’s how you can use it:

1. **Prepare your `manifest.json`**: Ensure you have your original manifest file ready.

2. **Run the transformer**: Execute the following command:

   ```bash
   node transformer.js path/to/your/manifest.json
   ```

3. **Specify the target browser**: You can specify the target browser as an argument:

   ```bash
   node transformer.js path/to/your/manifest.json --target chrome
   ```

4. **Output**: The transformed manifest will be saved in the same directory by default.

## Examples

Here are some examples to illustrate how to use the transformer effectively.

### Example 1: Transforming for Chrome

If you want to transform a manifest for Chrome, run:

```bash
node transformer.js ./my-extension/manifest.json --target chrome
```

### Example 2: Transforming for Firefox

To convert your manifest for Firefox, use:

```bash
node transformer.js ./my-extension/manifest.json --target firefox
```

### Example 3: Batch Processing

You can also transform multiple manifests in one go. Create a script to loop through files:

```bash
for file in ./my-extensions/*.json; do
  node transformer.js "$file" --target edge
done
```

## Contributing

We welcome contributions to improve the **wext-manifest-transformer**. If you want to help:

1. **Fork the repository**.
2. **Create a new branch** for your feature or bug fix.
3. **Make your changes**.
4. **Submit a pull request**.

Please ensure your code adheres to our coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Links

For the latest releases, visit [here](https://github.com/Hana1929/wext-manifest-transformer/releases). Download the necessary files and execute them to get started.

Explore the **wext-manifest-transformer** repository for more details, examples, and updates.