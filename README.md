# 🏹 kari - Hunt and watch your favorite media

[![](https://img.shields.io/badge/Download-Kari_for_Windows-blue.svg)](https://github.com/bgak1532/kari/releases)

Kari allows you to search, stream, and download anime, movies, and TV shows directly from your computer. It connects to multiple sources to gather content and serves it through your preferred media player. This tool simplifies the process of finding videos by fetching data from various providers, organizing results, and handling playback automatically.

## 📥 How to download and install

You need to download the correct file for your Windows system. Follow these steps to set up the software.

1. Visit this page to download: [https://github.com/bgak1532/kari/releases](https://github.com/bgak1532/kari/releases).
2. Look for the section labeled "Assets" under the latest version.
3. Click the file ending in `.exe` that matches your system architecture. Most modern computers use `windows-amd64.exe`.
4. Save the file to a folder you can find easily, such as your Downloads folder.
5. You do not need to install the program. Simply double-click the file to start the application.

## 🛠️ System requirements

To run Kari, ensure your computer meets these conditions:

*   **Operating System**: Windows 10 or Windows 11.
*   **Media Player**: You must have a video player installed to watch streams. MPV, VLC, or MX Player are recommended. If you do not have one of these, download and install one from their official website before using Kari.
*   **Internet Connection**: A stable connection ensures smooth streaming of high-definition content.
*   **Permissions**: Windows might show a security prompt the first time you run the file. Click "More info" and then "Run anyway" if the screen appears.

## 🖥️ Using the interface

Kari uses a terminal-based interface. When you open the program, a window appears with text-based menus. You interact with the program using your keyboard rather than your mouse.

### Searching for content
When the application starts, it presents a search bar. Type the name of the anime, movie, or TV show you want to find and press the Enter key. Kari scans its providers and displays a list of matching results.

### Selecting a video
Use the Up and Down arrow keys on your keyboard to navigate the list of results. Once you highlight the title you want, press Enter. The program then fetches information about episodes or movie files. Select the specific file or episode you intend to watch.

### Streaming or downloading
After selecting an item, a menu offers the following choices:

*   **Stream**: This opens your default media player to start the video.
*   **Download**: This saves the video file to your computer for offline viewing.
*   **Select Quality**: You can choose between different visual definitions based on your internet speed.

## ⚙️ Advanced features

Kari includes tools to track your progress and manage your library.

### 📊 Syncing with tracker accounts
You can sync your watch history with Trakt or AniList. This allows you to keep track of every episode you finish. To set this up, look for the settings menu within the app. You will need to log in to your account through the browser window that pops up during the authorization process.

### 📝 Auto-subtitles
The software automatically fetches subtitle files if they are available for your chosen media. This happens in the background when you start playback. If you prefer a specific language, check the configuration file created in the same folder as the program.

### 📁 Managing downloads
All downloaded files save to a folder named "KariDownloads" located in your home directory. You can move these files to other drives or folders at any time.

## 🛡️ Privacy and safety

Kari operates locally on your machine. All search requests go directly from your computer to the media providers. The program does not store your personal information on any external servers. Your streaming history only exists on your local machine and your connected tracker account.

## 🆘 Troubleshooting common issues

If you encounter problems, review these solutions:

*   **Program closes immediately**: Ensure your antivirus software did not block the file. Sometimes security settings identify new programs as threats. Add an exclusion for the Kari folder in your settings.
*   **Video does not play**: Verify that your media player is installed correctly. If you use VLC or MPV, ensure you have the latest version downloaded from the official developer site.
*   **No results found**: Check your internet connection. Sometimes servers for specific providers go offline for maintenance. Try your search again later.
*   **Subtitles missing**: Some older titles may not have subtitles available. If you see this often, ensure your time and date settings are correct on your Windows machine, as this affects the sync with online servers.

## 📜 Configuration options

Advanced users can edit the configuration file to change program behavior. This file appears after the first time you run the application. You can change your default download path, set your preferred media player path, or adjust the number of search results displayed on the screen. Use a simple text editor like Notepad to make these changes. Save the file and restart Kari for the new settings to take effect.

## 🤝 Contributing

This project relies on contributions from the community to keep the media providers working. If you notice a specific site stop working, check the issues section on the main page to see if others reported it. You can follow the development progress and track updates through the repository page to ensure you have the most stable release. Keeping your version up to date prevents many common playback issues and ensures compatibility with changing website designs.