int led_1 = 8;                                //Initialize pin
int led_2 = 9;
int led_3 = 10;
int led_4 = 11;
void setup() {
  pinMode(8, OUTPUT);
  pinMode(9, OUTPUT);
  pinMode(10, OUTPUT);
  pinMode(11, OUTPUT);
}

void loop() {
                                              //for 1 way
  for (int i = 8; i <= 11; i++)
  digitalWrite(8, HIGH);
  delay(1000);
  digitalWrite(8, LOW);
  digitalWrite(9, HIGH);
  delay(1000);
  digitalWrite(9, LOW);
  digitalWrite(10, HIGH);
  delay(1000);
  digitalWrite(10, LOW);
  digitalWrite(11, HIGH);
  delay(1000);
  digitalWrite(11, LOW);
  
                                              //to return back
  digitalWrite(10, HIGH);
  delay(1000);
  digitalWrite(10, LOW);
  digitalWrite(9, HIGH);
  delay(1000);
  digitalWrite(9, LOW);
}


OR THIS WHOLE CODE CAN ALSO BE WRITTEN AS:


int pin_1 = 8;
int pin_2 = 9;
int pin_3 = 10;
int pin_4 = 11;
int i = 8;
void setup() {
  // put your setup code here, to run once:
pinMode(8,OUTPUT);
pinMode(9,OUTPUT);
pinMode(10,OUTPUT);
pinMode(11,OUTPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
 for(i=8;i<=11;i++){
 digitalWrite(i,HIGH);
 delay(1000);
 digitalWrite(i,LOW);
 }
}
