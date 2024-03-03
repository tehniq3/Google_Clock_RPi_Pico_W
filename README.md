# Google_Clock_RPi_Pico_W
baesd on https://github.com/tehniq3/google_clock_esp8266

same as clock from https://youtu.be/-Kpe0kVYMFw but Wemos D1 mini (ESP8266 )was changed with RPi Pico W

sketch https://github.com/tehniq3/google_clock_esp8266/tree/main/BIG_Clock_ESP8266_DeskClock1h
but changed:
// for RPi Pico W
#define DIN_PIN 3  
#define CS_PIN  5  
#define CLK_PIN 2  
const int oneWireBus = 22;
