# Azure-IoT-with-Raspberry-Pi

<!DOCTYPE html>
<html>
<body>
  <h1>Connecting DHT11 Temperature and Humidity Sensor with Azure IoT Hub using Raspberry Pi</h1>
  <h2>Prerequisites</h2>
  <ul>
    <li>Raspberry Pi (any model) with an operating system installed (e.g., Raspbian)</li>
    <li>Temperature and humidity sensor (e.g., DHT11, DHT22, or similar)</li>
    <li>Azure subscription</li>
    <li>Azure IoT Hub instance created</li>
    <li>Python 3.x installed on Raspberry Pi</li>
  </ul>
  <h2>Configuration</h2>
  <p>Before running the code, you need to configure the connection to your Azure IoT Hub. Follow these steps:</p>
  <ol>
    <li>Open the <code>raspberryprogram.py</code> file in a text editor.</li>
    <li>Replace the placeholders (<code>YOUR_IOT_HUB_CONNECTION_STRING</code>) with your Azure IoT Hub connection string. You can find the connection string by creating a device in the Azure portal under your IoT Hub.</li>
    <li>Save the changes and close the file.</li>
  </ol>
  <h2>Running the Code</h2>
  <p>To run the code and start sending sensor data to Azure IoT Hub, follow these steps:</p>
  <ol>
    <li>Connect the temperature and humidity sensor to your Raspberry Pi following the sensor's wiring instructions. Make sure it's properly connected.</li>
    <li>Make sure your Raspberry Pi is connected to the internet.</li>
    <li>From the repository's directory, run the Python script:</li>
    <code>python3 raspberryprogram.py</code>
    <li>The script will continuously read the sensor data and send it to your Azure IoT Hub.</li>
    <li>You can monitor the data being sent by checking the Azure CLI.</li>
  </ol>
  <h2>Acknowledgments</h2>
  <ul>
    <li><a href="https://github.com/Azure/azure-iot-sdk-python">Microsoft Azure IoT SDK for Python</a></li>
    <li><a href="https://www.raspberrypi.org/">Raspberry Pi</a></li>
  </ul>
  <h2>Disclaimer</h2>
  <p>This code is provided as-is, without any warranties or guarantees. Use at your own risk.</p>
</body>
</html>
