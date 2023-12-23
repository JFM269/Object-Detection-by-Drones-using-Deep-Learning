# Drone-with-Object-Tracking
- Assembled a DM002 Remote Control Quadcopter with camera
- Recorded video from the drone camera in real-time
- Transmitted the video capture to device using WiFi UAV app
- Implemented the pre-existing YOLO model(you-only-look-once) and faster R-CNN for object detection and tracking
- The model is capable of detecting and naming multiple objects on a single video frame from a wide range of options (human, umbrella, bottle, etc)
- Coded in Python using libraries like Numpy, OpenCV, Darknet & COCO dataset.

![image](https://github.com/JFM269/Object-Detection-by-Drones-using-Deep-Learning/assets/87769268/ca2829e6-5e75-476d-a97d-6d93f7a091d0)

# Steps for Assembling
-	<b>Assemble the frame:</b> Follow the instructions that come with your frame to assemble it.
-	<b>Install the motors and ESCs:</b> Attach the motors to the frame and connect them to the ESCs (Electronic Speed Controllers) using the appropriate wiring.
-	<b>Install the flight controller:</b> Mount the flight controller to the frame and connect it to the ESCs and other components.
-	<b>Add the battery and power distribution board:</b> Install the battery and power distribution board, which connects the battery to the flight controller and other components.
-	<b>Attach the propellers:</b> Attach the propellers to the motors, making sure they are securely fastened
-	<b>Calibrate the flight controller:</b> Follow the instructions provided with the flight controller to calibrate it, which involves setting up the quadcopter's orientation and configuring other settings.

![image](https://github.com/JFM269/Object-Detection-by-Drones-using-Deep-Learning/assets/87769268/4a12a742-2e20-4bd6-9658-267f566a8951)

# Specifications of the Drone 

![image](https://github.com/JFM269/Object-Detection-by-Drones-using-Deep-Learning/assets/87769268/81947cee-f00a-4092-a44c-7bec2a5c248e)

![Drone9](https://github.com/JFM269/Object-Detection-by-Drones-using-Deep-Learning/assets/87769268/730bc8f7-e379-4187-9729-fd49288cf598)


# Displaying Video Footage on Laptop

Next, we connected the camera present on the drone to a laptop using WiFi. This task involved the following steps:
-	<b>Install a compatible WiFi module:</b> The DM002 quadcopter has a specific WiFi module that is compatible, and it needs to be bought.
-	<b>Turn on the quadcopter:</b> Turn on the quadcopter by connecting the battery and pressing the power button.
-	<b>Enable WiFi on the device:</b> Enable WiFi on the device and search for available networks. Look for the network name of the WiFi module that was installed on the quadcopter.
-	<b>Connect to the WiFi network:</b> Select the network name of the WiFi module on the device and enter the password, if required.
-	<b>Launch the quadcopter app:</b> Launch the quadcopter app on the device. The app should automatically detect and connect to the quadcopter via WiFi.
-	<b>Control the quadcopter:</b> We can see the live camera feed of the drone now from the device and can use it to control all the movement via joystick.

Using WiFi UAV app as shown below, we transmitted the video footage from drone camera to laptop screen using WiFi. We then performed object tracking on the footage.

![image](https://github.com/JFM269/Object-Detection-by-Drones-using-Deep-Learning/assets/87769268/dd67e572-c5ba-42de-b360-828e633fbbd3)



