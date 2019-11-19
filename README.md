## Verkefni 5 (10%) 

Gerðu eftirfarandi æfingar (_e. tutorials_) á TinkerCad Arduino Projects:
[Learn Arduino](https://www.tinkercad.com/learn/project-gallery;collectionId=OMOZACHJ9IR8LRE)
og svaraðu spurningum. 

5.1  **Pushbutton (Digital Input) (2%)**
   1. _Hverju myndi það breyta ef við myndum tengja viðnám fyrir hnappinn í 5V í staðinn fyrir jörð (GND)?_
   2. _Afhverju þarf pinni 2 að vera tengdur við jörð?_
   3. _Breyttu kóðanum þannig að með að ýta á takkann þá sé slökkt á LED ljósi sem myndi annars lýsa stöðugt._

5.2  **Potentiometer (Analog Input)(2%)**
   1. Arduino er með 10 bita analog to digital converter (ADC). _Hvernig virkar ADC og hvaða gildi er verið að vinna með?_
   2. _Hvað gerist ef við tengjum digital skynjara við analog pinna?_

5.3  **Using the Serial Monitor (1%)**
   1. _Hvað þýðir 9600 baud í Serial.begin(9600) og hvað gerist ef þú breytir gildinu?_

5.4  **Photoresistor (Analog Input) (1%) - Þarf ekki að tengja**
   1. _Útskýrðu færibreyturnar og gildin í map fallinu. Afhverju þarf úttakið í analogWrite að vera á bilinu 0-255?_
   
       ```analogWrite(9, map(sensorValue, 0, 1023, 0, 255));```

5.5  **Ultrasonic Distance Sensor (2%)**    
1. _Breyttu kóðanum þannig að hann vinnur eingöngu með sentimetra._
2. _Hvað gerir timeout í eftirfarandi falli? `pulseIn(pin, value, timeout);`_

5.6  **Project 5: Mood Cue  (servo motor) (1%) - Þarf ekki að tengja**
 1. _Hvers vegna þarf að nota rafþéttir (e. capacitor) og hvað ber að varast við notkun þeirra?_
 2. _Afhverju snýst servo mótor venjulega aðeins í hálfhring (180 gráður) en ekki í heilan hring (360 gráður)?_

5.7  **Project 6: Light Theremin (hátalari og ljósviðnám) (1%) - Þarf ekki að tengja**
 1. _Hvað er verkhlutfall (e. duty cycle) og hvernig tengist það tíðni (e. frequency)?_
 2. _Tíðni (e. frequnzy) er mæld í Hertz (Hz). Útskýrðu hvernig það er gert._


### Námsmat og skil
Fyrir hvern lið þá er gefið fullt fyrir fullnægjandi lausn og svör, hálft ef ábótavant.

Skilaðu á Innu vefslóð á GitHub Wiki sem inniheldur:

* tengla á myndbönd sem sýna Arduino, brauðbretti, íhluti og kóða í keyrslu í ofangreindum verkefnum. Á myndböndunum þarf að koma fram nafn þitt og dagsetning. 
* tengla á kóðaskrár í geymslunni (_e. repository_)
* svör við spurningum
