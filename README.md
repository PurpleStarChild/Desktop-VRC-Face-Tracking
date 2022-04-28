# Desktop-VRC-Face-Tracking
This is meant as repository for storing my documentation on getting face tracking working in VR Chat on desktop via OSC. 

## Goals
The scope of this is primarily to cover the overview of the process I followed, but to reference specific guides where appropriate and focus on notating gaps or problems I found.

- [] backend/data flow
  - [] Facial Tracking Capture
    - [] Define pro's/cons/why's of remote vs local capture
  - [] OSC Quirks
    - [] Which parameters to track
    - [] Limitations of VRC implementation
- [] Blender Specifics
  - [] Eye animation 
  - [] Avatar Blend Shapes
- [] Unity Specifics
  - Animation definitions
- [] VRC Specifics 
  

## Current implementation
### Data Flow
Video capture device (either webcam on PC / meowface via Android) > VSeeFace(via the openseeface backend) > VR Chat Client

## Contributions
I expect to be the sole/primary contributor to this repository. That said I gladly welcome input/feedback/PR's/etc. Please make sure whatever documentation that is submitted has sources appropriately linked/referenced, and preferably with github optimized images. I reserve the right to decline PR's that are off topic, or I otherwise deem not to be a good fit for this repo. 
