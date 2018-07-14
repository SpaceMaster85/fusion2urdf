# fusion2urdf

This is a fusion 360 script to export urdf from fusion 360 directly.

## How to use

As an example, I'll export a urdf file from this cool fusion360 robot-arm model(https://grabcad.com/library/industrial-robot-10).
This was created by [sanket patil](https://grabcad.com/sanket.patil-16)

#### At Fusion 360

At first, download this repository and unzip at anywhere you like. The "URDF_Exporter" in this repository is the script to install into your fusion 360.

Copy and paste URDF_Exporter at the repository where your fusion scripts locate. In windows, it is usually at 'C:\Users\username\AppData\Roaming\Autodesk\Autodesk Fusion 360\API\Scripts'



#### At your ROS environment

Place this repository at your own ROS workspace. "catkin_ws" is used in this example.
Then, run catkin_make in catkin_make.

```bash
cd ~/catkin_ws/src
git clone git@github.com:syuntoku14/fusion2urdf.git
cd ..
catkin_make
```

**convertSTL.rb** was created by [@Chris Polis](https://github.com/cmpolis/convertSTL#author)
