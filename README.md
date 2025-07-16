# ambulance lights

---

## code for this: 

``` c++


int red = 12;
int blue = 13;

void setup()

{

pinMode(red, OUTPUT);

}

void loop(){

// the first LED is made to blink one time

digitalWrite(red, HIGH);
  digitalWrite(blue, LOW);

delay(1000);

// delay time in milliseconds

digitalWrite(red, LOW);
  digitalWrite(blue, HIGH);


delay(1000);

}


