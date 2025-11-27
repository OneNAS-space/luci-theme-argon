<!-- markdownlint-configure-file {
  "MD013": {
    "code_blocks": false,
    "tables": false,
    "line_length":200
  },
  "MD033": false,
  "MD041": false
} -->

<div align="center">

# A brand new OpenWrt LuCI theme

Argon is **a clean and tidy OpenWrt LuCI theme** that allows<br/>
users to customize their login interface with images or videos.  
It also supports automatic and manual switching between light and dark modes.

**English** |

[Key Features](#key-features) •
[Branch](#branch-introduction) •
[Version History](#version-history) •
[Getting started](#getting-started) •
[Screenshots](#screenshots) •
[Contributors](#contributors) •
[Credits](#credits)

</div>

## Key Features

- Clean Layout.
- Adapted to mobile display.
- Customizable theme colors.
- Support for using Bing images as login background.
- Support for custom uploading of images or videos as login background.
- Automatically switch between light and dark modes with the system, and can also be set to a fixed mode.
- Settings plugin with extensions [luci-app-argon-config][config-link]

> **Upcoming Version **
>
> "The current theme uses Less for CSS construction, and the method for switching between light and dark modes is relatively primitive. Meanwhile, the official theme has already switched to the UT template. I am exploring a way to build the theme template using modern front-end development tools, initially settling on a solution using Vite + UnoCSS. This approach will utilize a proxy server for debugging and also support HMR (Hot Module Replacement), significantly improving development speed. Currently, the basic development framework has been set up, but due to a busy schedule, I still need some time to migrate the existing styles. Stay tuned!"



## Notice

- Chrome browser is highly recommended. There are some new css3 features used in this theme, currently only Chrome has the best compatibility.
- Microsoft has officially retired Internet Explorer, RIP IE🙏<del>Currently, the mainline version of the IE series has bugs that need to be addressed.</del>
- FireFox does not enable the backdrop-filter by default, [see here](https://developer.mozilla.org/zh-CN/docs/Web/CSS/backdrop-filter) for the opening method.

## Screenshots

![desktop](/Screenshots/screenshot_pc.jpg)
![mobile](/Screenshots/screenshot_phone.jpg)

