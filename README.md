# LeetCode VSCode Setup Guide

This repository provides a step-by-step guide to setting up LeetCode coding environment in Visual Studio Code (VSCode).

## Prerequisites

Before you start, make sure you have:
- [Visual Studio Code](https://code.visualstudio.com/) installed.
- [Node.js](https://nodejs.org/) installed.
- A LeetCode account.

## Steps to Setup

### 1. Install VSCode Extensions

1. Open VSCode.
2. Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window or pressing `Ctrl+Shift+X`.
3. Search for and install the following extensions:
   - **LeetCode**: This extension integrates with the LeetCode platform to help you manage and submit your code.
   - **Python** (or the appropriate language extension you plan to use): For coding in Python, C++, Java, etc.
   - **Code Runner**: Allows you to run code snippets quickly.

### 2. Configure LeetCode Extension

1. After installing the LeetCode extension, open the Command Palette with `Ctrl+Shift+P` (or `Cmd+Shift+P` on macOS).
2. Type `LeetCode: Sign In` and follow the prompts to log in to your LeetCode account.
3. Configure any additional settings if needed by going to the VSCode settings (`File` > `Preferences` > `Settings`) and searching for `LeetCode`.

### 3. Cloning LeetCode Repository

1. Open a terminal in VSCode by selecting `Terminal` > `New Terminal` from the menu.
2. Clone the LeetCode repository (or create a new one) by using the following command:
   ```sh
   git clone https://github.com/your-username/your-repo-name.git
   ```
3. Navigate to the cloned repository:
   ```sh
   cd your-repo-name
   ```

### 4. Start Coding

1. **Open a LeetCode Problem**:
   - Open the Command Palette by pressing `Ctrl+Shift+P` (or `Cmd+Shift+P` on macOS).
   - Type `LeetCode: Search Problem` and select it from the list.
   - Choose a problem from your LeetCode account to open it in the editor.

2. **Write Your Solution**:
   - In the editor, write your code to solve the problem.

3. **Test Your Code**:
   - Open the Command Palette by pressing `Ctrl+Shift+P` (or `Cmd+Shift+P` on macOS).
   - Type `LeetCode: Test` and select it from the list.
   - The extension will run your code against the test cases provided by LeetCode and display the results in the Output pane or inline in the editor.

4. **Submit Your Code**:
   - Open the Command Palette by pressing `Ctrl+Shift+P` (or `Cmd+Shift+P` on macOS).
   - Type `LeetCode: Submit` and select it from the list.
   - Confirm the submission when prompted. The extension will submit your solution to LeetCode.

By following these steps, you can efficiently test and submit your LeetCode solutions directly from VSCode.


## Additional Resources

- [LeetCode Documentation](https://leetcode.com/)
- [VSCode Documentation](https://code.visualstudio.com/docs)

## Contributing

If you'd like to contribute to this guide or have suggestions for improvement, please fork the repository and create a pull request.

## License

This repository is licensed under the [MIT License](LICENSE).

