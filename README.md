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
