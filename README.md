# Vehicle-Detection-and-Counting-System
 Video-based vehicle detection and counting system using OpenCV. 
 
 It is made up of three main components: a detector, tracker and counter. The detector identifies vehicles in a given frame of video and returns a list of bounding boxes around the vehicles to the tracker. The tracker uses the bounding boxes to track the vehicles in subsequent frames. The detector is also used to update the trackers periodically to ensure that they are still tracking the vehicles correctly. The counter counts vehicles when they leave the frame or makes use of a counting line drawn across a road.
 
 Algorithm Used here is BackgroundSubtractorMOG.
 
 Applications:
 Traffic management and planning, Traffic control, Parking management
 
 <img width="700" height="400" alt="2021-07-28" src="https://user-images.githubusercontent.com/70203511/127349836-34f035d1-efef-4115-95cc-0570209ba40b.png">
