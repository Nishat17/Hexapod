const int forward1 =0;
const int backward1=1;
const int forward2=2;
const int backward2=3;
const int forward3=4;
const int backward3=5;
const int forward4 =6;
const int backward4=7;
const int forward5=8;
const int backward5=9;
const int forward6=10;
const int backward6=11;
const int forward7 =12;
const int backward7=24;
const int forward8=14;
const int backward8=15;
const int forward9=16;
const int backward9=17;
const int forward10=18;
const int backward10=19;
const int forward11=20;
const int backward11=21;
const int forward12=25;
const int backward12=23;
void setup()
{
  pinMode(forward1, OUTPUT);
  pinMode(backward1, OUTPUT);
  pinMode(forward2, OUTPUT);
  pinMode(backward2, OUTPUT);
  pinMode(forward3, OUTPUT);
  pinMode(backward3, OUTPUT);
  pinMode(forward4, OUTPUT);
  pinMode(backward4, OUTPUT);
  pinMode(forward5, OUTPUT);
  pinMode(backward5, OUTPUT);
  pinMode(forward6, OUTPUT);
  pinMode(backward6, OUTPUT);
  pinMode(forward7, OUTPUT);
  pinMode(backward7, OUTPUT);
  pinMode(forward8, OUTPUT);
  pinMode(backward8, OUTPUT);
  pinMode(forward9, OUTPUT);
  pinMode(backward9, OUTPUT);
  pinMode(forward10, OUTPUT);
  pinMode(backward10, OUTPUT);
  pinMode(forward11, OUTPUT);
  pinMode(backward11, OUTPUT);
  pinMode(forward12, OUTPUT);
  pinMode(backward12, OUTPUT);
  digitalWrite(forward1,HIGH);
  digitalWrite(backward1,HIGH);
  digitalWrite(forward2,HIGH);
  digitalWrite(backward2,HIGH);
  digitalWrite(forward3,HIGH);
  digitalWrite(backward3,HIGH);
  digitalWrite(forward4,HIGH);
  digitalWrite(backward4,HIGH);
  digitalWrite(forward5,HIGH);
  digitalWrite(backward5,HIGH);
  digitalWrite(forward6,HIGH);
  digitalWrite(backward6,HIGH);
  digitalWrite(forward7,HIGH);
  digitalWrite(backward7,HIGH);
  digitalWrite(forward8,HIGH);
  digitalWrite(backward8,HIGH);
  digitalWrite(forward9,HIGH);
  digitalWrite(backward9,HIGH);
  digitalWrite(forward10,HIGH);
  digitalWrite(backward10,HIGH);
  digitalWrite(forward11,HIGH);
  digitalWrite(backward11,HIGH);
  digitalWrite(forward12,HIGH);
  digitalWrite(backward12,HIGH);
  delay(5000);

}
void loop()
{
     digitalWrite(forward1,LOW); //leg1,11 up
     digitalWrite(backward1,HIGH);
     digitalWrite(forward11,LOW);
     digitalWrite(backward11,HIGH);
     delay(10000);
     digitalWrite(forward1,HIGH); 
     digitalWrite(backward1,HIGH);
     digitalWrite(forward11,HIGH);
     digitalWrite(backward11,HIGH);//STP
     digitalWrite(forward2,HIGH);//leg1,11 forward
     digitalWrite(backward2,LOW);
     digitalWrite(forward12,LOW);
     digitalWrite(backward12,HIGH);
     delay(5000);
      digitalWrite(forward2,HIGH);
     digitalWrite(backward2,HIGH);
     digitalWrite(forward12,HIGH);
     digitalWrite(backward12,HIGH);//STOP
     digitalWrite(forward1,HIGH);//leg1,11 down
     digitalWrite(backward1,LOW);
     digitalWrite(forward11,HIGH);
     digitalWrite(backward11,LOW);
     delay(10000);
     digitalWrite(forward1,HIGH);
     digitalWrite(backward1,HIGH);
     digitalWrite(forward11,HIGH);
     digitalWrite(backward11,HIGH); //STOP
     digitalWrite(forward7,LOW); //leg3,4 up
     digitalWrite(backward7,HIGH);
     digitalWrite(forward5,LOW);
     digitalWrite(backward5,HIGH);
     delay(5000);
     digitalWrite(forward6,LOW);//leg3,4 forward
     digitalWrite(backward6,HIGH);
     digitalWrite(forward8,HIGH);
     digitalWrite(backward8,LOW);
     delay(5000);
     digitalWrite(forward6,HIGH);//leg3,4 forward
     digitalWrite(backward6,HIGH);
     digitalWrite(forward8,HIGH);
     digitalWrite(backward8,HIGH);//STOP
     digitalWrite(forward7,HIGH);//leg3,4 down
     digitalWrite(backward7,LOW);
     digitalWrite(forward5,HIGH);
     digitalWrite(backward5,LOW);
     delay(10000);
     digitalWrite(forward7,HIGH);
     digitalWrite(backward7,HIGH);
     digitalWrite(forward5,HIGH);
     digitalWrite(backward5,HIGH);//STOP
     digitalWrite(forward3,LOW);//leg2,5 up
     digitalWrite(backward3,HIGH);
     digitalWrite(forward9,LOW);
     digitalWrite(backward9,HIGH);
     delay(10000);
     digitalWrite(forward3,HIGH);
     digitalWrite(backward3,HIGH);
     digitalWrite(forward9,HIGH);
     digitalWrite(backward9,HIGH);//STOP
     digitalWrite(forward4,LOW);//leg2,5 forward
     digitalWrite(backward4,HIGH);
     digitalWrite(forward10,LOW);
     digitalWrite(backward10,HIGH);
     delay(5000);
     digitalWrite(forward4,HIGH);
     digitalWrite(backward4,HIGH);
     digitalWrite(forward10,HIGH);
     digitalWrite(backward10,HIGH);//STOP
     digitalWrite(forward3,HIGH);//leg2,5 down
     digitalWrite(backward3,LOW);
     digitalWrite(forward9,HIGH);
     digitalWrite(backward9,LOW);
     delay(10000);
     digitalWrite(forward3,HIGH);//leg2,5 down
     digitalWrite(backward3,HIGH);
     digitalWrite(forward9,HIGH);
     digitalWrite(backward9,HIGH);//STP
     digitalWrite(forward2,LOW);//all back
     digitalWrite(backward2,HIGH);
     digitalWrite(forward4,HIGH);
     digitalWrite(backward4,LOW);
     digitalWrite(forward6,HIGH);
     digitalWrite(backward6,LOW);
     digitalWrite(forward8,LOW);
     digitalWrite(backward8,HIGH);
     digitalWrite(forward10,HIGH);
     digitalWrite(backward10,LOW);
     digitalWrite(forward12,HIGH);
     digitalWrite(backward12,LOW);
     delay(5000);
     digitalWrite(forward2,HIGH);//all back
     digitalWrite(backward2,HIGH);
     digitalWrite(forward4,HIGH);
     digitalWrite(backward4,HIGH);
     digitalWrite(forward6,HIGH);
     digitalWrite(backward6,HIGH);
     digitalWrite(forward8,HIGH);
     digitalWrite(backward8,HIGH);
     digitalWrite(forward10,HIGH);
     digitalWrite(backward10,HIGH);
     digitalWrite(forward12,HIGH);
     digitalWrite(backward12,HIGH);//STP
     delay(5000);
}




