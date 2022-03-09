# wifi-deauth-tool
An easy to use tool that allows one to deauth users from wifi connections
# Usage
Upon running the python file, you will be asked to input different values into the terminal. These include the name of your wifi card and the target BSSID
### Wifi Card
You must make sure that the designated wifi card is in monitor mode. This cannot be intergrated due to licencing and must manually be done using the command << sudo airmon-ng <<insert name of wifi card>> mode monitor >>
If you do not know the name of your wifi card then first input the command << ifconfig >> into the terminal. Then complete the above step. After this, the name of the wifi card often changes, so you must double check if it has by re-inputting the command << ifconfig >> and finding the changed name. 
Using these steps, you can then input the correct value into the terminal, which will allow you to use the tool.
### BSSID
If you do not know the intended BSSID target then our other tool does manage to locate this. This is also found on github [here](https://github.com/h00per5/bssid-locator).
  
