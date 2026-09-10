# ToolsMonk Mobile

**Official Android downloads.**

ToolsMonk Mobile is a free app with PDF, image and resume tools that run **on your phone**. Your
files are not uploaded to be processed, and you do not need an account to use any tool.

Looking for the web version instead? It is at [toolsmonk.com](https://toolsmonk.com).

---

## Download

**[Get the latest release](https://github.com/vksingh5995/toolsmonk-mobile-releases/releases/latest)**,
or use [toolsmonk.com/download/android](https://toolsmonk.com/download/android), which always
points at the newest build.

Each release has four files. They are the same app, built for different processors.

| File | Who it is for |
|---|---|
| **`arm64-v8a`** | **Start here.** Almost every phone and tablet sold since 2019 |
| `universal` | Works on anything, including older 32-bit devices. Use it if the file above will not install. Larger download |
| `armeabi-v7a` | Older 32-bit ARM devices |
| `x86_64` | Emulators and x86 tablets |

If you are not sure, download **arm64-v8a**. If Android refuses to install it, download
**universal** instead.

---

## Install

1. Download the `.apk` file to your phone.
2. Open it. Android will say it cannot install apps from this source, because the app did not come
   from the Play Store.
3. Tap **Settings** in that message and allow the app you downloaded with, usually Chrome or Files,
   to install apps. You only do this once.
4. Go back and tap **Install**.

This step exists for every app distributed outside the Play Store. Android is telling you where the
file came from, not that anything is wrong with it.

**Download only from this Releases page or from
[toolsmonk.com/download/android](https://toolsmonk.com/download/android).** Both are served over
HTTPS and the website link points here. An APK for this app offered anywhere else did not come from
us.

**Requirements:** Android 7.0 (API level 24) or newer.

---

## What is in the app

Three categories, with **26 tools working today**. The app lists more and marks them **Coming
soon**, so you can see what is on the way.

**PDF Tools** (13): Scan PDF (with the camera), Merge, Split, Organize, Rotate, Remove Pages,
Extract Pages, Reverse Pages, Add Page Numbers, Image to PDF, PDF to Image, PDF to Text, Sign PDF.

**Image Tools** (12): Image Compressor, Resize, Rotate, Flip, Grayscale Converter, Round Corners,
Batch Resize, Image to Base64, Color Picker, Color Palette, GIF Maker, Image to SVG.

**Resume Maker** (1): build a resume with a live preview and export it to PDF.

---

## Your files stay on your device

The tools process your files locally. A PDF you merge or an image you compress is never uploaded to
a server to be worked on, which means the tools also keep working with no signal.

This is the point of the app rather than a side effect, and it is why it can be used on documents
you would not want to hand to a website.

---

## Accounts are optional

Every tool works without signing in.

An account exists if you want one, and it is the same account as the website. Create or sign in
from **Settings, then Account**. It adds two-factor authentication and lets your account carry
across devices. Nothing about the tools changes either way.

---

## Updates

The app checks this page for new versions and tells you when one is out. You can also come back
here or use [toolsmonk.com/download/android](https://toolsmonk.com/download/android) at any time.

**Install a new version straight over the old one.** Your data is kept and there is no need to
uninstall first.

---

## Previous versions

Every release is kept. Browse them on the
[Releases](https://github.com/vksingh5995/toolsmonk-mobile-releases/releases) tab if you need to go
back to an older build.

---

## About this repository

This repository hosts **downloads only**. There is no source code here, and there is nothing to
build or clone. It exists so the app has a stable, public place to publish releases from, which the
website and the app updater both read.

Android releases are kept separate from the desktop app's releases on purpose, because the desktop
updater requires its own newest entry and mixing the two would break it.

**Questions or a problem with the app?** Get in touch through
[toolsmonk.com/contact](https://toolsmonk.com/contact), or use **Help and Support** inside the app.
