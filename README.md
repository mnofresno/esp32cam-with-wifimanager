# esp32cam-with-wifimanager

## Overview
This project integrates the WifiManager Library with the ESP32Cam software, enabling easy Wi-Fi configuration for your ESP32 camera module. With this setup, users can effortlessly connect their ESP32Cam to a Wi-Fi network without hardcoding credentials, making it ideal for IoT applications.

## Features
- **Easy Wi-Fi Configuration**: Automatically creates a Wi-Fi access point for easy connection setup.
- **Camera Functionality**: Leverages the ESP32Cam capabilities for capturing images and streaming video.
- **User-Friendly Interface**: Allows users to connect to the ESP32Cam via a web interface to configure Wi-Fi settings.

## Getting Started

### Prerequisites
- An ESP32Cam module
- Arduino IDE installed with ESP32 board support
- WifiManager Library (can be installed via the Arduino Library Manager)

### Installation
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/esp32cam-with-wifimanager.git
   ```
2. Open the `esp32cam-with-wifimanager.ino` file in the Arduino IDE.
3. Ensure you have the required libraries installed (WifiManager, ESP32 board definitions).
4. Connect your ESP32Cam to your computer and select the appropriate board and port in the Arduino IDE.
5. Upload the sketch to your ESP32Cam.

### Usage
1. After uploading, open the Serial Monitor to view the IP address of the ESP32Cam.
2. Connect to the Wi-Fi network created by the ESP32Cam (SSID will be something like `ESP32-CAM`).
3. Open a web browser and navigate to `http://192.168.4.1` (or the IP address shown in the Serial Monitor).
4. Use the web interface to enter your Wi-Fi credentials and connect to your network.

## Contributing
Contributions are welcome! If you have suggestions for improvements or features, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- [WifiManager Library](https://github.com/tzapu/WiFiManager) for providing an easy way to manage Wi-Fi connections.
- [ESP32Cam](https://github.com/espressif/esp32-camera) for the camera functionality.

## Support
For any questions or issues, please open an issue in this repository or contact the maintainer.
