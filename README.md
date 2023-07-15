<h1 align="center">
  Enigma 🤖 - A music recommender bot for Discord
  
 [![Open Source Love](https://badges.frapsoft.com/os/v3/open-source.png?v=103)](https://github.com/ellerbrock/open-source-badges/)
</h1>

<div align="center">

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![DOI](https://zenodo.org/badge/533639670.svg)](https://zenodo.org/badge/latestdoi/533639670)
[![Build Status](https://github.com/chetana-c/Enigma/actions/workflows/github-actions-build.yml/badge.svg)](https://github.com/chetana-c/Enigma/actions)
[![GitHub Release](https://img.shields.io/github/release/chetana-c/Enigma.svg)](https://github.com/chetana-c/Enigma/releases)
[![GitHub Repo Size](https://img.shields.io/github/repo-size/chetana-c/Enigma.svg)](https://img.shields.io/github/repo-size/chetana-c/Enigma.svg)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![GitHub contributors](https://img.shields.io/github/contributors/chetana-c/Enigma)](https://github.com/chetana-c/Enigma/graphs/contributors)
[![Open Issues](https://img.shields.io/github/issues/chetana-c/Enigma)](https://github.com/chetana-c/Enigma/issues)
[![Pull Requests](https://img.shields.io/github/issues-pr/chetana-c/Enigma)](https://github.com/chetana-c/Enigma/pulls)
![Supports Python](https://img.shields.io/pypi/pyversions/pytest)
[![Formatting python code](https://github.com/chetana-c/Enigma/actions/workflows/code-formatter.yml/badge.svg)](https://github.com/chetana-c/Enigma/actions/workflows/code-formatter.yml)
[![codecov](https://codecov.io/gh/chetana-c/Enigma/branch/main/graph/badge.svg?token=OEPEJ0W8CR)](https://codecov.io/gh/chetana-c/Enigma)

</div>

<p align="center">
    <a href="https://github.com/chetana-c/Enigma/issues/new/choose">Report Bug</a>
    ·
    <a href="https://github.com/chetana-c/Enigma/issues/new/choose">Request Feature</a>
</p>

<h1> 💡 Features </h1>

<div>
<ul>
  <li>Recommend songs based on user input and play them on discord voice channel</li>
  <li>Can be used by teams/friends to listen to the same songs together</li>
  <li>Acts as an amplifier - can be used to play same music on multiple speakers to give a surround sound effect and increase volume output</li>
  <li>Ability to toggle music pause/resume</li>
  <li>Ability to play custom song without having to search the song on youtube</li>
  <li>Ability to switch back and forth between songs</li>
</ul>
</div>
  
  
<h1> ⚒️ Installation Procedure </h1>


## 1. Prerequisites 

  * Install FFMPEG from [FFMPEG builds](https://www.gyan.dev/ffmpeg/builds), extract it and add it to your path [How to add FFMPEG to Path](https://www.thewindowsclub.com/how-to-install-ffmpeg-on-windows-10#:~:text=Add%20FFmpeg%20to%20Windows%20path%20using%20Environment%20variables&text=In%20the%20Environment%20Variables%20window,bin%5C%E2%80%9D%20and%20click%20OK.)

## 2. Running Code

First, clone the repository and cd into the folder:

```
$ git clone git@github.com:chetana-c/Enigma.git
$ cd Enigma
```

### Create a .env file with the discord token info: DISCORD_TOKEN=#SECRET_TOKEN#
### Join the discord channel of the bot [Discord Channel of bot](https://discord.com/channels/1017135653315686490/1017135653789646850) and connect to the voice channel.

```
$ pip install -r requirements.txt
$ python bot.py 
```

You can now use the discord bot to give music recommendations! Use /help to see all functionalities of bot.

<h1> 🚀 Demo </h1>

https://user-images.githubusercontent.com/20087273/194780603-f163caf6-2c9e-4d74-8fbd-c93f30e8935a.mp4




<h1>📍RoadMap </h1>

What We've Done:
1. Created a Discord Bot via the Discord Developer Portal.
2. Incorporated a [dataset](https://www.kaggle.com/datasets/leonardopena/top-spotify-songs-from-20102019-by-year) to our application.
3. Added functionalities to the Discord bot (explained in the [Features](https://github.com/chetana-c/Enigma/blob/main/README.md) section above.
4. Use the Discord Bot to play music based on the user's recommendations.
5. Can also use the Bot to play custom songs without having to search for it on YouTube.

What We've Yet To Do:
1. Extend the application to be deployed online (via a website or an application).
2. Make the song recommendations more sophisticated by using content-based recommendor systems.
3. Integrating dislikes (taking into account the feedback of users) in the recommendation logic.
4. Use web scraping and EDA to get a better database for the discord bot.
5. Alternatively, use [this](https://www.kaggle.com/datasets/saurabhshahane/music-dataset-1950-to-2019) as the primary data source to make better recommendations.
6. Add some more functionality to the discord bot:
    * Move a song within a queue or to the top of the queue
    * Shuffle songs within the queue
    * Jump to a specific song in the queue
    * Replay the song (instead of going to the next song and then coming back to the previous song)


<h1> 👥 Contributors <a name="Contributors"></a> </h1>

<table>
  <tr>
    <td align="center"><a href="https://github.com/chetana-c"><img src="https://avatars.githubusercontent.com/u/57283645?v=4" width="75px;" alt=""/><br /><sub><b>Chetana Chunduru</b></sub></a><br /></td>
  </tr>

</table>

<h1> Contributing </h1>

Please see [`CONTRIBUTING`](CONTRIBUTING.md) for contributing to this project.

<h1> Data </h1>

The data for this project is present [here](https://www.kaggle.com/datasets/leonardopena/top-spotify-songs-from-20102019-by-year)

