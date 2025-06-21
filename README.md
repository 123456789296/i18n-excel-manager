# i18n Excel Manager 🌍

![i18n Excel Manager](https://img.shields.io/badge/i18n%20Excel%20Manager-v1.0.0-blue.svg)
[![Releases](https://img.shields.io/badge/Releases-latest-orange.svg)](https://github.com/123456789296/i18n-excel-manager/releases)

Welcome to the **i18n Excel Manager**! This command-line interface (CLI) tool simplifies the process of converting and validating internationalization (i18n) JSON and Excel files. It ensures your translations are accurate and properly formatted, making localization easier than ever.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Commands](#commands)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Convert JSON to Excel**: Easily convert your i18n JSON files into Excel format.
- **Validate Files**: Check for errors in your JSON and Excel files.
- **Placeholder Validation**: Ensure that placeholders in your translations are correctly formatted.
- **Multi-language Support**: Work with various languages and formats.
- **Easy to Use**: Simple commands for fast execution.

## Installation

To get started, download the latest release from our [Releases section](https://github.com/123456789296/i18n-excel-manager/releases). You will find the necessary files to download and execute.

### Prerequisites

Make sure you have the following installed:

- Node.js (version 12 or higher)
- npm (Node package manager)

### Steps to Install

1. Clone the repository:
   ```bash
   git clone https://github.com/123456789296/i18n-excel-manager.git
   cd i18n-excel-manager
   ```

2. Install the dependencies:
   ```bash
   npm install
   ```

3. Build the project:
   ```bash
   npm run build
   ```

4. Run the tool:
   ```bash
   npm start
   ```

## Usage

Once installed, you can start using the tool directly from your command line. The basic syntax is:

```bash
i18n-excel-manager <command> [options]
```

## Commands

### Convert JSON to Excel

To convert a JSON file to Excel format, use the following command:

```bash
i18n-excel-manager convert json-to-excel --input <input.json> --output <output.xlsx>
```

### Validate JSON

To validate a JSON file, run:

```bash
i18n-excel-manager validate json --input <input.json>
```

### Validate Excel

To validate an Excel file, use:

```bash
i18n-excel-manager validate excel --input <input.xlsx>
```

### Placeholder Validation

To validate placeholders in your translations, execute:

```bash
i18n-excel-manager validate placeholders --input <input.json>
```

## Example

Here’s an example of how to convert a JSON file to Excel:

```bash
i18n-excel-manager convert json-to-excel --input translations.json --output translations.xlsx
```

This command takes `translations.json` and converts it into `translations.xlsx`.

## Contributing

We welcome contributions! If you have ideas for improvements or new features, please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push to your branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or issues, feel free to reach out:

- GitHub: [i18n Excel Manager](https://github.com/123456789296/i18n-excel-manager)
- Email: your-email@example.com

## Acknowledgments

- Thanks to the contributors who have helped improve this tool.
- Special thanks to the community for their support and feedback.

## Conclusion

The **i18n Excel Manager** is a powerful tool for anyone working with translations and localization. Download the latest version from our [Releases section](https://github.com/123456789296/i18n-excel-manager/releases) to get started. 

Happy coding! 🌟