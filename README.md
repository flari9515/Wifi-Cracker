> [!TIP] 
> # How to run
> 
> ## Install Python
> 
> 1. Go to the official Python website: https://www.python.org/downloads/release/python-3139/
> 2. Scroll down to the files part. Then download the Windows installer (64-bit)
> 3. Once downloaded, run the installer.
> 4. ✅ Important: On the first screen of the installer, check the box that says
> “Add Python to PATH” before clicking Install Now.
> ## How to download the repo
> Click the button below to download the code as a .zip:
>
> <a href="https://github.com/flari9515/Wifi-Cracker/archive/refs/heads/main.zip"><img src="https://img.shields.io/badge/⬇️_Download_ZIP-2ea44f?style=for-the-badge&logo=github&logoColor=white" alt="Download ZIP"></a>
>
> 
> Now extract the .zip folder
> 
> ## Run the script
> 
> Open the command prompt inside the extracted folder and run:
>
> `py aircrack.py`
> 
>  or
> 
> `python aircrack.py`

# GUI-wifi-cracker
Would you like to be able to extract WPA/WPA2 handshakes from FlipperZero's captured .pcap files, and analyze them with hashcat, and find out passwords JUST IN ONE CLICK?

This is the GUI (Graphic User Interface) version of my other script and repo [`flipperzero-CLI-wifi-cracker`](https://github.com/grugnoymeme/flipperzero-CLI-wifi-cracker), i just wanted to make the process easyest as possible, and this is the result.  
         

### BEFORE RUNNING THE SCRIPT:

```
cd dictionary/brutefoce_attack

pip install -r requirements.txt
```      

---
## Extarcion of .pcap file.

You can automatize the extraction of .pcap files from flipper zero, using the [@0xchocolate](https://github.com/0xchocolate) 's companion app, of the [@JustCallMeKoKo's](https://github.com/justcallmekoko) ESP32marauder. Once you've connected the devboard and opened the app,follow these instructions:
```
Menu       
Apps       
WIFI / GPIO / GPIO EXTRA            
[ESP32] WiFi Marauder       
Scripts   
[+]ADD SCRIPT    
< Enter a name for your script >   
Save    
< Select your script >    
[+]EDIT STAGES    
[+]ADD STAGE    
[+]Deauth     
< Select Deauth >     
Timeout 1    
Save    
Back    
[+]ADD STAGE    
[+]Sniff RAW     
< Select Sniff RAW >    
Timeout 15 (or 10, maybe also 5 is ok)     
Save    
Back     
Back     
[*]SAVE
```
  
---
# Disclaimer
This tool is not developed by the Flipper Zero staff.    
Please note that the code you find on this repo is only proposed for educational purposes and should NEVER be used for illegal activities.

o