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
 # Archlinux
 ```
sudo pacman -S mpv
```
#Windows
Download mpv
```
https://sourceforge.net/projects/mpv-player-windows/files/
```
and run Mpv-installer as administrator the add mpv file to path envionment!

# linux
6. If you are on linux follow [this](ttps://github.com/Devanagaraj/Tg_Meowzik_Bot/blob/master/vnc.md) 
instruction to set up vnc. If you are using windows you can skip this step.
6. Download Telegram x64 desktop from https://t.me/tg_x64 , Log in using your second account, and enable radio mode in settings/advanced settings and then connect 
to 
the 
voice chat in your group.
7. Follow [This](https://unix.stackexchange.com/questions/82259/how-to-pipe-audio-output-to-mic-input) to route 
your PC or Server's audio output to audio input. [For Linux]
8. If you're on windows, Follow 
[This](https://superuser.com/questions/1133750/set-output-audio-of-windows-as-input-audio-of-microphone) or install Virtual Audio Cable instead.
9. Run the bot `python3 main.py`
10. Open Telegram and start voice chat.
11. Send [commads](https://github.com/Devanagaraj/Tg_Meowzik_Bot/blob/master/README.md#commands) to bot to 
play music.

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
