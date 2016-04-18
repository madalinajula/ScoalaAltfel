void setup() {
   pinMode (2,OUTPUT);
   pinMode (3,OUTPUT);
   pinMode (4,OUTPUT);
   pinMode (5,OUTPUT);
   pinMode (6,OUTPUT);
   pinMode (7,OUTPUT);
   pinMode (8,OUTPUT);
   pinMode (9,OUTPUT);
   pinMode (10,OUTPUT);
}

void loop() {
  int i;
  for(i=2;i<=10;i++)
  { digitalWrite(i,HIGH);
    delay(100);
    digitalWrite(i,LOW);
    delay(100);
  }
  digitalWrite(2,HIGH);
  digitalWrite(3,HIGH);
  delay(50);
  for(i=4;i<=10;i++)
    digitalWrite(i,HIGH);
    delay(50);
  digitalWrite(5,HIGH);
   delay(500);
   for(i=2;i<=10;i++)
   digitalWrite(i,LOW);
   delay(100);
}
   