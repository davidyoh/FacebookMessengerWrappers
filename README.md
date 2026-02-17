# FacebookMessengerWrapper
Created Feb 17, 2026

Don't you just hate how Meta got rid of their cilents, and is now removing Messenger.com? This repository will contain varous workarounds to have a simple icon and a simplified browser window to access Messenger. 

## Mac/OSX

### Option 1: Using Automator, Chrome, and Bash

**Requirements:**

- OSX Tahoe (Older versions may work, depending on Automators backwards compatibility)
- Google Chrome

This Automator app simply runs this bash command

`open -na "Google Chrome" --args --app="https://www.facebook.com/messages/"`

**Installation**

1. Download here: https://github.com/davidyoh/FacebookMessengerWrappers/blob/main/download/Messenger.zip
2. Unzip, and drag the app into your Application Folder.
3. Optional - Open the application folder, and drag the Messenger icon to your dock for easy access

**Limitations:**
OSX Treats it as a Chrome window. That means it won't have a separate icon when it's running that's differentiated from Chrome because it is Chrome.

### Option 2: Using Webcatalog.io

Coming soon.

