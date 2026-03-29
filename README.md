# N8N Localy Run

# n8n Local Setup Guide

#### Install n8n on your computer for free — with paid features unlocked

```
n PREREQUISITES: Windows / Mac / Linux + Internet connection + 5 minutes
```
## 1.  Install Node.js

##### n8n runs on Node.js, so we need to install it first. This is a one-time setup.

##### n What to do:

1. Open your browser
2. Go to nodejs.org
3. Click the LTS (Long Term Support) version — it's the stable one
4. Download the installer for your OS (Windows / Mac / Linux)
5. Run the installer — click Next through all steps, keep defaults

```
n TIP: Always pick the LTS version, not Current. LTS is stable and tested.
```
##### Verify Installation:

##### Open Command Prompt (Windows) or Terminal (Mac/Linux) and type:

##### node -v

##### If you see a version number like v20.x.x — Node.js is installed successfully.


##### n What you should see:

```
$ node -v
v20.18.1 ← Any version 18+ is fine
$ npm -v
10.8.2 ← npm comes bundled with Node.js
```
### 2.  Install n8n

##### One command is all it takes. This installs n8n globally on your system.

##### Open Command Prompt / PowerShell / Terminal and run:

##### npm i n8n -g

##### n Breaking it down:

```
npm → Node Package Manager (comes with Node.js)
i → Short for 'install'
n8n → The package we're installing
-g → Install globally (so you can use it from anywhere)
```
##### Wait for the installation to finish. It may take 1-2 minutes, depending on your internet speed.

```
n ERROR? If you get a permission error on Mac/Linux, run: sudo npm i n8n -g
```
### 3.  Start n8n


##### Launch n8n for the first time. It will set up everything automatically.

##### In the same terminal, run:

##### n8n start

##### This takes a minute the first time. Once it's ready, you'll see a message with a URL.

##### n What you should see in the terminal:

```
Editor is now accessible via:
http://localhost:
Press 'o' to open in browser
```
##### Now open your browser and go to:

##### localhost:

##### You'll see the n8n signup screen. Create your account — this is local, only on your machine.

```
n NOTE: n8n has no desktop icon. You always start it via a terminal command and open it in
your browser.
```
### 4.  Unlock Paid Features (Free!)

##### n8n offers a free community license that unlocks paid features like execution history, debug mode,

##### and more.


##### n What to do:

1. Inside n8n, go to Settings (bottom-left gear icon)
2. Click on Community or License
3. Enter your email address
4. Click the 'Send Me' button
5. Check your email — you'll receive a license key

##### If you get an activation error, run this in your terminal:

##### n8n license: activate YOUR_LICENSE_KEY

##### Then restart n8n:

##### n8n start

```
n DONE! Paid features are now unlocked. You get execution history, debug mode, and
more — all free.
```
## Quick Reference Card

###### ACTION COMMAND

```
Install n8n npm i n8n -g
```
```
Start n8n n8n start
```
```
Open n8n in the browser at localhost:
```
```
Update n8n npm update n8n -g
```
```
Check Node version node -v
```
```
Activate license n8n license:activate KEY
```
```
Stop n8n Ctrl + C (in terminal)
```

## Troubleshooting

##### n Problem: "npm" is not recognized

```
Fix: Node.js not installed properly. Reinstall from nodejs.org and restart your terminal.
```
##### n Problem: Permission denied (Mac/Linux)

```
Fix: Use sudo npm i n8n -g to install with admin permissions.
```
##### n Problem: n8n won't start

```
Fix: Make sure no other app is using port 5678. Or run: n8n start --port=
```
##### n Problem: License activation error

```
Fix: Copy the exact key from email. Run n8n license:activate KEY then restart.
```
##### n Problem: Page won't load in browser

```
Fix: Make sure terminal still shows n8n running. Don't close the terminal window.
```
```
@fullstackparody · Learning AI Automation · March 2026
```

