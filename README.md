# 💻 Scriptcord (Vencord Fork for Scriptkiddies)

> *Modded Discord for people who wana do some funny*  

![](https://img.shields.io/github/package-json/v/CreeperKing3532/Vencord-fork?style=for-the-badge&label=version&color=blueviolet)  
[![Join Support Discord](https://img.shields.io/discord/1138499236202944522?style=for-the-badge&label=Need%20Help%3F&color=5865F2)](https://discord.gg/D9uwnFnqmd)

---

## 🧠 What Is This?

A fork of [Vencord](https://github.com/Vendicated/Vencord), but tweaked for the scriptkiddies.

---

## 🔧 How to Install (Step by Step)

### ✅ Step 1: Download the Fork

You’ve got two options:

**Option A: Download the ZIP**
1. Click the green `Code` button at the top of this repo
2. Click `Download ZIP`
3. Right-click the ZIP, extract it somewhere you’ll remember (like `Desktop` or `Documents`)

**Option B: Use Git (if you’re fancy)** (ONLY WORKS IF YOU GOT GIT INSTALLED)
1. Open **Command Prompt** (press `Win + R`, type `cmd`, hit Enter)
2. Paste this and press enter:
   ```bash
   git clone https://github.com/CreeperKing3532/Vencord-fork.git
   cd Vencord-fork
   ```

---

### ✅ Step 2: Open the Folder in Terminal

**If you downloaded ZIP:**

1. Go into the folder where you extracted the ZIP
2. Right-click somewhere *inside* the folder (not on a file)
3. Click **“Open in Terminal”** or **“Open in Command Prompt”**

If you **don’t** see that, open **Command Prompt** manually and type:

```bash
cd C:\Path\To\Your\Folder
```

Replace `C:\Path\To\Your\Folder` with the actual folder path (you can copy it from the address bar in File Explorer).

---

### ✅ Step 3: Install Node.js and pnpm

You need Node.js and a package manager called `pnpm`.

1. Go to [https://nodejs.org](https://nodejs.org)  
   Download the **LTS version**, install it, then restart your PC just to be safe.

2. Then in **Command Prompt**, run this:

```bash
npm install -g pnpm
```

---

### ✅ Step 4: Build the Mod

With Command Prompt open in the folder (you should see something like `C:\Users\You\Desktop\Vencord-fork>`), type:

```bash
pnpm install
pnpm build
```

Let it finish doing its thing. It might take a bit.

---

### ✅ Step 5: Inject Into Discord

After it's built, run:

```bash
pnpm inject
```

Discord will restart automatically, and boom — you’re modded. (you may need to manually open discord)

---

## ❌ How to Uninstall (if you get cold feet)

Just run this command in the same folder:

```bash
pnpm uninject
```

---

## ⚠️ Important Notes

- Works on **Desktop Discord only** (Stable / Canary / PTB)
- Don't post screenshots in servers that hate client mods
- If Discord breaks or updates, just rerun:
  ```bash
  pnpm build
  pnpm inject
  ```

---

## 💬 Support

For help, plugin dev stuff, or just to ask dumb questions (respectfully), join the [Vencord Support Server](https://discord.gg/D9uwnFnqmd).

---

## 🧼 Legal Stuff

> This is **not** affiliated with Discord Inc. at all.  
> Use at your own risk. Modding the client breaks [Discord’s Terms of Service](https://discord.com/terms), but they don’t usually care unless you do something dumb.
