# Pentagramme Veritatis Wallpaper 🎥

> **Bring your Windows 11 desktop to life!** This repository is a fork of the [`thebookisclosed/ViVe`](https://github.com/thebookisclosed/ViVe) project, dedicated to **enabling and using the hidden video wallpaper feature in Windows 11** (the modern successor to DreamScene).

This repository contains the **"Pentagramme Veritatis Wallpaper.mp4"** file. By following the steps below, you can set this video (or any of your own) as your desktop wallpaper directly through Windows Settings, **without any third-party software**.

---

## ✨ Features

- **Set Video as Wallpaper:** Use MP4, MOV, AVI, WMV, M4V, and MKV files as your desktop background.
- **No Third-Party Software Required:** Everything is done using a minimal command-line tool and Windows' own hidden feature.
- **Lightweight and Reliable:** Consumes far fewer resources than additional background software.
- **The Return of DreamScene:** The legendary feature from Windows Vista Ultimate is reborn in modern Windows 11.

## ⚠️ Requirements

To use this feature, your computer must meet the following conditions:

1.  **Operating System:** Windows 11 (Version 24H2 or later).
2.  **Build Number:** **26x20.6690** or higher from a preview build (Dev / Beta Channel).
3.  **Administrator Privileges:** Ability to run Command Prompt as Administrator.
4.  **ViVeTool:** A free tool used to enable or disable hidden Windows features.

> **Note:** This feature is currently in development and is disabled by default on stable Windows releases. It is expected to be officially added in future updates.

## 🚀 Installation and Usage

Follow these steps in order to set your video as a wallpaper.

### Step 1: Download and Prepare ViVeTool

1.  Download the latest version from the [ViVeTool GitHub Releases](https://github.com/thebookisclosed/ViVe/releases) page.
2.  Extract the downloaded ZIP file to an easily accessible folder, such as `C:\vive`.

### Step 2: Open Command Prompt as Administrator

1.  Type `cmd` in the Start menu.
2.  Right-click on **Command Prompt** and select **"Run as administrator"**.

### Step 3: Enable the Hidden Feature

1.  In Command Prompt, navigate to the ViVeTool folder:
    ```cmd
    cd C:\vive
    ```
2.  Run the following command to enable the video wallpaper feature:
    ```cmd
    ViVeTool.exe /enable /id:57645315
    ```
    This command activates the hidden video wallpaper feature (DreamScene) in Windows 11.

### Step 4: Restart Your Computer

A restart is recommended for the changes to take effect. Alternatively, you can restart the `explorer.exe` process from Task Manager.

### Step 5: Set Your Video as Wallpaper

1.  Go to **Settings > Personalization > Background**.
2.  Under "Personalize your background," click on **"Browse photos"**.
3.  Click the **"Browse"** button and select the `Pentagramme Veritatis Wallpaper.mp4` file included in this repository (or your own video).
4.  Your video will now start playing as your desktop wallpaper.

## 🎬 About the Video in This Repository

The **"Pentagramme Veritatis Wallpaper.mp4"** included in this repository is a high-resolution, loop-friendly, and visually striking video wallpaper. It has been specifically chosen to add depth and motion to your desktop.

## 🔧 Troubleshooting

- **Feature not showing up:** Ensure your Windows version is `26x20.6690` or higher. Update to the latest preview build via Windows Update.
- **Command not working:** Make sure you have run Command Prompt as Administrator.
- **Video not playing:** Try a different format (e.g., MP4/H.264). AVI, WMV, M4V, and MKV are also supported.
- **I want to disable the feature:** Run the same command with the `/disable` parameter:
    ```cmd
    ViVeTool.exe /disable /id:57645315
    ```

## 📜 License

This project is licensed under the **GPLv3** license, the same as the original ViVe project. See the `LICENSE` file for more information.

## 🙏 Acknowledgements

- Thanks to the [thebookisclosed/ViVe](https://github.com/thebookisclosed/ViVe) project and its developers, upon which this project is based.
- Thanks to all community members who discover and document hidden Windows features.
