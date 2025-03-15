# FrontCam
Grab cam shots from target's phone front camera or PC webcam just sending a link.
![FrontCam]()

# What is FrontCam?![FrontCam](https://github.com/user-attachments/assets/e09ea49c-0e95-4c77-8afb-9f49d2f3ffb0)

<p>FrontCam is techniques to take cam shots of target's phone front camera or PC webcam. FrontCam Hosts a fake website on in built PHP server and uses ngrok & serveo to generate a link which we will forward to the target, which can be used on over internet. website asks for camera permission and if the target allows it, this tool grab camshots of target's device</p>

## Features
<p>In this tool I added two automatic webpage templates for engaged target on webpage to get more picture of cam</p>
<ul>
  <li>Festival Wishing</li>
  <li>Live YouTube TV</li>
   <li>Online Meeting [Beta]</li>
</ul>
<p>simply enter festival name or youtube's video ID</p>

## This Tool Tested On :
<ul

  <li>Kali Linux</li>
  <li>Termux</li>
  <li>MacOS</li>
  <li>Ubuntu</li>
  <li>Parrot Sec OS</li>
</ul>

# Installing and requirements
<p>This tool require PHP for webserver, SSH or serveo link. First run following command on your terminal</p>

```
apt-get -y install php openssh git wget
```

## Installing (Kali Linux/Termux):

```
git clone https://github.com/spycode2/FrontCam.git
cd FrontCam
bash frontcam.sh
```

Tutorial Video -->> https://youtu.be/G6ADBIg7rwE?si=nt65zZcU93uljoGm
