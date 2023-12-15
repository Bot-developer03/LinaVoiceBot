# Lina Voice Bot
![-5856165201060146060_121](https://github.com/Bot-developer03/LinaVoiceBot/assets/145082163/95089326-3f9c-4be0-8aa8-c0bae7d7d9ef)

- Telegram Voice-Chat Bot To Play Music From Various Sources In Your Group.
- Uses MPV Player for Playing! with Queue supported.
- Enjoy 320Kbps Lina Voice Bot with Telegram x64 Radio Mode.

# Support

1. All linux based os.
2. Windows.
3. Mac.

# Working

Python receives bot commands using pyrogram client which processes to play via mpv player.
Using pulseaudio we can route our audio to telegram desktop.

## Requirements

- Python 3.9 or higher
- A [Telegram bot token](//t.me/botfather)
- Bot needs to be admin in the chat, atleast give message delete permissions.
- Install `mpv` with

# Installation

```
pkg install mpv
```
```
gitclone://bot-developer03/LinaVoiceBot
```
```
cd LinaVoiceBot
```
```
pip3 install -r requirements.txt
```
```
cp sample_config.py config.py
```
```
python3 main.py
```
# Ubuntu 
```
sudo apt-get install mpv
```
```
gitclone://bot-developer03/LinaVoiceBot
```
```
cd LinaVoiceBot
```
```
pip3 install -r requirements.txt
```
```
cp sample_config.py config.py
```
```
python3 main.py
```

Open Telegram and start voice chat.

## Commands
Command | Description
:--- | :---
/help | To Show This Message.
/saavn <song_name> | To search and Play A Song From Jiosaavn.
/playlist | Saavn_playlist_link or Playlist Name" To Search and Add all songs to Queue and Play.
/youtube <song_name> | To Search For A Song And Play The Top-Most Song Or Play With A Link.
/telegram | To Play A Song Directly From Telegram File.
/deezer | To Play A Song From Deezer.
/queue | To See Queue List.
/skip | To Skip Any Playing Music.
Admin Commands:
/clearqueue | It clears entire Queue in a snap.

## Note

1. More updates will be added soon.
2. Termux is supported using debian inside termux.
