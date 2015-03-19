const int trig =2;
const int echo= 3;

int sure=0;
int mesafe=0;

void setup() {
pinMode(trig, OUTPUT);
pinMode(echo, INPUT);
Serial.begin(9600);
}

void loop() {
digitalWrite(trig, HIGH);
delayMicroseconds(1000);
digitalWrite(trig, LOW);
sure = pulseIn(echo, HIGH);
mesafe = (sure/2) / 29.1;
Serial.print("Mesafe: ");
Serial.print(mesafe);
Serial.println(" cm");
delay(250);
}
