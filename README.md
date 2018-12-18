# Open-Loop-Control-of-OWI-Robot
# ECE6311 Demo2 Code

/* for motor M1  
*/


void setup()
 {
  pinMode(33,OUTPUT);
  pinMode(32,OUTPUT);
  pinMode(8,OUTPUT);
  pinMode(30,OUTPUT);
  pinMode(31,OUTPUT);
  pinMode(9,OUTPUT);
  pinMode(29,OUTPUT);
  pinMode(28,OUTPUT);
  pinMode(10,OUTPUT);
  pinMode(27,OUTPUT);
  pinMode(26,OUTPUT);
  pinMode(11,OUTPUT);
  pinMode(25,OUTPUT);
  pinMode(24,OUTPUT);
  pinMode(12,OUTPUT);
  pinMode(23,OUTPUT);
  pinMode(22,OUTPUT);
  pinMode(13,OUTPUT);
  }

void loop(){

delay(10000);

//Upward trajectory 1
//for Motor 1 Grabber  

digitalWrite(32,HIGH);
digitalWrite(33,LOW);
analogWrite(8,255);
delay(750);
analogWrite(8,0);
delay(1000);

//for motor M2 Hand 
digitalWrite(31,HIGH);
digitalWrite(30,LOW);
analogWrite(9,255);
delay(1000);
analogWrite(9,0);


//for motor M3 arm 

digitalWrite(28,HIGH);
digitalWrite(29,LOW);
analogWrite(10,255);
delay(1000);
analogWrite(10,0);

//for motor M4  Shoulder
/*
digitalWrite(26,HIGH);
digitalWrite(27,LOW);
analogWrite(11,200);
delay(1000);
analogWrite(11,0);
*/

//analogWrite(11,0);

//delay(500);

// for motor M5  Shoulder 

digitalWrite(24,HIGH);
digitalWrite(25,LOW);
analogWrite(12,255);
delay(3000);
analogWrite(12,0);
//analogWrite(12,0);
//delay(1000);

//************ Downward Part 1**************
/*
//For Downward moment of shoulder M4
digitalWrite(27,HIGH);
digitalWrite(26,LOW); 
analogWrite(11,200);
delay(1000);
analogWrite(11,0);
*/

//For Downward moment of elbow M3
digitalWrite(29,HIGH);
digitalWrite(28,LOW); 
analogWrite(10,255);
delay(1000);

analogWrite(10,0);

//For Downward moment of arm M2
digitalWrite(30,HIGH);
digitalWrite(31,LOW); 
analogWrite(9,255);
delay(1000);
analogWrite(9,0);
delay(1000);

//For Release M1

digitalWrite(33,HIGH);
digitalWrite(32,LOW); 
analogWrite(8,255);
delay(750);
analogWrite(8,0);
delay(15000);

//****Upward Trajectory 2********

digitalWrite(32,HIGH);
digitalWrite(33,LOW);
analogWrite(8,255);
delay(1000);
analogWrite(8,0);
delay(1000);

//for motor M2 Hand 
digitalWrite(31,HIGH);
digitalWrite(30,LOW);
analogWrite(9,255);
delay(1000);
analogWrite(9,0);



//for motor M3 arm 

digitalWrite(28,HIGH);
digitalWrite(29,LOW);
analogWrite(10,255);
delay(1000);
analogWrite(10,0);

//for motor M4  Shoulder
/*
digitalWrite(26,HIGH);
digitalWrite(27,LOW);
analogWrite(11,200);
delay(1000);
analogWrite(11,0);
*/

//analogWrite(11,0);

//delay(500);

// for motor M5  Shoulder 

digitalWrite(25,HIGH);
digitalWrite(24,LOW);
analogWrite(12,255);
delay(3000);
analogWrite(12,0);

//************ Downward Part**************
/*
//For Downward moment of shoulder M4
digitalWrite(27,HIGH);
digitalWrite(26,LOW); 
analogWrite(11,200);
delay(1000);

analogWrite(11,0);
*/

//For Downward moment of elbow M3
digitalWrite(29,HIGH);
digitalWrite(28,LOW); 
analogWrite(10,255);
delay(1000);

analogWrite(10,0);

//For Downward moment of arm M2
digitalWrite(30,HIGH);
digitalWrite(31,LOW); 
analogWrite(9,255);
delay(1000);
analogWrite(9,0);
delay(1000);

//For Release M1

digitalWrite(33,HIGH);
digitalWrite(32,LOW); 
analogWrite(8,255);
delay(750);
analogWrite(8,0);
delay(15000);


//for light
/*
digitalWrite(22,HIGH);
digitalWrite(23,LOW);
analogWrite(13,200);
delay(1000);
analogWrite(13,0);
delay(1000);
digitalWrite(22,LOW);
digitalWrite(23,HIGH); 
analogWrite(13,150);
delay(1000);
analogWrite(13,0);
delay(1000);
*/
}

 
