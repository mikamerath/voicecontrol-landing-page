---
layout: page
title: About
permalink: /about/
---

Voice Control for VS Code is an extension that allows users to execute commands hands free. Using thei voice, users can execute a variety of commands available to the IDE. Simply speak the wake word "go", then say the command you would like to run
"Terminal: Create new terminal" and the extension will execute the command for you. Speed up your development process by writing code and running commands simultaneously.

Voice Control supports the `en`, `zh-cn`, `ja`, `es`, `it`, `pt-br`, `ru`, `ko`, `fr`, `de`, `pl`, `hu`, `cs`, `tr` locales.

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
