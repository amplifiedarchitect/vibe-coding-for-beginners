# Vibe Coding For Beginners

The exact prompts and commands from every video in the **Vibe Coding For Beginners** playlist by [Amplified Architect](https://www.youtube.com/@AmplifiedArchitect).

You direct, the AI builds. Each video is a complete follow-along recorded on a real machine: copy a prompt, paste it into your AI assistant, and build along. You don't need to know how to code.

**Watch the playlist:** https://www.youtube.com/playlist?list=PLLRVNOCjAuec

| # | Video | What you build |
|---|---|---|
| 1 | [How to Start Vibe Coding for FREE! Easy VS Code + GitHub Copilot Setup for Beginners (2026)](https://youtu.be/EryUxT0FQbE) | The free setup on Windows (Ubuntu on WSL, VS Code, GitHub Copilot's free plan) and a to-do list app |
| 2 | [How to Vibe Code a Game with ONE Prompt! (FREE with GitHub Copilot, No Coding)](https://youtu.be/9-KWuFBE6gQ) | A neon space shooter from one prompt, a real bug fixed, then a boss fight |
| 3 | [Vibe Coding Basics Nobody Explains! What node_modules, package.json and npm ACTUALLY Do](https://youtu.be/iIdb50QHiIk) | A neon beat maker, and what an app is made of: dependencies, the dev server, the production build |
| 4 | [Web App vs Native App: Don't Build the WRONG One! (PWA Explained for Beginners)](https://youtu.be/EhQKgI5RnQQ) | A kaleidoscope drawing app you can install and use offline, then wrapped as an Android project |
| 5 | [How to Use Claude Code in VS Code: Build an AMAZING 3D Game with Plan Mode!](https://youtu.be/HwdwHNtn0EE) | Skyhold, a 3D tower defense game, built by Claude Code from one plan |
| 6 | [How to Set Up and Secure a VPS the EASY Way! Claude Code Does It for You (SSH Keys, Firewall)](https://youtu.be/PuJtWFCcjj8) | Your own server on the internet, secured by Claude over SSH |
| 7 | [How to Host a Website on a VPS with Claude Code! Your Game LIVE on Your Own Domain (FREE HTTPS)](https://youtu.be/WfWYY4RFxWA) | Skyhold online with HTTPS on your own server |
| 8 | [How to use a local AI Agent FREE on an 8 GB GPU: Ollama + Claude Code for Beginners](https://youtu.be/8B9O0B-Pl3c) | A free AI agent that runs on your own graphics card with Ollama, and a fireworks show it builds and then fixes |
| 9 | [Git and GitHub for Beginners: NEVER Lose Your Work Again! (Claude Code Runs Every Command)](https://youtu.be/1aEvIcyBDmg) | Save points for your project with Git and GitHub, used for real while Claude Code builds a website with an email signup list and member logins |

Videos 1 to 4 use GitHub Copilot's free plan in VS Code. Videos 5 to 7 and video 9 use Claude Code (a paid plan). Video 8 runs a local model with Ollama, free on your own graphics card.
Play the game from videos 5 and 7: https://tdgame.amplifiedarchitect.com

## 1. How to Start Vibe Coding for FREE! Easy VS Code + GitHub Copilot Setup for Beginners (2026)

Watch: https://youtu.be/EryUxT0FQbE

The free setup on Windows (Ubuntu on WSL, VS Code, GitHub Copilot's free plan) and a to-do list app.

**Prompts**

```text
Build me a simple to-do list website with a clean design that I can open in my browser.
```

```text
Add a dark mode.
```

```text
Make the buttons bigger.
```

```text
Save my tasks so they're still there tomorrow.
```

## 2. How to Vibe Code a Game with ONE Prompt! (FREE with GitHub Copilot, No Coding)

Watch: https://youtu.be/9-KWuFBE6gQ

A neon space shooter from one prompt, a real bug fixed, then a boss fight.

**Prompts**

```text
Build me a neon space shooter game that runs in my browser. Make it glow, add explosions and sound effects, keep score with a saved high score, and make it work with the keyboard or touch on a phone.
```

```text
When I shoot, the bullets go down instead of up, so I can't hit anything. Please fix it.
```

```text
Add a boss fight after the first wave, and missile upgrades that drop from destroyed enemies.
```

## 3. Vibe Coding Basics Nobody Explains! What node_modules, package.json and npm ACTUALLY Do

Watch: https://youtu.be/iIdb50QHiIk

A neon beat maker, and what an app is made of: dependencies, the dev server, the production build.

**Prompts**

```text
Build me a neon beat maker that runs in my browser. Make it a Vite project that uses Tone.js for the sound. Give it a glowing step sequencer for drums and bass that pulses to the music, load a catchy beat so it plays as soon as I press play, and add tempo and volume controls.
```

```text
Make it purple and pink.
```

**Commands**

Install Node.js and npm (once):

```bash
sudo apt update && sudo apt install -y nodejs npm
```

Check Node.js:

```bash
node -v
```

Start the dev server:

```bash
npm run dev
```

Production build:

```bash
npm run build
```

Compare the folder sizes:

```bash
du -sh node_modules dist
```

Try the production build:

```bash
npm run preview
```

## 4. Web App vs Native App: Don't Build the WRONG One! (PWA Explained for Beginners)

Watch: https://youtu.be/EhQKgI5RnQQ

A kaleidoscope drawing app you can install and use offline, then wrapped as an Android project.

**Prompts**

```text
Build me a neon kaleidoscope drawing app that runs in my browser. Everything I draw with my finger or mouse gets mirrored into a glowing mandala, with colors that shift as I draw. Add a clear button and a way to save my drawing as an image. Make it a Vite project, and make it installable as an app that works offline, so I can put it on my phone's home screen.
```

```text
Turn this into a native Android app with Capacitor, so I can open it in Android Studio. Just set up the project, don't build it.
```

**Commands**

Make the finished version:

```bash
npm run build
```

Run it on your computer (then install it from the browser's address bar):

```bash
npm run preview
```

## 5. How to Use Claude Code in VS Code: Build an AMAZING 3D Game with Plan Mode!

Watch: https://youtu.be/HwdwHNtn0EE

Skyhold, a 3D tower defense game, built by Claude Code from one plan.

**Prompts**

```text
Build me a 3D tower defense game in my browser with Three.js and Vite. Set it on a floating island at golden hour, with a winding stone path, grassy hills, rocks, trees and a waterfall pouring off the edge, and make it look like a polished indie game: soft shadows, warm light, crisp and sharp at full screen resolution, with no blurry glow. I build towers on the grass beside the path: a cannon with explosive splash damage, a frost tower that slows enemies, and a laser that locks onto one target, each with its own model and three upgrade levels I can buy. Send ten waves along the path with fast runners, armored tanks, flying drones and a giant boss on the last wave, all with health bars. Add gold for every kill, lives, a wave counter, a start wave button, a speed-up button, satisfying hit and explosion effects, and a sound for every shot and hit.
```

```text
When the golem dies, make it crumble into boulders that tumble off the edge of the island.
```

```text
When you're done, add a title screen with the game's name and a Play button.
```

```text
Add a pause menu. Pressing P or Escape pauses the game and shows Resume, Restart and a sound toggle, styled like the title screen.
```

**Commands**

Install the Claude CLI (Linux / WSL):

```bash
curl -fsSL https://claude.ai/install.sh | bash
```

If the installer says ~/.local/bin is not in your PATH:

```bash
echo 'export PATH="$HOME/.local/bin:$PATH"' | tee -a ~/.bashrc && source ~/.bashrc
```

Start Claude in your project folder:

```bash
claude
```

Run the game, then open the address it shows:

```bash
npm run dev
```

## 6. How to Set Up and Secure a VPS the EASY Way! Claude Code Does It for You (SSH Keys, Firewall)

Watch: https://youtu.be/PuJtWFCcjj8

Your own server on the internet, secured by Claude over SSH.

**Prompts**

```text
Make me an SSH key for my new server, with no passphrase, and copy the public key to my clipboard so I can paste it into Spaceship.
```

```text
My new Ubuntu server is ready at [your server's IP address], SSH port 22022, user root, with the key you just made. Add it to my SSH config as myserver. Then secure it: a new user named architect who can use sudo without a password, SSH with keys only and no root login, a firewall that only lets in SSH and web traffic, automatic security updates, and fail2ban. Log in as the new user before you turn off root, so I can't get locked out. When you're done, write down what you did in SERVER.md.
```

**Commands**

Log in to your server as the new user:

```bash
ssh myserver
```

Root should now be turned away:

```bash
ssh root@myserver
```

## 7. How to Host a Website on a VPS with Claude Code! Your Game LIVE on Your Own Domain (FREE HTTPS)

Watch: https://youtu.be/WfWYY4RFxWA

Skyhold online with HTTPS on your own server.

**Prompts**

```text
Get Skyhold ready to put online. Make the ?debug shortcuts work only while developing, never in the production build. Make it play well on a phone held sideways, with taps instead of clicks and buttons big enough for a finger. Then make a fresh production build and check that it works.
```

```text
Put Skyhold online at tdgame.amplifiedarchitect.com on myserver. The DNS record already points there. Install Caddy for automatic HTTPS, upload the production build, and add an npm run deploy command that builds the game and uploads the new version.
```

```text
Add a line under the title on the title screen that says Now playing online.
```

**Commands**

Build and upload a new version:

```bash
npm run deploy
```

## 8. How to use a local AI Agent FREE on an 8 GB GPU: Ollama + Claude Code for Beginners

Watch: https://youtu.be/8B9O0B-Pl3c

A free AI agent that runs on your own graphics card with Ollama, and a fireworks show it builds and then fixes.

**Prompts**

```text
What graphics card does this computer have?
```

```text
Build a fireworks show that runs in my browser, in a single file called index.html. A dark night sky with stars, rockets that launch where I click and burst into bright colorful sparks with trails that fall with gravity, and an automatic show when I'm not clicking. Make it crisp and vivid, no blur filters.
```

```text
The fireworks freeze right after they start. The browser console says: Uncaught IndexSizeError, the radius provided is negative, at index.html line 114. Fix it.
```

```text
In index.html, the firework bursts are too small and fade too fast. Make every burst about three times bigger with twice as many sparks, brighter colors, and trails that glow longer. Only change the file.
```

**Commands**

Install Ollama in Ubuntu:

```bash
sudo apt install zstd
curl -fsSL https://ollama.com/install.sh | sh
```

Download the model and chat with it:

```bash
ollama pull ornith:9b
ollama run ornith:9b
```

Inside the chat: a bigger context, saved as your own version of the model:

```text
/set parameter num_ctx 32768
/save ornith-agent
/bye
```

Open Ollama's menu and launch the agent:

```bash
ollama
```

Open the page the agent built (from Ubuntu, in your Windows browser):

```bash
explorer.exe index.html
```

## 9. Git and GitHub for Beginners: NEVER Lose Your Work Again! (Claude Code Runs Every Command)

Watch: https://youtu.be/1aEvIcyBDmg

Save points for your project with Git and GitHub, used for real while Claude Code builds a website with an email signup list and member logins.

**Prompts**

```text
Build the website for my brand, Amplified Architect. Read brand.md first: it has our colors, fonts, wording and video list, and the brand folder has our logo and video thumbnails. Use Node.js with Express, because we'll add an email signup list and member logins next. Start with the landing page: a bold hero with our headline, what you'll learn, our videos as cards with their thumbnails, our game Skyhold, and a footer. Make it look like a premium product launch page: dark, crisp and confident, with big type, generous spacing, subtle motion and hover effects, and make it work just as well on a phone. No blur or glow filters over text. Don't open a browser. When it's done, start it and tell me the address.
```

```text
Set up Git for this project and save everything as the first save point.
```

```text
Now add the email signup list to the landing page. When someone enters their email, save it in a SQLite database file in a data folder and show a friendly confirmation right on the page. Refuse anything that isn't an email address, and don't add the same address twice. We'll send real confirmation emails later, when the site goes live.
```

```text
What changed since the last save point? In plain words, and keep it short.
```

```text
Save this as the next save point.
```

```text
Now add member logins. People create an account with their email and a password, then log in and log out. Members get a private page called My Path, with our eight videos as steps they can check off and a progress bar, saved to their account. Hash the passwords, keep the session secret in a .env file, and use the same database.
```

```text
Save this as the next save point, and push it to GitHub.
```

```text
I deleted the views folder by accident. Bring it back from the last save point.
```

**Commands**

Is Git there? (Ubuntu comes with it):

```bash
git --version
```

Tell Git who you are, once per computer (the email: your private address from GitHub, Settings, Emails):

```bash
git config --global user.name "Your Name"
git config --global user.email "your-private-address@users.noreply.github.com"
```

---

The narration in the videos uses an AI voice. Every step was recorded on a real machine and checked before publishing. The prompts here are free to copy and change.
