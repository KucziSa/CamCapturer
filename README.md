### [+] Description

**VidPhisher is a phishing tool. It will generate a link. If anyone opens the link and permits camera access, his/her video will be captured and sent to you!**

### [+] Installation

- `git clone https://github.com/KasRoudra/VidPhisher`
- `cd VidPhisher`

For termux, use additional command `termux-setup-storage`

- `bash vp.sh`

##### Or Run Directly

```
wget https://raw.githubusercontent.com/KasRoudra/VidPhisher/main/vp.sh && bash vp.sh
```

##### Usage

```
Usage: bash vp.sh [-h] [-o OPTION] [-p PORT] [-t TYPE] [-s DURATION] [-d DIRECTORY] [-u] [-nu]

Options:
  -h, --help                           Show this help message and exit
  -o OPTION, --option OPTION           Index of the template
  -p PORT, --port PORT                 Port of VidPhisher's Server
  -t TYPE, --tunneler TYPE             Type of media (video or audio or screen)
  -d DIRECTORY, --directory DIRECTORY  Directory where videos will be saved
  -s DURATION, --duration DURATION     Duration of media (Default: 5000(ms))
  --update(-u), --no-update (-nu)      Check for update (Default: true)
```

### [+] Features

- Two Templates
- Get IP, Location, Device type and Browser
- Dual Tunneling (Ngrok and Cloudflared)
- Choose where to save videos(custom directory)
- Error Diagnoser
- Argument support for templates, type, port, duration and directory

### [+] Preview

![Hack anyone's camera and get videos](files/vp.gif)

### [+] Depenencies

- `php`
- `curl`
- `wget`
- `unzip`

All of the necessary depenencies will be installed automatically in first run!

### [+] Note

Edge do not suport video capturing. Only audio can be captured from it. Only Firefox supports screen capturing additionally. And most of the rests support video and audio. If browser doesn't block VidPhisher and the victim allows access only then you can capture video/audio

### [+] Credits

Thanks to <a href="https://github.com/Techchipnet/camphish">Techchip</a> and <a href="https://github.com/muaz-khan/RecordRTC">Muaz Khan</a> for their open source codes!

### [+] Disclaimer

**_This tool is developed for educational purposes. Here it demonstrates how camera phishing works. If anybody wants to gain unauthorized access to someones camera, he/she may try out this at his/her own risk. You have your own responsibilities and you are liable to any damage or violation of laws by this tool. The author is not responsible for any misuse of VidPhisher!_**
