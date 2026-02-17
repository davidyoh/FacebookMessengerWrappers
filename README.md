![Messenger Desktop Workarounds](./banner.jpg)

# FacebookMessengerWrapper(s)

Created Feb 17, 2026

Remember when Meta had a perfectly good desktop Messenger app? They killed it. 🪦 Messenger.com? On the chopping block too. 🔪 Apparently "a simple window where you send messages on your computer" was too radical a concept for a trillion-dollar company. 🤷

This repo is a collection of workarounds to get Messenger back as a standalone desktop app — a proper icon in your Dock, a clean browser window, no nonsense. Think of it as a poor man's Electron app, except it doesn't take up 4GB of disk space 💀, which already makes it better than most Electron apps.

## Mac/OSX

### Option 1: Using Automator, Chrome, and Bash

**Requirements:**

- OSX Tahoe (Older versions may work, depending on Automators backwards compatibility)
- Google Chrome

This Automator app simply runs this bash command

`open -na "Google Chrome" --args --app="https://www.facebook.com/messages/"`

**Download**

[v0.1.0-Messenger-OSX-Automator-Chrome.zip](https://github.com/davidyoh/FacebookMessengerWrappers/releases/download/osx/v0.1.0-Messenger-OSX-Automator-Chrome.zip)

**Installation**

1. Unzip, and drag the app into your **Application Folder.**
2. **Optional** - From application folder, and drag the Messenger icon to your dock for easy access

**Customize the Icon**

I preloaded my personal favorite icon for Messenger, but you can simply 

1. Find a `.png` or `.icns` image you want to use
2. Open the image in **Preview** and **Cmd+A** to select all, then **Cmd+C** to copy
3. Right-click the app → **Get Info**
4. Click the small icon in the **top-left corner** of the Get Info window (it'll get a blue highlight)
5. **Cmd+V** to paste

**Notes**
OSX Treats it as a Chrome window because it is just another Chrome window. That means it won't have a separate icon when it's running that's differentiated from Chrome because it *is* Chrome. From a storage perspective, this is more efficient than downloading a huge electron app. Another benefit is that you shouldn't have to login separately.

### Option 2: Using Webcatalog.io

Coming soon.

