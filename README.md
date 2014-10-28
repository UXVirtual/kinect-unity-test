Kinect Unity Test Project
=========================

A test project for Kinect 2.0 integration with Unity 4.

Depencencies
------------

* [Kinect 2.0 Unity Pro plugin](http://go.microsoft.com/fwlink/?LinkId=513177)


Setup
-----

1. Check out the repository
2. Download the [Kinect 2.0 Unity Pro plugin](http://go.microsoft.com/fwlink/?LinkId=513177).
3. Expand the .zip file, and move `Kinect.2.0.1410.19000.UnityPackage` to a well known <location>
4. Open Unity Pro (you need to have a Pro edition to pull in custom packages and plugins)
5. Open the Unity project from the repository in Unity Pro.
6. Click on the menu item Assets -> Import Package -> Custom Package...
7. Navigate to the <location> from step 3
8. Select the `Kinect.2.0.1410.19000.UnityPackage`
9. Click "Open"
10. Click "Import" in the lower right hand corner of the "Importing Package" Dialog (which Unity will launch after step 7)
11. Two sample scenes are available in `Assets/GreenScreenScene.unity` and `Assets/KinectViewScene.unity`
12. Repeat steps 3 through 9 with `Kinect.VisualGestureBuilder.2.0.1410.19000.unitypackage` to enable VisualGestureBuilder within Unity
13. Repeat steps 3 through 9 with `Kinect.Face.2.0.1410.19000.unitypackage` to enable Face functionality within Unity
14. Save the project and restart Unity to enable all imported packages.

Version Control
---------------

Version control settings for this project have been set as follows to make compatible with git:

* Unity Remote Device: None
* Version Control Mode: Visible Meta Files
* WWW Security Emulation Host URL: leave unchanged
* Asset Serialization: Force Text
* Default Behavior Mode: 3D
* Sprite Packer Mode: Disabled

See the .gitignore file in the repository for a list of Unity files that can be safely excluded from the project in the repository. These are re-generated.