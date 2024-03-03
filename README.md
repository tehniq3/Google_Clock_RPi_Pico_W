# Google_Clock_RPi_Pico_W
baesd on https://github.com/tehniq3/google_clock_esp8266

![phpto1](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjDENLv6O36V50FXa9_kNe2oCm8PjctPT_sHS1li82FHiydziPCmb67M6xiH45rEKJUeObB6RWJutU898C-iO4cU5sE7Q8wKmPLQTC66fskQbioLCC50IC0v01Y5EiB9XSZFz8Q47V73fq7cFPB-X9Mx5QkO74Bia6z15BvhDcz4BtT6vqhNknEe02x92Je/w200-h150/googleclock_RpiPicoW_3.jpg)
![photo2](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgW-W8X4MH5gGkT_MRjMdzvVTei-dBvIGiPlBwmZWmIFExkwwziz1fKBuvnqVhPrUpjDbqpdmND3yoobukKaLrtkfMCxLsZ82UOHywgB3OR_z7QAF7KA8G_1jXHxmFG0B272kUxd5rhQhxZ8m1vr10ToWkc6uNQQpKmkXG1-6PY4GIX7EiG9Rvk9Vwa_ALA/w200-h150/googleclock_RpiPicoW_4.jpg)

same as clock from https://youtu.be/-Kpe0kVYMFw but Wemos D1 mini (ESP8266 )was changed with RPi Pico W

sketch https://github.com/tehniq3/google_clock_esp8266/tree/main/BIG_Clock_ESP8266_DeskClock1h
but changed:
// for RPi Pico W
#define DIN_PIN 3  
#define CS_PIN  5  
#define CLK_PIN 2  
const int oneWireBus = 22;

my article: https://nicuflorica.blogspot.com/2024/03/ceas-google-cu-data-si-termometru-ce.html

![schematic](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjlPes9OY_oUrGglp-Nwl6sZvoTN7kqYYkfeXxczMIRr6n6sWVmrPlfIwE-RcaIPn-O2N-3X_a8yd1RKRhzVKbLsIFLGGK_7sXwR1qKWfLGxSrbRthzCV78dpQX1xzxqHJoV_EmvcLCnat1NsXt-YFmq0smU1oZWkHUZW86kiw4VS3SGoPLihMzX_B_MohF/s1125/GoogleClock_RPIPico_W_32x8_MAX7219_sch.png)

