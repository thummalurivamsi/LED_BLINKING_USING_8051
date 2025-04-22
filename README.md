//Led blinking with using 8051
//T. Vamsi

#include <reg51.h>  

sbit LED = P2^0;    // Define LED pin at Port 2.0

void delay_ms(unsigned int ms) {
    unsigned int i, j;
    for(i = 0; i < ms; i++)
        for(j = 0; j < 1275; j++);  // Roughly 1 ms delay at 12MHz
}

void main() {
    while(1) {
        LED = 0;      // Turn ON LED (Active Low if connected with GND through resistor)
        delay_ms(50);
        LED = 1;      // Turn OFF LED
        delay_ms(50);
    }
}
