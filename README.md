# PlaneTracking and object placement-ARFoundationUnity3D
Assests and script for PlaneTracking and object placement

- Make sure that ARcore (ARKit for iOS) and ARfoundation are there in Windows>Package manager
- Next go to File> Open Scene > Assets > 0-AR-MainScene
- Go to File > Build Settings > select and switch to Android platform
- Once done open Player settings (bottom left on build settings) > make sure that the XR management has ARcore in android (for iOS it should be ARKit)
- make sure that the rendering API is set to OpenGL ES 3 for android and Metal for iOS (if there is vulkan then select and remove it) and minimum API level at 24.
- Close player setting and connect your Android/iOS device where you should have already enabled USB debugging from the developers option of your phone.
- Allow for USB debugging and under Run Device select your device
- Build and run 

Resources from existing works were used to build this code
