# Structure from Motion (SfM)
## Data 
The data consist of 6 images provided which are from different camera perspectives of the same building with fixed camera parameters.
<p align="center">
  <img src="P3Data/1.png" width="256">
  <img src="P3Data/2.png" width="256">
  <img src="P3Data/3.png" width="256">
  <img src="P3Data/4.png" width="256">
  <img src="P3Data/5.png" width="256">
</p>

The target poses of the camera of each image is as follows:
<p align="center">
  <img src="Results/Camera Poses.png" width="512">
</p>

## Results
The following is the result obtained from Linear and Non-Linear triangulation for camera poses 1 and 2.
<p align="center">
  <img src="Results/SoS_Linear_NonLinear.png" width="512">
</p>

The below is the result of using Linear and Non-Linear Perspective-n-Points (PnP) on the camera poses.
<p align="center">
  <img src="Results/PnP.png" width="512">
</p>

## Running the code
Run the following command in the terminal window for the program to start

```json
python3 Wrapper.py
```
