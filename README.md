# BlinkName
Task 2.1P Photon - First Name Blinky

int led = D7;
void setup() 
{
    pinMode(led, OUTPUT);
    digitalWrite(led,LOW);

}

void dot() 
{
    digitalWrite(led,HIGH);
    delay(1000);
    digitalWrite(led,LOW);
    delay(1000);

}

void dash() 
{
    digitalWrite(led,HIGH);
    delay(4000);
    digitalWrite(led, LOW);
    delay(1000);
    
}

void loop() 
{
    dot();
    dash();     //"L"          
    dot();
    dot();
    
    dot();      //"I"
    dot();
    
    dash();
    dot();      //"Y"
    dash();
    dash();
    
    dot();      //"A"
    dash();
    
    dash();     //"N"
    dot();
    
    dot();      //"A"
    dash();
    
}
