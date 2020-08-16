theme: Poster
slidenumbers: true
slide-transition: fade(0.3)

> There are only two hard things in Computer Science: cache invalidation and naming things.

-- Phil Karlton

---

> There are 2 hard problems in computer science: cache invalidation, naming things, and off-by-1 errors.

-- Leon Bambrick

---

> there's two hard problems in computer science: we only have one joke and it's not funny.

-- @pbowden

---

## Level up Your Git Commits with Gitmoji! 👍🏻

---

# Overview

- Emoji Primer
- WTF?
- Gitmoji Tour
- Theory
- Tools

---

# Emoji Primer

## 💩

- name: Pile of Poop
- Unicode codepoint: U+1F4A9

![inline right](images/character-info.png)

- shortcode: `:poop:`
- https://emojipedia.org/pile-of-poo/

^ shortcode is plain text which is rendered using an emoji icon
^ emojipedia is a great place to review emoji details
^ different platforms/apps show different icons

---

# Emoji Versions

- Unicode 6.0 (2010)
- Unicode 8.0/Emoji 1.0 (2015)
- Unicode 10.0/Emoji 5.0 (2017)
- _No Emoji 6.0-10.0_
- Unicode/Emoji 11.0 (2018)
- **Unicode/[Emoji 12.0](https://emojipedia.org/emoji-12.0/)** (2019)
- Unicode/[Emoji 13.0](https://emojipedia.org/emoji-13.0/) (2020)

^ Unicode 6 was first version to include emoji
^ Now on a somewhat annual cadence
^ Emoji 13 now in Android 11, maybe iOS 14.1, macOS 11.1
^ Emoji 14 will be delayed 6 months into 2022 due to COVID-19

---

![fill](images/gitmoji-banner.png)

^ Created by Carlos Cuesta

---

# Inspired by Atom

[CONTRIBUTING.md#git-commit-messages](https://github.com/atom/atom/blob/master/CONTRIBUTING.md#git-commit-messages)

![fill right](images/atom.png)

^ contribution guidelines

---

# Examples

![mas history](images/mas-history.png)

---

# Gitmoji Tour

^ Built for JavaScript web projects

---

# 🎉

## `:tada:`

- Begin a project

^ first commit
^ called "party popper"

---

# ✨

## `:sparkles:`

- Introducing new features

---

# 🐛

## `:bug:`

- Fixing a bug

---

# ✅

## `:white_check_mark:`

- Adding or updating tests

---

# 🚨

## `:rotating_light:`

- Removing linter warnings

---

# 💄

## `:lipstick:`

- Adding or updating UI and style files

---

# 🔥

## `:fire:`

- Removing code or files

---

# 🎨

## `:art:`

- Improving structure or format of code

---

# 💥

## `:boom:`

- Introducing breaking changes

---

# 🔖

## `:bookmark:`

- Release/version tags

^ use this for the commit where you updated an app/library version

---

# 👷🏻‍♀️

## `:construction_worker:`

- Adding or updating CI build system

---

# 🔧

## `:wrench:`

- Adding or updating configuration files

---

# 🛠

## `:hammer_and_wrench:`

- Adding or updating **Xcode** configuration files

*This is a @phatblat™️ suggestion for Apple devs

---

# Get all that? 🤯

---

# Online Cheatsheet

- https://gitmoji.carloscuesta.me/

---

# Practice

---

# One emoji per commit message

- Like a label
- Wanting to cram more emoji is a sign that your commit may not be focused
- 🚑 > 🐛

^ some emoji are similar but trump each other
^ ambulance is a type of bug

---

# Tools

- gitmoji
- macOS Character Picker
- Karabiner-Elements
- Rocket

---

# Gitmoji Install

`npm i -g gitmoji-cli`

---

# Gitmoji List

![inline](images/gitmoji-list.png)

---

# Gitmoji Search

![inline](images/gitmoji-search.png)

---

# Gitmoji Commit

![inline fit](images/gitmoji-commit1.png)

^ interactive emoji search

---

# Gitmoji Commit

![inline fit](images/gitmoji-commit2.png)

^ interactive commit message

---

## macOS Character Viewer

![inline](images/emoji-picker.png)

# ^ + ⌘ + ⎵

^ control-command-space is the macOS system shortcut for Character Viewer
^ up to 32 most frequently used symbols

---

# Karabiner-Elements

![inline](images/karabiner-elements.png)

^ open source

---

# Programmable Keyboard

![](images/keycaps.jpg)

^ ErgoDox EZ programmable mechanical keyboard

---

# Rocket 🚀

![inline](images/rocket.png)

https://matthewpalmer.net/rocket/

^ slack-style emoji picker
^ free download
^ $5 pro features, like custom aliases

---

# References

- [What the 2021 Unicode Delay Means for Emoji Updates](https://blog.emojipedia.org/what-the-2021-unicode-delay-means-for-emoji/)
- [Gitmoji](https://gitmoji.carloscuesta.me/)
- [GitHub emoji shortcodes](https://emojipedia.org/github/)
- [GitHub Markdown Emoji](https://gist.github.com/rxaviers/7360908)
- [Slack Emoji Short Codes](https://emojipedia.org/slack/#:~:text=Slack%20permits%20a%20set%20of,instead%20of%20the%20emoji%20character.)
- [Use emoji and symbols on Mac](https://support.apple.com/en-gb/guide/mac-help/mchlp1560/mac)
- [@phatblat's keyboard setup](https://people.ergodox-ez.com/ben-chatelain/)
- [ErgoDox EZ programmable keyboards](https://ergodox-ez.com/)
- [Karabiner-Elements](https://karabiner-elements.pqrs.org/)
  - [Emoji-key](https://ke-complex-modifications.pqrs.org/json/Right_option_as_emoji_key.json)
  - [source](https://github.com/pqrs-org/Karabiner-Elements)
- [TwoHardThings](https://martinfowler.com/bliki/TwoHardThings.html) by Martin Fowler
