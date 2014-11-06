# MMA 7455 is 3-axis Digital Tilt Sensor. 

Bought from - 


http://www.ebay.in/itm/171469436597?ssPageName=STRK:MEWNX:IT&_trksid=p3984.m1439.l2649 

Wiring is simple 

GND - To Spark  GND  
VCC - To Spark  +3.3V (Note: this module has onboard 3.3 V regulator)  
SCL - To Spark D1  
SDA - To Spark D0  

You should see output like this, if things work well - 

X = 235   Y = 176   Z = 252  
X = 244   Y = 222   Z = 64  
X = 244   Y = 230   Z = 65  
X = 242   Y = 233   Z = 67  
X = 247   Y = 231   Z = 67  
X = 249   Y = 230   Z = 66  
X = 251   Y = 231   Z = 65  
X = 244   Y = 196   Z = 58  
X = 249   Y = 42   Z = 247  
X = 249   Y = 42   Z = 248  

Note, that you can also set the offsets in the .INO file.
