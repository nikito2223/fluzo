# Fluzo
[![Build status](https://ci.appveyor.com/api/projects/status/eawhvp0h2215rqhj?svg=true)](https://ci.appveyor.com/project/Saektide/app)
[![DeepScan grade](https://deepscan.io/api/teams/9325/projects/11662/branches/175184/badge/grade.svg)](https://deepscan.io/dashboard/#view=project&tid=27105&pid=29693&bid=949440)


* [Download](https://github.com/nikito2223/fluzo/releases/latest)
* [Changelog](https://github.com/nikito2223/fluzo/blob/master/CHANGELOG.md#changelog)

### Creater this program
* https://github.com/e6Hub

## 🌟 Features
* Fetch, list (save temporally on your session) and download posts and pools
* SWF support (see [FAQ](#-faq) for how to enable it)
* Webm support
* Third party plugins support
* Blur explicit images
* DText support
* i18n support

## 📸 Showcase / Screenshot
<p align="center">
  <img src="assets/screenshots/e6HubShowcase1.gif">
</p>

## 🌎 Translation status
| Language name | Progress | Translated by |
| ------------- | -------: | ------------: |
| English       | 100%     | Saektide      |
| Spanish       | 100%     | Saektide      |
| Russiun       |   0%     | Saektide      |

## 🖥 Machine requirements
| Component | Minimum | Recommended |
| --------- | ------: | ----------: |
| RAM       | 2 GB    | 4 GB        |
| Storage   | ~150 MB | 250 MB      |
| CPU       |Any single core CPU | Any dual core CPU |
| Bandwidth Downstream | 1 MiB | 3 MiB |

## 🧪 OS Supported
> **Note** We release only 64 bits versions

| OS Name    | Status | Type |
| ---------- | :----: | ---: |
| Windows 7  |✔<sup>1</sup>     | .exe |
| Windows 8  |✔     | .exe |
| Windows 10 |✔     | .exe |
| Debian     |✔     | .AppImage |
| Fedora     |✔     | .AppImage |
| Arch       |✔     | .AppImage |
| macOS      |⚠     | .dmg |

* ✔ Supported
* ❌ Not supported but can compile it
* ⚠ Not tested yet

1. A clean installation of Windows 7 (w/o recent updates) have the black screen issue. Learn more about [this Electron issue](https://github.com/electron/electron/issues/19569).

## 💾 Development build
### 🚧 Requirements
* Node.js ( v20 or above )
* Git
### 💽 Clone
```
git clone https://github.com/e6Hub/app.git
cd app
```

### 📚 Install deps with NPM
```
npm i
```
or with Yarn
```
yarn
```

## 🛠 Compile
You can now start to write code. Once you done, compile it to make sure if it's work correctly.
```
yarn dev
```
or
```
npm run dev
```

## 📦 Build
It works? Great! now you can build it!
```
yarn build
```
or
```
npm run build
```

## ❓ FAQ

### Can i download multiple pools/posts at the same time?
You can download only one pool at the time. Fluzo will mark posts (and pools) as "pending" to avoid saturate rufik's servers.

### Can i see blacklisted posts on this app?
No, Fluzo's global blacklist works on server-side.

### Fluzo have telemetry?
No. And we wont include that feature on our app.

### I want to report a bug or give my feedback, where should i go?
Since the app is discontinued, you cannot report bugs and submit your feedback.

### There's premium functions in this app?
No, all the app (and everything on there) is free and open source.

