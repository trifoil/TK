// Define your data structure
struct SensorData {
  float temperature;
  int humidity;
  // Add more fields as needed
};

void setup() {
  // Initialize the serial communication
  Serial.begin(9600);
  Serial.print("launching...");
}

void loop() {
  // Create an instance of the SensorData struct
  SensorData data;

  // Populate the data structure with sample values
  data.temperature = 255;
  data.humidity = 60;

  // Send the data structure over serial
  Serial.write((uint8_t*)&data, sizeof(data));

  // Delay before sending the next data
  delay(500);
}
