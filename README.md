# orange_vision_helper
This projects aims to solve a ton of real world problems. It will make use of open source CV, and speech tools to solve following problems : 

1. Identification of common objects such as books,cans,clothes in my room and assigning them following information 
    last time object was seen
    location of object
    home location of object ( each object must have a base / home location when house is in clean state )
    id of object
    name of object
    image of object
 
 2. Tracking of Objects
 
 3. automatic object clustering rules for giving cleaning suggestions :
    everytime a group of similar objects are found in room, an opportunity object will be generated

Software Stack

Vision 
  - Object Detection Backend : Darknet / Yolov3
  - Image similarity Backend : 
  
 Speech
  - ASR Backend - Kaldi
  
