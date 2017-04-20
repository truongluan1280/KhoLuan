byte ledPin[] = {0,1,2,3,4,5,6,7};
byte pinCount; 
void setup() {
  pinCount = sizeof(ledPin);  
  for (int i=0;i<pinCount;i++) {
    pinMode(ledPin[i],OUTPUT);  
    digitalWrite(ledPin[i],LOW); 
  }
}
void loop() {
  //từ phải sang trái

  for (int i=0; i < pinCount; i++) 
  {
    digitalWrite(ledPin[i],HIGH); 
    delay(500);
  }
  
  for (int i = 0;i < pinCount; i ++) 
  {
    digitalWrite(ledPin[i],LOW); 
    delay(500);
  }
  //từ trái sáng phải
    for (int i=pinCount; i >=0; i--) 
  {
    digitalWrite(ledPin[i],HIGH); 
    delay(500);
  }
  
  for (int i = pinCount;i >=0; i --) 
  {
    digitalWrite(ledPin[i],LOW); 
    delay(500);
  }
}
