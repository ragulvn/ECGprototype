const int ecgPin = A0;  // AD8232 Output connected to A0

void setup() {
  Serial.begin(9600); // Initialize serial communication at 9600 baud

  Serial.println("ECG Reading from the prototype:");   // Print a header for the Serial Plotter
}

void loop() {
  int ecgValue = analogRead(ecgPin);    // Read the analog value from the ECG sensor (0-1023)
  
  Serial.println(ecgValue);    // Send the ECG value to the Serial Plotter

  delay(2);  // Small delay to make the plot more readable
}
