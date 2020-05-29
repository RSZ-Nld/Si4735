# Si4735
si4735 projects

Made a pcb for the Si4735 radio with buttons and Encoder on Pcb.
Works with Arduino Pro Mini.
And a 0,96 inch Oled display.
Code used is https://github.com/pu2clr/SI4735/tree/master/examples/SI47XX_08_RDS/SI4735_04_RDS_ALL_IN_ONE_OLED
Change the encoder pins:
// Enconder PINs
#define ENCODER_PIN_A 2
#define ENCODER_PIN_B 3

// Buttons controllers
#define MODE_SWITCH 4      // Switch MODE (Am/LSB/USB)
#define BANDWIDTH_BUTTON 5 // Used to select the banddwith. Values: 1.2, 2.2, 3.0, 4.0, 0.5, 1.0 KHz
#define VOL_UP 6           // Volume Up
#define VOL_DOWN 7         // Volume Down
#define BAND_BUTTON_UP 8   // Next band
#define BAND_BUTTON_DOWN 9 // Previous band
#define AGC_SWITCH 11      // Switch AGC ON/OF
#define STEP_SWITCH 10     // Used to select the increment or decrement frequency step (1, 5 or 10 KHz)
#define BFO_SWITCH 13      // Used to select the enconder control (BFO or VFO)
//#define BFO_SWITCH 14 // A0 (Alternative to the pin 13). Used to select the enconder control (BFO or VFO)
