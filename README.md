# Traffic-Stop-Info-FivePD
A traffic stop experience enhancer  

# About
You get the more realistic process of a plate check

**How does it work**
- You stopping the vehicle
- Do a request for a plate check
- Press the button after request
- *'Dispatch'* starts find info about vehicle and its owner
- You get the convenient and detailed report

**Report** consists of:
- Short *color name* and *model* of vehicle
- *Vehicle flags*, if any
- A note if vehicle was stopped multiple times
- *Insurance* and *Registration* check
- *Owner name* and his *warrant/s*
- *DL status*

Your actions have sound surroundings like press button or getting report

A plugin has a __Config__ for full customize:
- __Change keybind__ after requesting a plate check
- __Change__ minimum and maximum __wait time__ of report
- __Translate all text__ to your language ( _Note: text may not fit in different languages_ )

# Installation
1. Download the [latest release](https://github.com/DR099H/Traffic-Stop-Info-FivePD/releases)
   
2. Place the `TSInfo` folder into `fivepd/plugins`
   
3. Make sure you have `'./plugins/**/*.net.dll'` string in `client_scripts` section of `fxmanifest.lua`

# Plugin is WIP
Currently working on:
- [ ] Make sure that the plugin is stable

- [x] **Config** for full plugin customize (_thanks [DevKilo](https://github.com/DevKilo1/Kilo.Commons.Config) for his config_)

  - [x] **Full translation** on any language
        
  - [x] Customizable button (only `N` now)
        
- [x] Pursuit check for cancelling report
