# Desktop Naotu (DesktopNaotu) [![Join the chat at https://gitter.im/DesktopNaotu/DesktopNaotu](https://badges.gitter.im/DesktopNaotu/DesktopNaotu.svg)](https:// gitter.im/DesktopNaotu/DesktopNaotu) [![Join the desktop version of the brain map QQ group: 330722928](https://pub.idqqimg.com/wpa/images/group.png)](https://shang.qq. com/wpa/qunwpa?idkey=cbd6fbc32adbe20c99c005bc559ec45bf3c9bfe581f9226ed14bd0951ae95739)

## 1. Chinese introduction

### Software introduction [--> **English introduction**](README.md)

The desktop version of Mind Map is a localized version based on Baidu Mind Map, which helps you to use the Mind Map tool even in the absence of an Internet environment.

### how to download

-Method 1: Via [**Baidu Cloud Download**](http://pan.baidu.com/s/1jHNBL7C)
-Method 2: Via [**Github's Releases Download**](https://github.com/NaoTu/DesktopNaotu/releases)

### System corresponding to each version

| Operating System | Number of Digits | Corresponding File | Size | Support Status |
| -------- | -----: | -----: | :---- | - |
| MacOS | 64-bit | DesktopNaotu-macOS-x64 | <50M | Support all functions |
| Linux | 64bit | DesktopNaotu-linux-x64 | <50M | Support all functions |
| Windows 7/10 | 64-bit | DesktopNaotu-win32-x64 | <50M | Support all functions |
| Windows 7/10 | 32-bit | DesktopNaotu-win32-ia32 | <50M | Support all functions |
| Windows XP | 32-bit | DesktopNaotu-Windows-mini | <8M | Does not support debugging |

### Features

-Contains the basic functions of Baidu Brain Map
-Operation of local km files
-Support drag and drop to open km file
-Support to open km files in association
-Support auto save function
-[Provide **Baidu Brain Map** file download method] (Help.md)
-[Provide **ProcessOn** download method of mind map](Help.md)
-[View historical version](History.md)

### Software screenshot

-Windows screenshot

![Windows](screenshot/Windows.png)

-Mac OS X screenshot

![OS X](screenshot/OSX.png)

-Linux screenshot

![Linux](screenshot/Linux.png)

### How to compile

#### 1. Install all dependencies

```bash
# Install necessary tools
npm install -g gulp
npm install -g bower

# Automatic installation of dependencies
npm install
bower install
```

#### 2. Change the graceful-fs version (for Node `v10.x` and above)

```bash
npm install graceful-fs

# If the error "ReferenceError: primordials is not defined" still occurs,
# Then delete the old version installed by cnpm
rm -rf node_modules/_graceful-fs@3.0.12@graceful-fs

# If a submodule depends on the old version of graceful-fs, please follow the error message,
# Switch to the module directory to update.
cd node_modules/<PATH_TO_MODULE_USING_DEPRECATED_GRACEFUL_FS>
npm install graceful-fs@4.x
```

#### 3. Change `@types/node` version

```bash
npm install @types/node@12.x
```

#### 4. Start compiling

```bash
gulp
```

#### 5. Test run

```bash
npm run demo
```

### contact us

Questions and suggestions feedback:

-[Github issues](https://github.com/NaoTu/DesktopNaotu/issues)
-[Join the discussion group](https://gitter.im/DesktopNaotu/DesktopNaotu)
-QQ group: 330722928

### Donation Project

Thank you for your generous donation.

![WeChat donation](doc/image/wechat-qr.png)

Code released under the [GPL-2.0 License](LICENSE).

## 2. English introduction

### Software introduction [--> **Chinese Introduction**](doc/README-zh.md)

The desktop version of Mind Mapping is a localized version of Baidu Mind Mapping, which helps you to use Mind Mapping Tool without Internet.

### Special Sponsors

<p align="center"><a href="https://documentnode.io/?utm_source=github&utm_medium=sponsor&utm_campaign=desktopnaotu" target="_blank" rel="noopener noreferrer"><img src="https:/ /user-images.githubusercontent.com/2252451/65103852-16463380-da02-11e9-8b58-bea4a84c2e31.png" alt="Document Node logo"></a><br>
Open Document Node, Inspiration Unfold</p>

### How to download

-Method 1: Download through [**Baidu Cloud**](http://pan.baidu.com/s/1jHNBL7C)
-Method 2: Download through [**Github's Releases**](https://github.com/NaoTu/DesktopNaotu/releases)

### System corresponding to each version

| Operating System | Bit | Corresponding File | Size | Support |
| -------- | -----: | -----: | :---- | - |
| MacOS | 64 bit | DesktopNaotu-macOS-x64 | <50M | Supports all functions |
| Linux | 64 bit | DesktopNaotu-linux-x64 | <50M | Supports all functions |
| Windows 7/10 | 64 bit | DesktopNaotu-win32-x64 | <50M | Supports all functions |
| Windows 7/10 | 32 bits | DesktopNaotu-win32-ia32 | <50M | Supports all functions |
| Windows XP | 32 bits | DesktopNaotu-Windows-mini | <8M | Debugging is not supported |

### Functional characteristics

-Basic functions of Baidu Mind Mapping
-Operation of local km files
-Support dragging open km files
-Support association to open km files
-Support for automatic saving
-[Provide **Baidu Mind Mapping** File Download Method](doc/Help.md)
-[Provide **ProcessOn** Mind Map Download Method](doc/Help.md)
-[View Historical Version](doc/History.md)

### Software screenshots

-Windows screenshot

![Windows](screenshot/Windows-en.png)

-Mac OS X screenshot

![OS X](screenshot/OSX.png)

-Linux screenshot

![Linux](screenshot/Linux.png)

### How to compile

#### 1. Install dependencies

```bash
# Install prerequisites
npm install -g gulp
npm install -g bower

# Install dependencies
npm install
bower install
```

#### 2. Change graceful-fs version (For Node `v10.x` or newer)

```bash
npm install graceful-fs

# If error "ReferenceError: primordials is not defined" still occurs, remove the old edition installed by cnpm
rm -rf node_modules/_graceful-fs@3.0.12@graceful-fs

# If a submodule relies on old graceful-fs, please follow the log, locate to its directory,
# then manually update
cd node_modules/<PATH_TO_MODULE_USING_DEPRECATED_GRACEFUL_FS>
npm install graceful-fs@4.x
```

#### 3. Change `@types/node` to v12.x

```bash
npm install @types/node@12.x
```

#### 4. Build

```bash
gulp
```

#### 5. Try running

```bash
npm run demo
```

### Contact us

Questions and suggestion feedback:

- [Github issues](https://github.com/NaoTu/DesktopNaotu/issues)
- [Join the discussion group](https://gitter.im/DesktopNaotu/DesktopNaotu)
- QQ group：330722928

### License

Code released under the [GPL-2.0 License](LICENSE).
