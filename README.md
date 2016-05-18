> Don't forget these ideas

* [Ideas](#ideas)
  * [Facebook chat cli](#facebook-chat-cli)
  * [Soundcloud cli](#soundcloud-cli)
  * [Github chrome extension](#github-chrome-extension)
  * [Mobilify](#mobilify)
  * [Social coding](#social-coding)
  * [Holographic spaceinvaders](#holographic-spaceinvaders)
  * [Config manager](#config-manager)
* [Summary](#summary)

# Ideas

This repo has some crazy ideas that could become, some day, in awesome projects.

## Facebook chat cli

> Facebook chat from the command line

### Description:

There are many cli extension through npm modules, like:

* https://github.com/sindresorhus/term-img-cli
* https://github.com/chjj/blessed
* https://github.com/JoshCheek/animated-gif-in-the-terminal
* https://github.com/as-cii/terminal-emojify
* https://github.com/yaronn/blessed-contrib

That improve the terminal experience, also there are some facebook messenger clones like [this](https://github.com/sindresorhus/caprine).

So, the idea is simple, clone the facebook chat on the terminal, so there is no need of a browser.

## Soundcloud cli

> Soundcloud client from the terminal

### Description:

Similar to facebook chat cli, but easier because there is a [public API](https://developers.soundcloud.com/docs/api/guide) for the souncloud app. Some people already made some [GUI app](https://github.com/Soundnode/soundnode-app) with it

### References:

* http://askubuntu.com/questions/82605/how-to-play-music-in-terminal
* http://askubuntu.com/questions/115369/how-to-play-mp3-files-from-the-command-line
* http://askubuntu.com/questions/193737/how-to-listen-radio-from-terminal
* http://www.unixmen.com/how-to-play-music-from-command-line-terminal/

## Github chrome extension

> Manage your github stars by tags

### Description:

There are already some github chrome extensions, but this wouls be only to (better) manage github stars, as Github only group by langague. Check [astralapp](http://astralapp.com/)

## Mobilify

> Convert any web page into a mobile app

### Description:

Heavily inspired by the awesome [nativifier](https://github.com/jiahaog/nativefier). Basically, the same but to make mobile apps from a web page. It would use cordova to take the html, js and css and convert it in a mobile app. It would be useful for awesome pages that doesn't have a mobile app, but have awesome mobile sites, for example, Github.

## Social coding

> Let others developers know what you are coding

### Description:

Github and Stackoverflow are some of the most popular dev sites/tools. They have two big things in common:

1. A public API
2. They are social!

So, it would be awesome to have some feed of your social coding, for the cli or as an embedded html (to add to portfolio for example)

## Holographic spaceinvaders

> Futuristic space invaders

### description:

Everyone knows the Spaceinvaders game. Seeing this two projects.

* https://github.com/feross/magickeyboard.io
* https://github.com/philippedubost/keybright
 
I think that an awesome new version of the popular game could be made. A web version and an awesome holographic version.

## Config manager

> Centralized manager for config files of npm modules

### description:

Many npm packages use config files, like `eslint`, `babel`, `flow`, etc. So it would be useful to have a single json file to manage all of that config files.

# Summary

Here is a quick and highly opinionated summary about the ideas, showing three metrics from 1 to 10, except for the dificulty that goes from 1 to 5. The priority is the sum of the three metrics, and give us the order of development of the ideas. 

| Idea                      | Difficulty | Fun | Useful | Priority |
| ------------------------- | ---------- | --- | ------ | -------- |
| Facebook chat cli         | 5          | 8   | 5      | 18       |
| Soundcloud cli            | 4          | 10  | 10     | 24       |
| Github extension          | 2          | 5   | 10     | 17       |
| Mobilify                  | 5          | 5   | 7      | 17       |
| Social coding             | 3          | 8   | 5      | 15       |
| Holographic Spaceinvaders | 5          | 10  | 3      | 19       |
| Config manager            | 4          | 7   | 7      | 18       |

So, the order would be 

1. **Soundcloud cli**
2. **Config manager**
2. **Holographic Spaceinvaders**
2. **Facebook chat cli**
3. **Github extension**
4. **Mobilify**
5. **Social coding**

