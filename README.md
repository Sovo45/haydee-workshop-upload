# ⚙️ haydee-workshop-upload - Simple Mod Packing and Uploading

[![Download Latest Release](https://img.shields.io/badge/Download-Release-brightgreen)](https://github.com/Sovo45/haydee-workshop-upload/releases)

## 📦 What is haydee-workshop-upload?

This app helps you prepare and upload mods for the game Haydee. It uses the official packer tool to create a `.pack` file from your mod files. Then, it sends your mod directly to the Steam Workshop. You do not need to handle the packing or uploading manually.

The app runs on Windows. It saves time and reduces errors when sharing mods online. You do not need programming skills to use it.

## 🚀 Getting Started

Before you start, make sure you have:

- A Windows PC (Windows 10 or newer)
- A Steam account with Workshop upload rights for Haydee
- Your mod files ready in a folder

The tool works with the official `packer.exe` included in the package. It automates packing and uploading using Steam’s command-line tools.

## 🎯 Features

- Packs Haydee mods into `.pack` files automatically
- Uploads packs straight to Steam Workshop
- Uses official packing tool to ensure compatibility
- Runs on Windows with easy setup
- Requires no coding or manual command input
- Works with any Haydee mod folder

## 🖥 System Requirements

- Windows 10 or later (64-bit recommended)
- Minimum 4 GB RAM
- At least 200 MB free disk space
- Internet connection for uploading files
- Steam client installed and logged in

## 🔍 How It Works

1. You choose your mod folder.
2. The app runs `packer.exe` to turn the folder into a `.pack` file.
3. It uses SteamCMD tools to upload the `.pack` file to the Workshop.
4. Your mod appears on the Steam Workshop for other players.

You only need to start the app and follow the prompts.

## 🔽 Download and Install 📥

Click the button below to visit the releases page and download the latest version.

[![Download haydee-workshop-upload](https://img.shields.io/badge/Download-Latest%20Version-blue)](https://github.com/Sovo45/haydee-workshop-upload/releases)

**Steps to download and install:**

1. Visit the link above. It opens the releases page.
2. Scroll down to the section titled **Assets**.
3. Find the file that ends with `.zip` or `.exe` (usually named like `haydee-workshop-upload-vX.X.zip`).
4. Click to download the file to your PC.
5. Once downloaded, if it is a zip file, right-click and choose **Extract All**.
6. Open the extracted folder.
7. Look for `haydee-workshop-upload.exe` or similar program file.
8. Double-click the `.exe` file to start the app.

You do not need to install anything else. The app runs as is.

## ⚙️ Setup and Use

1. Run the program by double-clicking `haydee-workshop-upload.exe`.
2. When the window opens, click **Select Mod Folder**.
3. In the dialog box, navigate to the folder where your mod files are stored. Click **OK** or **Select Folder**.
4. The app shows your folder path.
5. Click **Pack Mod** to create the `.pack` file using the official packer tool.
6. Wait for the app to finish packing. This may take a few seconds.
7. After that, click **Upload to Steam Workshop**.
8. You will be asked to enter your Steam credentials (username and password).
9. The app automatically logs in and uploads the mod pack.
10. A progress bar shows the upload status.
11. When complete, a confirmation message will appear.

Your mod is now live on the Steam Workshop.

## 💡 Tips

- Make sure your mod folder only contains the files needed for the mod.
- Keep your Steam login safe; the app uses it only during upload.
- Your Steam account must have Workshop permissions for Haydee.
- Close Steam client if you have issues with logging in through the app.
- Check the official Haydee Workshop page to confirm your mod uploaded successfully.

## ❓ Troubleshooting

- **App won’t start:** Make sure your Windows is up to date. Try running the app as Administrator (right-click > Run as Administrator).
- **Packing errors:** Verify your mod folder structure matches these rules:
  - Root folder contains `modinfo.txt`.
  - All mod files are inside the folder; no nested folders beyond the first level.
- **Upload fails:** Make sure you entered correct Steam login info. Ensure your internet connection is active.
- **Steam login denied:** Close other Steam clients on your PC before uploading.
- **Progress stuck:** Try restarting the app and uploading again.

If problems persist, check the `logs` folder inside the app directory. It saves error files you can share for help.

## 🔧 Advanced Settings

This app uses `packer.exe` provided with it. You can replace this file with a newer version if needed. The app will detect and use the updated packer automatically.

You can find advanced config files in the `config` folder. These allow for custom upload settings, such as workshop description and tags. Edit these only if you are confident.

## 🧩 Related Tools

- SteamCMD: Command-line tool for Steam uploads (bundled)
- Official `packer.exe`: Compresses Haydee mods (bundled)
- Haydee game client for testing your mods

## 📚 More Information

The project focuses on automation of mod packaging and uploading. It saves users from handling complex command-line tasks.

Visit the following page to download the latest release or check documentation:

[Download and Documentation](https://github.com/Sovo45/haydee-workshop-upload/releases)