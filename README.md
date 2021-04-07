# Bitclout Dark Mode & Style Tweaks 

A collection of tiny style tweaks for the BitClout UI

![Screenshot](/screenshot.jpg?raw=true "Screenshot (default)")

TLDR; The monospaced font being used "stylistically" in place of a proportional font annoys the bejeesus out of me, so I created this extension to turn it off. I decided to make a few more tweaks along the way, to improve the user experience of other early BitClout users.


## Find me on BitClout!

If you want to follow along for updates, I'm [kidGodzilla](https://bitclout.com/u/kidGodzilla) on BitClout (and [kidgdzilla](https://twitter.com/kidgdzilla) on Twitter)

---

## Installation via Google Chrome (also compatible with Edge, Opera)

**Chrome Web Store:** *Soon! See instructions below for manual installation*


## Installation via Firefox Addon

**Firefox addon:** https://addons.mozilla.org/en-US/firefox/addon/bitclout-dark-mode-ui-tweaks/


## Manual Installation

[Download this extension as zip](https://github.com/kidGodzilla/bitclout-style-tweaks/archive/refs/heads/main.zip)

Then, **unzip** the folder somewhere, and leave it there. If you delete it, the extension stops working.

**Google Chrome:**

1. Navigate to `chrome://extensions/` in your browser
2. Enable Developer Mode (toggle in upper right corner of screen)
3. Click `Load Unpacked` (extension) in the top left corner, and select the extension directory

**Firefox:**

1. Navigate to `about:debugging#/runtime/this-firefox` in your browser. 
2. Click `Load Temporary Addon` & then select the `manifest.json` in the folder you just created


That's it! 

Remember, Updates don't occur automatically when you manually install the extension from source.


## Dark Mode (Experimental)

![Screenshot dark](/screenshot-dark.jpg?raw=true "Screenshot (dark)")

I've put together an MVP of "dark mode". A lot of the values are too generic (`#111, #222, etc.`) – I'm just roughing it out. Ideally, these would be a bit tighter and a bit more nuanced.


## Todos

- [x] There's still quite a bit of boilerplate that I might end up deleting, just so people don't have to read as much code to ensure I'm not stealing their keys 😅 

- [x] I wanted to have a fancy settings menu for dark mode, but it ends up generating a lot of "stuff". Could remove it for v1, especially since dark mode might be too ambitious for the first release.

- [x] Dark mode MVP completed


## Credits

Boilerplate generated by https://extensionizr.com/

