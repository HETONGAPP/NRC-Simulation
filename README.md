# 🌏NRC-SIMULATION
This repository is designed to create a comprehensive drone simulation platform using AirSim, integrating PX4, ROS, and Matlab for in-depth research. The project encompasses tasks such as platform setup, communication protocol establishment, and algorithm configuration, providing a robust and flexible framework for drone-related studies.
AirSim Integration: AirSim will be utilized as a core component in the codebase to provide a highly realistic simulated environment for drones.

    👉 PX4 Integration: The inclusion of PX4 will enable flight control and navigation for the drones, ensuring consistency between simulation and actual hardware.

    👉 ROS Communication: ROS will serve as a powerful communication bridge, facilitating efficient information exchange and data sharing among different modules.

    👉 Matlab Support: Integration of Matlab as a tool for research and algorithm development, empowering researchers to leverage Matlab's capabilities for algorithm experiments and optimization.

    👉 Algorithm Configuration: Flexible options for algorithm configuration will be provided to meet various research needs, including areas such as path planning and target tracking.

|     Winsows     |
| --------------- |
|  win_setup.bat  |


⦿ `Install Unreal Engine 5 & Visual Studio 2022`

    👉 https://www.unrealengine.com/en-US/download
    👉 Install Visual Studio 2022. Make sure to select Desktop Development with C++ and Windows 10 SDK 10.0.19041 (should be selected by default) and select the latest .NET Framework SDK under the 'Individual Components' tab while installing VS 2022.
    👉 Start Developer Command Prompt for VS 2022.

⦿ `Build and Install Airsim Plugin`
``` bash
# by git without submodules (Windows)
git clone https://github.com/CodexLabsLLC/Colosseum.git
# cd to target folder
cd Colosseum/
# run the build command
./build.cmd
````

⦿ `Run the demo project`
``` bash
Double click on .sln file to load the Blocks project in Unreal\Environments\Blocks (or .sln file in your own custom Unreal project)
````

⦿ `Revise setting.json file`
``` bash
replace Airsim Setting/settings.json TO cd C:\Users\Username\Documents\AirSim\settings.json
THEN change the "Windows IP" in settings.json with your windows machine IP
````

|      Linux      |
|:---------------:|
|  linux_setup.sh |

``` bash
# for Linux
$ export PX4_SIM_HOST_ADDR=your windows IP

# Set up PX4 
👉 https://microsoft.github.io/AirSim/px4_sitl/
````

⦿ `Install ZeroMQ`

``` bash
pip install pyzmq
````


