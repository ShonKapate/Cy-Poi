# Hand Tracking Module

This Python module utilizes OpenCV, MediaPipe, and PyAutoGUI to perform real-time hand tracking using a webcam feed.

## Overview

This module tracks hand movements in real-time using the MediaPipe library to detect hand landmarks. It then utilizes PyAutoGUI to control the mouse cursor based on hand movements. The module is useful for implementing gesture-based controls or interactive applications.

## Dependencies

- OpenCV (`cv2`)
- MediaPipe (`mediapipe`)
- PyAutoGUI (`pyautogui`)

Make sure to install these dependencies before using the module.

## Usage

1. Import the module and initialize it:

    ```python
    import hand_tracking_module as htm

    hand_tracker = htm.HandTracker()
    ```

2. Start the hand tracking:

    ```python
    hand_tracker.start_tracking()
    ```

3. Press 'q' to exit the tracking.

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or bug fixes, feel free to open an issue or create a pull request.

## License

This module is licensed under the [MIT License](LICENSE).
