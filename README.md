# Mac Setup Brewfile

This is a simple and efficient Brewfile designed to help automate the setup of Mac laptops at StoryCorps. Instead of manually downloading common apps like Google Chrome, Zoom, and Slack one by one, this Brewfile lets you install everything with a single command — saving time and reducing setup errors.

Whether you're configuring a new MacBook or re-imaging a machine, this file helps ensure consistency across devices.

📦 What's included?

This Brewfile currently installs:

Google Chrome

Zoom

Slack

(More apps can easily be added as needed.)

## How to use (in your terminal)

1️⃣ Install Homebrew (if you don’t have it already): 

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"


2️⃣ Download the Brewfile

curl -O https://raw.githubusercontent.com/jalejandro23/downloading-applications/main/Brewfile


3️⃣ Run the Brewfile to install all apps:

brew bundle --file=Brewfile
