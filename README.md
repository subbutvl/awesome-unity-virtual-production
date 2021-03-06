# awesome-unity-virtual-production

Awesome Tools for Unity Virtual Production ( This is an non-official list ). We hope Unity Company creates a good Workflow/Pipeline for Virtual Production in a near future for us. At the moment we can test this options. Send your results.

![image](https://github.com/magadan/awesome-unity-virtual-production/blob/master/draft.jpg)

Prepare your Project and Studio Workstation with this amazing collection of tools for your own Unity 3D Virtual Production software solution. Feel free to help the list !

## Unity 3D LEDWall possible solutions and assets ##

Depends of your LedWall Layout if is "curved" you will need to adjust the distortion of your virtual camera(s) to fits the real world.

### Thirdy Part options: ###

Disguise Multiple Displays Middleware - https://www.disguise.one/en/products/

Omnity for Curved Displays Mounts - https://www.elumenati.com/product/omnity/

VIOSO - https://vioso.com/software/   and   Plugin: https://assetstore.unity.com/packages/tools/integration/multi-projection-integration-for-blending-and-warping-166403

### Free Assets options (You will need to make some tweaks on scene or code): ###

Dome Tools - https://assetstore.unity.com/packages/vfx/shaders/fullscreen-camera-effects/dome-tools-62664

360 VR Camera - https://assetstore.unity.com/packages/tools/camera/360-vr-camera-capture-rig-53264

### Comercial Assets Options: ###

Multi Projector Warp System - https://assetstore.unity.com/packages/tools/camera/multi-projector-warp-system-75582

VR Panorama - https://assetstore.unity.com/packages/tools/video/vr-panorama-360-pro-renderer-35102

### For Builded Projects with Multi Monitor Support (No In-Editor mode): ###

If you prepare your project to Run with Unity Builds dont forget to activate your Multiple Screens Output:

https://docs.unity3d.com/560/Documentation/Manual/MultiDisplay.html

## Camera Off Axis (ViewPort) ##

OffAxisCamera computes and applies an off-axis perspective projection to a camera dynamically. This can save your CPU and GPU processing when you are running multiple screens, like nDisplay does for Unreal.

https://assetstore.unity.com/packages/tools/camera/offaxiscamera-98991

https://assetstore.unity.com/packages/tools/camera/camera-off-axis-projection-142595

## Multi User Edition in Realtime ##

Multi User edition can be a good solution to work with multiple render nodes on the Stage for multiple displays or you can create simple control gui that works over local lan or remote.

FREE VERSION
Scene Fusion can be used for free for teams of two (2) people on game environments of up to 2000 objects*. Simply register an account, then use the console to invite your teammate.

Scene Fusion from Kinematic Soup - https://www.kinematicsoup.com/scene-fusion/download

## Unity 3D Video Plugins ##

SPOUT for Unity 3D Plugin - https://github.com/keijiro/KlakSpout   ( almost zero latency and no gpu overhead ! ), input and output available.
(Note: I tested and Spout Sender not works in HDRP if attached to camera in this version, you need to create a Render Texture and output this texture to a spout sender ).

Unity UVC - https://github.com/Satoshi-Hirazawa/unity-uvc-camera - Insert a USB Video Capture Device Directly into a Scene (free and good) 

Unity Capture - Creates a Windows Virtual Device Output ( 4K and 60 fps support ) - https://github.com/schellingb/UnityCapture  

Unity3D UnityCam - https://github.com/mrayy/UnityCam

Unity3D uWindowCapture - https://github.com/hecomi/uWindowCapture/

Unity3D NextPlayer - https://github.com/NexPlayer/NexPlayer_Unity_Plugin

Unity 3D FFMpeg Out - Exports frame by frame to video file - https://github.com/keijiro/FFmpegOut/releases

NDI Input and Output for Unity 3D (unity plugin ) - https://github.com/keijiro/KlakNDI

Black Magic Decklink for Unity 3D - https://github.com/keijiro/Klinker

GenLock Frame Rates - https://github.com/Unity-Technologies/GenLockProofOfConcept

### HAP Video Codec Player for Unity 3D: ###

Free: https://github.com/keijiro/KlakHap

Comercial: https://assetstore.unity.com/packages/tools/video/demolition-media-hap-78908

### Comercial Plugins: ###

AVPRO Live Camera (DeckLink support) - https://assetstore.unity.com/packages/tools/video/avpro-live-camera-3683

AVPRO Video (4K Support) - https://assetstore.unity.com/packages/tools/video/avpro-video-windows-57969

AVPRO DeckLink - https://assetstore.unity.com/packages/tools/video/avpro-decklink-68784

## Unity 3D Shaders for Video Compositing ##

ClydedeSouza HDRP Chromakey Shader - https://github.com/dirrogate/HDRP-Unity-Chromakey

Chromakey Shader with Shadow Support - https://github.com/hecomi/uChromaKey

ProcAmp Shader ChromaKey (works in HDRP too) - https://github.com/keijiro/ProcAmp

## Unity 3D Control Plugins ##

SteamVR - https://assetstore.unity.com/packages/tools/integration/steamvr-plugin-32647

#### VRPN Asset to sync multiple Nodes and Trackers between another Unity running the same project ####

https://github.com/arviceblot/unityVRPN/releases   ( https://en.wikipedia.org/wiki/VRPN )

OSC Plugin for Unity:

https://github.com/keijiro/OscJack  (for me this is the best, simple and easy )

https://github.com/jorgegarcia/UnityOSC

https://github.com/thomasfredericks/UnityOSC

https://assetstore.unity.com/packages/tools/input-management/extosc-open-sound-control-72005

KlakUI - https://github.com/keijiro/KlakUI

Comercial: https://assetstore.unity.com/packages/tools/input-management/osc-simpl-53710

### External Video Tools ###

SpaceDesk Extend Monitor to a Smartphone ( Android and IoS ), create a Field Monitor

http://www.spacedesk.com

OBS - Spout Input Source - https://github.com/Off-World-Live/obs-spout2-source-plugin

OBS - OpenBroadCast Studio - https://obsproject.com/

OBS - NDI Plugin - https://github.com/Palakis/obs-ndi/releases

OBS - Virtual Camera Plugin - https://github.com/Fenrirthviti/obs-virtual-cam/releases

OBS OSC Control - https://github.com/CarloCattano/ObSC

## External Required Tools ##

SPOUT Runtime - https://spout.zeal.co/

NewTek NDI Tools for Windows - https://ndi.tv/tools/

Quick Time - https://support.apple.com/pt_BR/downloads/quicktime

HAP Codec - https://hap.video/developers.html

FFmpeg - https://www.ffmpeg.org/download.html

## For remote Productions ##

Medialooks Transport for NDI over internet - https://www.medialooks.com/video-transport

See too:  Unity RenderStreaming built-in package

### Remote Control Protocols ### 

DMX Support to control Virtual Lights - https://github.com/davivid/Unity-DMX

#### Use OSC over the web: ####

Open Stage Control , OSC Controller System for Web - https://openstagecontrol.ammd.net/

OSC Web Bridge for Node.JS - https://github.com/automata/osc-web

### Network VPN for remote team members ###

ZeroTier One is a good option and easy to configure - https://www.zerotier.com/

Uprinl VPN Server - This software deploys a fully openvpn for your project, very simple to install standalone or with docker container on a AWS EC2 or VPS. - https://pritunl.com/


## External Tracking Systems (Camera Tracker) ##

ZED 2 Camera for Depth Sensing and Spatial AI. Unity ready - https://www.stereolabs.com/

Driver4VR - http://www.driver4vr.com  (use any other tracker devices to help the stage )

PSMoveService (to use psmove as camera tracker ) - You PSMove and PSEYE's as a Tracker
https://github.com/psmoveservice/PSMoveService

Steam VR - Requeriment tool ( Download the app and Unity 3D Plugin)

Mo-Sys Camera plugin for Unity 3D (is ready!) -> https://www.mo-sys.com/

We are wainting (Professional Depth Tracker Cameras support ):

- nCam plugin for Unity 3D -> https://www.ncam-tech.com/
https://www.bhphotovideo.com/c/product/1538940-REG/ncam_nc_plu_vz_ue_unity_plugin.html

- sTYpe Camera plugin for Unity 3D -> https://stype.tv/

- Solid-Track (Unity Plugin available ) -> http://www.solid-track.com/

## Codeless ( Automation )

GameFlow is good for begginers that dont know how to make actions by script.

GameFlow -> https://evasiongames.itch.io/gameflow

## Hardware Recommendation Workstation

HP Z4

Nvidia RTX 2008Ti

CPU i9

Memory 32 Gb

## Eviroment ##

Use latest Unity version with HDRP + DXR Support for Realtime Ray Tracing

Contract

- A Technical Director

- A 3D software generalist Specialist

- A 3D Enviroment Artist Specialist

- A 3D Lighting Artist Specialist

- A Unity 3D HDRP (DXR) Pipeline specialist

- A Game Developer Specialized in VR Games to setup your VIVE Trackers.

Good Luck and great production.
