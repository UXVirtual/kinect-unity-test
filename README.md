Kinect Unity Test Project
=========================

A test project for Kinect 2.0 integration with Unity 4.

Setup
-----

1. Check out this repository and download the [Kinect 2.0 Unity Pro plugin](http://go.microsoft.com/fwlink/?LinkId=513177).
2. Expand the .zip file, and move `Kinect.2.0.1410.19000.UnityPackage` to a well known <location>
3. Open Unity Pro (you need to have a Pro edition to pull in custom packages and plugins)
4. Open the Unity project from the repository in Unity Pro.
5. Click on the menu item Assets -> Import Package -> Custom Package...
6. Navigate to the <location> from step 2
7. Select the `Kinect.2.0.1410.19000.UnityPackage`
8. Click "Open"
9. Click "Import" in the lower right hand corner of the "Importing Package" Dialog (which Unity will launch after step 7)
10. Two sample scenes are available in `Assets/GreenScreenScene.unity` and `Assets/KinectViewScene.unity`
11. If you wish to use VisualGestureBuilder within Unity, repeat steps 2 through 9 with `Kinect.VisualGestureBuilder.2.0.1410.19000.unitypackage`
12. If you wish to use the Face functionality within Unity, repeat steps 2 through 9 with `Kinect.Face.2.0.1410.19000.unitypackage`