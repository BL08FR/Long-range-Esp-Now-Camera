# Long-range-Esp-Now-Camera

Camera sending photo over ESP-NOW (long range) and display it on webserver (classic wifi).
The camera must be able to see the router AP at startup not to connect on it but to find the correct wifi channel.
The receiver connect to the router AP and spread webserver on it to show photos, it receive the photo sent by the camera and update the web page.

Inspired from Randomnerdtutorial for the webserver: https://randomnerdtutorials.com/esp32-esp-now-wi-fi-web-server/
Inspired from TenoTrash for the RSSI calculation: https://github.com/TenoTrash/ESP32_ESPNOW_RSSI
Inspired from Tal Ofer for Esp-now transfert: https://github.com/talofer99/ESP32CAM-Capture-and-send-image-over-esp-now
This is the screen portion of the code for more information
https://www.youtube.com/watch?v=0s4Bm9Ar42U
