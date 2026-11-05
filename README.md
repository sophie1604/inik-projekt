# inik-projekt
// C++ code
//
void setup()
{
  pinMode(0, OUTPUT);
  pinMode(LED_BUILTIN, OUTPUT);

  digitalWrite(0, HIGH);
  digitalWrite(LED_BUILTIN, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(LED_BUILTIN, LOW);
  digitalWrite(0, LOW);
}

void loop()
{
  delay(10); // Delay a little bit to improve simulation performance
}
