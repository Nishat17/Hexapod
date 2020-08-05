/Lift the body up:
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
//  pinMode(forward8, OUTPUT);
  //pinMode(backward8, OUTPUT);
  pinMode(forward9, OUTPUT);
  pinMode(backward9, OUTPUT);
  pinMode(forward10, OUTPUT);
  pinMode(backward10, OUTPUT);
  pinMode(forward11, OUTPUT);
  pinMode(backward11, OUTPUT);
  pinMode(forward12, OUTPUT);
  pinMode(backward12, OUTPUT);
   }
  void loop()
  {
      digitalWrite(forward1,LOW);
     digitalWrite(backward1,HIGH);
     digitalWrite(forward3,LOW);
    digitalWrite(backward3,HIGH);
    digitalWrite(forward5,LOW);
   digitalWrite(backward5,HIGH);
     digitalWrite(forward7,LOW);
    digitalWrite(backward7,HIGH);
     digitalWrite(forward9,LOW);
    digitalWrite(backward9,HIGH);
     digitalWrite(forward11,LOW);
    digitalWrite(backward11,HIGH);
  }




