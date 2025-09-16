# WSL + Ollama Installer (Windows)

This repository provides a simple **`.bat` script** that installs **Windows Subsystem for Linux (WSL)** with **Ubuntu** and then installs **[Ollama](https://ollama.com/)** inside WSL.

## 🚀 How It Works
The batch file:
1. Installs **WSL** with Ubuntu (`wsl --install -d Ubuntu`).
2. Waits briefly for setup.
3. Runs the official Ollama install script inside Ubuntu.

## 📋 Requirements
- Windows 10 (21H2 or later) or Windows 11.
- Administrator privileges to run the script.
- Internet connection for downloading WSL and Ollama.

## 🔧 Usage
1. Download `install_wsl_ollama.bat`.
2. Right-click the file → **Run as Administrator**.
3. If Windows asks you to restart, do so and **run the script again**.
4. Once finished, open Ubuntu via WSL and test:
   ```bash
   ollama run llama2
