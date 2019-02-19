// relay-controll-using-arduino
//Controlling relay circuit using  Arduino Uno Board, by the time gap of 1000 ms

//program starts from line no. 7, Click on RAW to get program txt


#define relay A0
#define interval 1000
void setup() {
  pinMode(relay, OUTPUT);
}
void loop()
{
   digitalWrite(relay, HIGH);
   delay(interval);
   digitalWrite(relay, LOW);
   delay(interval);
}
