# Video Stabilisation

Use basic opencv-python functionality to reduce shaking in a given video sample.

## Tasks

- [ ] Use the streetlamp at the corner to track the movement of the camera.

- [ ] Find the best crop for each frame and crop the frames so that it appears as if streetlamp is stationary. This method would generally be applied in case of a stationary camera capturing moving targets. It may not appear that clean.

- [ ] To tackle the problem of camera translation and rotation, calculate the camera projection matrix (how?! we dont know the location of any points) and then use perspective warping on each frame.

### Additional Tasks

- [ ] Make the video loop (how?! We want to have a smooth transition from the last frame to the first one).

## Files

A sample file is given in the res directory. The full file can be downloaded from [link](https://drive.google.com/file/d/15JQs1dCo_6Bkuz8K3pDZU4ajzdTBODGI).
