# unreal_engine 5.0
Implementation of Unreal Engine 5 for wheeled robot simulation.

## 1. Download Unreal Engine
https://www.unrealengine.com/en-US/download

## 2. Setting up Simulation Environment
[How to setup Unreal Engine 5 Environment](UE5_setup.md)

## 3. LiDAR set up
#### 3.1 Great Resource but not sure if it'll work on Windows. Move to 3.2
https://www.youtube.com/watch?v=Uf2p37seXGE
https://github.com/metabotics-ai/MetaLidar
#### 3.2 Airsim - ChatGPT's suggestion for LiDAR
AirSim (Aerial Informatics and Robotics Simulation) is an open-source, cross platform simulator for robots.

Referenced: 
- https://microsoft.github.io/AirSim/build_windows/
- https://www.youtube.com/watch?v=BVkN3CCMg4A&t

ON WINDOWS <br>

### 3.2.1 Clone the AirSim repository

```
git clone https://github.com/Microsoft/AirSim.git
cd Desktop/AirSim/
build.cmd # this will give you an error

oh oh... You need to run this command from x64 Native Tools Command Prompt for VS 2022.
```

### 3.2.2 Install vscode 2022

https://visualstudio.microsoft.com/ko/vs/community/
- Desktop development with C++ - (from Workloads)
- Windows XX SDK (latest version for your windows) - (from Onstallation details)
- .NET Framework 4.8.1. SDK - (From Individual components) 

VisualStudio 2022 > run without code > tools > command line > developer command line Prompt

### 3.2.3 Setting up
```
cd Desktop/AirSim/
build.cmd
# need at least 50Gb free space
```






Navigating to UE5 Program File
```
dseong@DESKTOP:~$ cd /mnt/c/Program\ Files/Epic\ Games/UE_5.4/

dseong@DESKTOP:/mnt/c/Program Files/Epic Games/UE_5.4$ ls
Engine  FeaturePacks  Samples  Templates  ToolComplete.txt

cd Engine/Plugins/


```

## 4. ROS2 implementation
I am running this on Windows. Figuring out Windows or wsl -> UE5 will might be a problem.


## 5. Point cloud extraction