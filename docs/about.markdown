---
layout: page
title: About
permalink: /about/
---

Visual Studio Code is an open source text editor from Microsoft that has a rich ecosystem of customization and extensions. Their current list of accessibility features include options to remap mouse buttons for commands, change color palettes for color blindness, change zoom settings, and connect to a screen reader. However, there are no current options to control the IDE with voice commands. Our VS Code extension will solve that issue by allowing the user to input voice commands into the editor to access its feature set. Those that have disabilities, injuries, or illnesses that prevent full use of their arms, hands, and fingers will have another option for interfacing with the VS Code editor. This will include a long list of commands available to the editor that are currently mapped as hotkeys or must be searched manually.

Because Visual Studio Code is an extremely popular text editor outside of just the English-speaking world, Voice Control supports the `en`, `zh-cn`, `ja`, `es`, `it`, `pt-br`, `ru`, `ko`, `fr`, `de`, `pl`, `hu`, `cs`, `tr` locales.

## Features
- Executes every command available to VS Code
- Rename spoken commands for easier interpretation
- Available for all locales in VS Code
- Completely cross platform (Windows, Mac, and Linux)
- Organize commands into groups and execute with an alias

## Technologies
- Python
- Typescript
- VS Code [Extension API](https://code.visualstudio.com/api)
- Speech-to-text with OpenAI's [Whisper Library](https://openai.com/index/whisper/)
