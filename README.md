# HDS Optrix release
## How to set up a new device

Got to http://cloud.highwaydata.co.uk/

1. Create a new client group http://cloud.highwaydata.co.uk/group/add/client and assign the right users to this group
2. Edit the group and add new devices
3. Go to the device page to find the device UUID
4. Go to the user account and click "Key authentication" to get the key - "Device Apikey"

Go to the Optrix device and open the setting form by clicking the gear icon at the top right of the screen

1. Click "Unlock" button at the top right of the screen and input password
2. Click "Reset" button at the bottom of "General" tab to wipe out the old data 
3. After Optrix app restarts, if the roller sensor was connected, the "Vehicle" tab in the setting form will require setting up the roller's information (set "Vehicle Min Speed" to 1 Mile/Hour)
4. Go to "General" tab, click "Unlock" button at the top right of the screen and input password again
5. Copy the device UUID from the cloud to "Device UUID"
6. Copy the key to "Device Apikey"
7. Change "Screen Direction" if the device is not installed with the default landscape direction
8. Click the "Save" button at the top right of the screen
9. After going back to the Home screen (Projects list), wait Optrix to sync data from HDS Cloud (If the newwork is not good enough, try to restart at a better location)
