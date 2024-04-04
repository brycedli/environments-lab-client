# Environments Lab Client

You've got this sophomores!

## To get this on your computer
1. Install Git and Git LFS
2. Install Unity 2022.3.18f1 or higher
3. Run: ```git lfs clone https://github.com/brycedli/environments-lab-client.git```

## Steps to run

#### MM-127 computer
1. On MM-127 computer, make sure Optitrack-Remote-Template is open, and run the "Server template" scene.
2. Set the port in "Optitrack Stream Server" script (Inside the "Enable for Server" gameobject) to something
3. In the Console tab, there will be an IP address/port– we'll reference this later. If there is a SocketException port issue, choose another port and run again. I will make it so that it automatically finds an open port in the future.
4. Create a new Optitrack Rigidbody with the corresponding ID, and give it the Tag "OptiTrack"

#### Your computer
1. In the SyphonClientHDRP project, open the Server Template scene.
2. Make an empty gameobject that has the same NAME as the rigidbody you made previously
3. Set the IP port in "Optitrack Stream Client" script (Inside the "Enable for Server" gameobject) the IP address/port

#### Optional (Mac): To fullscreen this or send this to touchdesigner, aftereffects, etc
1. Download Syphon.Simple.Apps.zip from this [link](https://github.com/Syphon/Simple/releases/tag/5)
2. Open Simple Client and select the Unity output channel
3. Hide toolbar/tab bar and hit fullscreen.
4. You can also use Syphon plugins to connect to all kinds of apps, [as described here.](https://syphon.github.io/) 

For Windows, I will test later, but the gist is you download the Spout simple client and you set it up the same way I set up Syphon. The Unity part should be already installed. 
