## **Overview**
Backdoor is a remote administration and monitoring tool designed for educational and testing purposes. It consists of two main components: ControlServer and BackdoorClient. The server controls the client, allowing for various operations like file transfer, system monitoring, and more.

## **Disclaimer**
This tool is intended for educational purposes only. Misuse of this software can violate privacy and security policies. The developers are not responsible for any misuse or damage caused by this software. Always ensure you have permission to use this tool in your intended environment.


## **Features**
- **File Transfer**: Upload and download files between server and client.
- **Screenshot Capture**: Take screenshots from the client's system.
- **System Information Gathering**: Retrieve detailed system and security software information.
- **Camera Access**: Capture images from the client's webcam.
- **Notifications**: Send and display notifications on the client system.
- **Help Menu**: Easy access to command information and usage.

## **Installation**
To set up `BackdoorSim`, you will need to install it on both the server and client machines.

1. Clone the repository:

   ```shell
   $ git clone https://github.com/HalilDeniz/BackDoorSim.git
   ```

2. Navigate to the project directory:

   ```shell
   $ cd BackDoorSim
   ```

3. Install the required dependencies:

   ```shell
   $ pip install -r requirements.txt
   ```
## **Usage**
After starting both the server and client, you can use the following commands in the server's command prompt:

- `upload [file_path]`: Upload a file to the client.
- `download [file_path]`: Download a file from the client.
- `screenshot`: Capture a screenshot from the client.
- `sysinfo`: Get system information from the client.
- `securityinfo`: Get security software status from the client.
- `camshot`: Capture an image from the client's webcam.
- `notify [title] [message]`: Send a notification to the client.
- `help`: Display the help menu.

## **Use**
You can use windows shell commands to get or put files, change your location, start application like below
- `start [application_name or link]`: start application or link you want.
- `dir`: show files your location.
- `cd`: change path.

## **Disclaimer**
BackDoorSim is developed for educational purposes only. The creators of BackDoorSim are not responsible for any misuse of this tool. This tool should not be used in any unauthorized or illegal manner. Always ensure ethical and legal use of this tool.
