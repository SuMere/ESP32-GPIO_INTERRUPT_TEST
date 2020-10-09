# Example: GPIO

This test code shows how to configure gpio and how to use gpio interrupt.

## GPIO functions:

 * GPIO18: output
 * GPIO19: output
 * GPIO39:  input, pulled up, interrupt from rising edge and falling edge
 * GPIO36:  input, pulled up, interrupt from rising edge and falling edge

## Test:
 * Connect GPIO18 with GPIO39
 * Connect GPIO19 with GPIO36
 * Generate pulses on GPIO18/19, that triggers interrupt on GPIO39/36
