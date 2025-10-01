# VOXCOMM intercom
ESP based MESH intercom for motorcycle or general use

UNDER DEVELOPMENT

## What is VOXCOMM?
VOXCOMM is an ESP based MESH intercom and bluetooth device that can be used for motorcycle communication or for any other intercom based usecases.
It uses a proprietory built mesh to communicate to multiple VOXCOMM devices
VOX MESH is designed to be highly competetive against other brands with clean and extremely low latency audio transmission, open and private mesh groups, and long range communication

### Features:
* Bluetooth audio
  - high quality 44.1k 16 bit stereo audio playback
* VOX (Voice over X-mesh)
  - Potentially hundreds of connections*
  - Private group MESH
  - Open MESH
  - High quality 14.7k 16 bit 2 channel audio output for clear communication
 * Device
   - Display for changing settings and ease of use
   - Voice Assist allows you to hear what mode you are in whilst not being able to see the display
     
*from hardware limiation perspective

## What is MESH?
MESH is a type of networking topology that allows multiple devices to communicate to eachother at the same time.

Mesh networking is a way of connecting devices (called nodes) so that each node can communicate directly with others, without needing a single central router.
In a mesh, every node can relay data for others. This creates multiple paths for information to travel. If one path is blocked or a node goes offline, the data can automatically take another route.

## What is the difference between VOXCOMM and something like Cardo or Senna?
The VOXCOMM intercom doesnt use zigbee or bluetooth hardware for MESH communication, thus, it does not have the hardware limitations of such. Because of this, it is possible to communicate with many devices over a long distance.

VOXCOMM is very lightweight in its features (currently) therefore it has only bluetooth and mesh based capabilities.

VOXCOMM doesnt have a limit as to how many devices can communicate at one time (a realistic limmit should be set however for bandwidth limitations. This will be defined after testing)

## What features does the VOXCOMM MESH have?
* Create private MESH groups using user defined group names and passwords
* Create an open MESH where any VOXCOMM device can connect and communicate
* Automatic disconnect and reconnect

## What cant VOXCOMM do?
* Currently, it is not possible to use bluetooth and MESH at the same time, therefore, the bluetooth device is disconneted when switching between MESH and bluetooth modes but solutions to this are being worked on
* Currently it does not support HFP (Hands Free Profile), therefore mobile calls will not function via bluetooth, but this is also under development

## What is the current status of VOXCOMM intercom
* As of 1.10.2025 it is still under development. Majority of the hard work is already done
* Bluetooth audio and VOX MESH is functional - optimisations are needed
* Circuit board design is being started
* Multi device benchmarking is under way

## How can I contribute?
Contribution is greatly appreciated, but at this current stage, it is only a case of waiting for the first release for prototyping and further testing, but where it would be helpful:
- Circuitboard design - Help here would be grealy appreciated
- Case design - Designing a suitable case for the circuiboard to reside that would also be waterproof
- Financial contribution - This is obviously not a must, but it would be extremely appreciated, as this project is taking up a lot of weekends! but in the end would really like to get a viable and reliable product out onto the market that can compete with the big boys for a fraction of the cost!

## How can I contact you?
You can send me an email at walkrush28@gmail.com
