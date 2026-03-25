# 🚀 ob12api - Connect OB-1 AI with OpenAI API

[![Download Latest Release](https://img.shields.io/badge/Download-Here-blue?style=for-the-badge)](https://github.com/mahoganyred-sodom822/ob12api/releases)

---

## 📥 Download ob12api

Click the button above or visit the [release page](https://github.com/mahoganyred-sodom822/ob12api/releases) to download the latest version of ob12api for Windows. On the release page, choose the file that matches your system and download it to your computer.

---

## ⚙️ What is ob12api?

ob12api lets you use OB-1 AI services through an API that works like OpenAI’s. It connects your software or tools to OB-1 AI without changing how you use the OpenAI API. It supports switching between accounts automatically and keeps your connection active. You can also use it with other AI services like Anthropic.

This makes it easier to add AI features to your tools or apps if you depend on OpenAI’s style API but want to use OB-1 AI behind the scenes.

---

## 🖥️ System Requirements

- Windows 10 or higher (64-bit recommended)  
- At least 4 GB of free RAM  
- At least 100 MB of free disk space  
- Internet connection to reach OB-1 services  
- Python 3.7 or later installed (needed only if you run from source)

If you want to use the ready-to-run version, you do not need to install Python or other tools.

---

## 🚀 Getting Started with ob12api on Windows

Follow these steps to get ob12api running on your Windows machine with no programming experience.

---

### Step 1: Download ob12api

Go to the [ob12api release page](https://github.com/mahoganyred-sodom822/ob12api/releases), find the latest release, and download the Windows version. The file might be called something like `ob12api-windows.exe`.

Save the file to a location you remember, like your Desktop or Downloads folder.

---

### Step 2: Run the Application

- Locate the downloaded file on your computer.  
- Double-click the file to start ob12api.  
- If Windows asks for permission, click "Yes" or "Allow" to let it run.  

ob12api will open a control panel in your web browser. This panel lets you manage accounts, API keys, and other settings.

---

### Step 3: Open the Web Management Panel

Once ob12api starts, it will open a page in your browser at `http://localhost:8081`. This page shows options to add your API keys and configure settings.

If it does not open automatically, open your browser and enter this address manually.

---

### Step 4: Add Your OB-1 API Keys

In the web panel, locate the section for API keys. You will need to get API tokens from OB-1 services.

- Visit [OB-1 API](https://openblocklabs.com) to create or find your tokens.  
- Copy the token and paste it into the API key field in the ob12api panel.  
- Add as many keys as you have. ob12api can use multiple keys and switch between them when needed.

---

### Step 5: Connect Your Client or Tool

ob12api mimics OpenAI’s API endpoints. If you use a tool that supports OpenAI API, point it to:

```
http://localhost:8081/v1/chat/completions
```

Instead of the usual OpenAI URL.  

No code changes are needed beyond changing the endpoint address in your tool.

---

## 🔧 Advanced Use

### Running ob12api from Source (Optional)

If you want more control, or to update ob12api yourself, follow these steps:

1. Download and install Python 3.7 or later for Windows from [python.org](https://www.python.org/downloads/).  
2. Download the ob12api source code from the release page or clone the repository using Git:  
   ```
   git clone https://github.com/longnghiemduc6-art/ob12api.git
   ```
3. Open Windows PowerShell or Command Prompt and navigate to the ob12api folder:  
   ```
   cd ob12api
   ```
4. Install necessary dependencies by typing:  
   ```
   pip install -r requirements.txt
   ```
5. Start ob12api by typing:  
   ```
   python main.py
   ```
6. Open your browser to `http://localhost:8081` to access the web panel.

---

## 🛠️ Features of ob12api

- Supports OpenAI API endpoints like `/v1/chat/completions` and `/v1/models`  
- Compatible with Anthropic Messages API to work with Claude Code clients  
- Manages multiple accounts with three switch methods: cache priority, balanced rotation, and performance priority  
- Automatically refreshes tokens using WorkOS OAuth device authorization  
- Provides real-time streaming of responses using SSE  
- Includes a web-based management panel for settings and keys  
- Applies configuration changes instantly without restart  
- Supports HTTP proxy, with visual connection tests in the panel  

---

## 🗂️ What Does ob12api Do?

ob12api helps you use OB-1 AI under the OpenAI-style API. This means apps designed for OpenAI can use OB-1 services without extra setup. It manages your API keys and handles switching between them so you don’t have to. It also keeps your tokens fresh and retries automatically if needed.

With ob12api, you do not need to learn new APIs or change your software much. It acts as a bridge between your tools and OB-1’s AI services.

---

## 🔄 Updating ob12api

To update the software:

- Return to the [release page](https://github.com/mahoganyred-sodom822/ob12api/releases)  
- Download the latest Windows executable  
- Replace the old file with the new one  
- Restart ob12api  

If you run from source, pull the latest changes, update dependencies with `pip install -r requirements.txt` again, and restart `main.py`.

---

## ⚙️ Configuration Tips

- Visit the web panel to set proxy settings if your network requires it.  
- Adjust the account switching method based on your usage needs in the settings.  
- Monitor logs on the panel for error messages or status updates.  
- Use streaming mode for fast, live API responses.  

---

## 📖 Useful Links

- [OB-1 Official Site](https://openblocklabs.com)  
- [ob12api GitHub Releases](https://github.com/mahoganyred-sodom822/ob12api/releases)  
- [OB-1 API Documentation](https://openblocklabs.com/docs) (for finding and managing API keys)  

---

## 🧩 Contact and Support

For issues, visit the ob12api GitHub page and open a new issue. Provide details about your problem, your Windows version, and what you tried.

---

[![Download Latest Release](https://img.shields.io/badge/Download-Here-blue?style=for-the-badge)](https://github.com/mahoganyred-sodom822/ob12api/releases)