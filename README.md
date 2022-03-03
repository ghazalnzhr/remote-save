## The following is a manual for saving images through open mv
The code allows you to save images in your own device. *Connection with the USB Cable is required*

Both of the codes have a shared ```main.py```


# Streaming the image remotly

Requirements:
'''pip install pyserial'''
'''pip install pygame'''

Setup steps:
1- Save main.py on open mv
2- Eject the camera and connect it again 
(WARN: DO NOT CONNECT THE OPEN MV IDE TO IT)
3- The camera ain't gonna do any led flashing etc, leave it as it is
4- Run: ```python rpc_image_blah_blah_blah.py```
5- Pick the COM -> usually COM7
6- The frame buffer will open up automatically

### example terminal output:
'''36.49635314941406
36.49635314941406
36.49635314941406
36.49635314941406
36.49635314941406
36.630035400390625
36.630035400390625
36.630035400390625
36.630035400390625'''

**you can find the youtube video [here](https://www.youtube.com/watch?v=WRHrqlKBZ3s)**

