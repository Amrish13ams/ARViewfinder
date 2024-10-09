# ARViewfinder

ARViewfinder is an augmented reality application that uses Vuforia to recognize images and display 3D models in real-time.

## Setup Instructions

1. **Download Vuforia SDK**:
   Visit [Vuforia Developer Portal](https://developer.vuforia.com/) to download the SDK.

2. **Create a New Unity Project**:
   Open Unity and create a new 3D project.

3. **Import Vuforia SDK**:
   - Go to `Assets` > `Import Package` > `Custom Package` and select the downloaded Vuforia SDK.

4. **Set Up Vuforia**:
   - Go to `Window` > `Vuforia Configuration` and enter your license key.
   - Enable the `Vuforia` feature in the player settings.

5. **Add an Image Target**:
   - Create an `Image Target` in your scene (`GameObject` > `Vuforia` > `Image` > `Image Target`).
   - Configure the target by uploading an image in the Vuforia Target Manager and setting it as your Image Target.

6. **Add a 3D Model**:
   - Create or import a 3D model in Unity.
   - Drag the model as a child of the Image Target.

7. **Build and Run**:
   - Build your project for your target device (Android or iOS).

## Notes
- Ensure your device camera is set up correctly to test image recognition.
- Use sample images available in the Vuforia Target Manager for testing.
