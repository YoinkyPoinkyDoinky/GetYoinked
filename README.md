# Sorry.

## Note

Hello. If you are reading this, that says that you have either fallen for a phishing attack, your device (and likely network) has been compromised, or your looking into some smaller repos on GitHub.

If the first is the case, your system's and network's information has been published here. Here is the information that was pulled and in the format it is pulled in:

## Data

Current user: [user]

City: [city]

Region: [state]

Zip-code: [zip code]

Private hostname: [computer name]

Private IP: [network / internal ipv4]

Public IP: [outfacing / worldwide ipv4]

SSID: [network name]

Internet provider: [isp]

Platform: [OS]

Device Name: [computer name]

Node: [computer's node]

OS Version: [OS version]

Machine Architecture: [cpu arch]

Processor: [processor family]

## Removal

I would first, like to start off by saying sorry. Secondly, look for the files named "runner.py", "upload.py" "install.py", "Per.py", and finnaly any .exe file.

## How it works

### Bordie.exe and install.py

The .exe script (normally bordie.exe) is what creates "install.py", a file that either creates all files from scratch with no internet connection or pulls web requests to install them along with adding per.py to startup. 

### runner.py and upload.py

runner.py collects the information as stated above, then upload.py sends the information out to this repo after encoding it in base64.

### GETSHITON.txt

If you see this file, it is likely too late. GETSHITON.txt is a file for installing the persistance software, if it doesnt exist then you are fine.
