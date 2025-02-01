# Flexit - Flex File Snippets for VS Code

**Flexit** is a VS Code extension that brings efficient code snippets for **Flex** files (`.l`). It simplifies your workflow by providing ready-to-use templates, making it easier to write **Lexical Analyzers** with **Flex**.

Whether you're a beginner or an experienced developer, **Flexit** helps you get started quickly with pre-configured Flex templates and commonly used patterns.


## Installation

You can install **Flexit** directly from the [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/) by searching for **Flexit**.

## Usage

1. Create a new file with a `.l` extension (e.g., `scanner.l`).
2. Start typing any snippet prefix (e.g., `st`) and hit `Enter` to insert the corresponding code.
3. Modify the code as needed to suit your project.


## Available Snippets

- **`st`**:  Flex starter code template.
- **`int`**: Matches an integer (`[0-9]+`).
- **`hex`**: Matches a hexadecimal number (`0[xX][0-9a-fA-F]+`).
- **`oct`**: Matches an octal number (`0[0-7]+`).
- **`flt`**: Matches a floating-point number (`[0-9]+\\.[0-9]+`).
- **`id`**: Matches an identifier (`[a-zA-Z_][a-zA-Z0-9_]*`).
- **`str`**: Matches a string (`"[^"]*"`).
- **`comm`**: Matches a block comment (`/\\*[^*]*\\*+(?:[^/*][^*]*\\*+)*\\/`).
- **`lcom`**: Matches a single-line comment (`//.*`).
- **`ws`**: Matches whitespace characters (`[ \t\r\n]+`).


## Release Notes

### 1.0.0
Initial Version

### 1.1.0
Added more snippets

## Contributing

Feel free to contribute by:
- Adding new snippets.
- Reporting bugs or issues.
- Submitting feature requests.

### Steps to Contribute:
1. Fork the repository.
2. Make changes or add snippets.
3. Create a pull request with your improvements.

## Author

**Santhosh**  
📍 IIIT Hyderabad  
📧 [santhoshiiith@gmail.com]  
🔗 [GitHub](https://github.com/Santhosh-2205)  

---

If you have any questions or feedback, feel free to open an issue on [GitHub](https://github.com/Santhosh-2205/flexit/issues).

Happy coding! 🎉
