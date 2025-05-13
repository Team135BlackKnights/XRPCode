# XRP Code

This is our library for the XRP robots, which _**actually handles the connection and disconnect protocols**_.

# Install Guide

1. Connect over USB to the XRP. 
2. Hit Connect XRP (in the top right) on [the XRP Code Editor](https://xrpcode.wpi.edu/)
    - Hit Over USB, *you should now be connected to the XRP*
3. At the bottom of the screen, confirm you see MicroPython v1.21.0 or later
    - If you do NOT have 1.21.0 or later, [download this file](https://micropython.org/resources/firmware/SPARKFUN_XRP_CONTROLLER_BETA-20250415-v1.25.0.uf2)
    - Turn off the XRP
    - Find the "bootSel" button on the board. Press and hold it while turning back on the XRP
    - It should now be viewable in File Explorer in Windows. Find the drive, and click and drag the file downloaded in step 1 here.
    - Go back to the XRP Code Editor, and follow the steps it instructs. **READ these instructions carefully. Failure to do as it asks will require a repeat of the process from step 2**
4. Confirm you have a folder named `lib` in `\`.
    - Confirm it has folders `XRPLib`, `ble`, and `phew`
       1. If you DO NOT have either `lib`, or any of the folders, go [here](https://blanksourcecode.com/)
       2. Upload these via the File menu, using Upload to XRP such that `\lib\XRPLib\`, `\lib\ble\`, `\lib\phew\` are all present.
    - Upload via the File menu, using Upload to XRP, this [pestolink.py](https://github.com/Team135BlackKnights/XRPCode/blob/main/pestolink.py)
       1. If it already exists, delete it first, then upload it to `\lib\pestolink.py`
5. Upload via the File menu, using Upload to XRP, this [pestolink_example.py](https://github.com/Team135BlackKnights/XRPCode/blob/main/pestolink_example.py).
    - If it already exists, delete it first, then upload it to `\pestolink_example.py`
6. Open `pestolink_example.py`, rename your robot, and hit Run.
7. Go to [Pesto Link Online](https://pestol.ink/) and connect over Bluetooth.
8. If you see a voltage, It works!!!

# FAQ

### I disconnect the USB cable, and restart, and it isn't available at [Pesto Link Online](https://pestol.ink/)
Turn on and off the device once more. It should appear. If it doesn't, go to step 6 of the Install Guide
