README.md

Added a Makefile which I've used to compile for the ATmega328, but still some bugs with ATmega32u4......

Success with Arduino : 











/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-g++ -c -g -Os -Wall -fno-exceptions -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/Alarms.cpp -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/Alarms.cpp.o 
In file included from Alarms.cpp:3:
def.h:935:1: warning: "SOFT_PWM_3_PIN_HIGH" redefined
def.h:444:1: warning: this is the location of the previous definition
def.h:936:1: warning: "SOFT_PWM_3_PIN_LOW" redefined
def.h:445:1: warning: this is the location of the previous definition
def.h:937:1: warning: "SOFT_PWM_4_PIN_HIGH" redefined
def.h:446:1: warning: this is the location of the previous definition
def.h:938:1: warning: "SOFT_PWM_4_PIN_LOW" redefined
def.h:447:1: warning: this is the location of the previous definition
def.h:939:1: warning: "SW_PWM_P3" redefined
def.h:448:1: warning: this is the location of the previous definition
def.h:940:1: warning: "SW_PWM_P4" redefined
def.h:449:1: warning: this is the location of the previous definition
def.h:943:1: warning: "SERVO_3_PINMODE" redefined
def.h:466:1: warning: this is the location of the previous definition
def.h:944:1: warning: "SERVO_3_PIN_HIGH" redefined
def.h:467:1: warning: this is the location of the previous definition
def.h:945:1: warning: "SERVO_3_PIN_LOW" redefined
def.h:468:1: warning: this is the location of the previous definition
def.h:946:1: warning: "SERVO_4_PINMODE" redefined
def.h:470:1: warning: this is the location of the previous definition
def.h:947:1: warning: "SERVO_4_PIN_HIGH" redefined
def.h:471:1: warning: this is the location of the previous definition
def.h:948:1: warning: "SERVO_4_PIN_LOW" redefined
def.h:472:1: warning: this is the location of the previous definition
def.h:951:1: warning: "LEDPIN_PINMODE" redefined
def.h:376:1: warning: this is the location of the previous definition
def.h:952:1: warning: "LEDPIN_TOGGLE" redefined
def.h:377:1: warning: this is the location of the previous definition
def.h:953:1: warning: "LEDPIN_OFF" redefined
def.h:379:1: warning: this is the location of the previous definition
def.h:954:1: warning: "LEDPIN_ON" redefined
def.h:380:1: warning: this is the location of the previous definition
Alarms.cpp: In function 'void alarmPatternComposer()':
Alarms.cpp:118: warning: unused variable 'resource'
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-g++ -c -g -Os -Wall -fno-exceptions -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/EEPROM.cpp -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/EEPROM.cpp.o 
In file included from EEPROM.cpp:4:
def.h:935:1: warning: "SOFT_PWM_3_PIN_HIGH" redefined
def.h:444:1: warning: this is the location of the previous definition
def.h:936:1: warning: "SOFT_PWM_3_PIN_LOW" redefined
def.h:445:1: warning: this is the location of the previous definition
def.h:937:1: warning: "SOFT_PWM_4_PIN_HIGH" redefined
def.h:446:1: warning: this is the location of the previous definition
def.h:938:1: warning: "SOFT_PWM_4_PIN_LOW" redefined
def.h:447:1: warning: this is the location of the previous definition
def.h:939:1: warning: "SW_PWM_P3" redefined
def.h:448:1: warning: this is the location of the previous definition
def.h:940:1: warning: "SW_PWM_P4" redefined
def.h:449:1: warning: this is the location of the previous definition
def.h:943:1: warning: "SERVO_3_PINMODE" redefined
def.h:466:1: warning: this is the location of the previous definition
def.h:944:1: warning: "SERVO_3_PIN_HIGH" redefined
def.h:467:1: warning: this is the location of the previous definition
def.h:945:1: warning: "SERVO_3_PIN_LOW" redefined
def.h:468:1: warning: this is the location of the previous definition
def.h:946:1: warning: "SERVO_4_PINMODE" redefined
def.h:470:1: warning: this is the location of the previous definition
def.h:947:1: warning: "SERVO_4_PIN_HIGH" redefined
def.h:471:1: warning: this is the location of the previous definition
def.h:948:1: warning: "SERVO_4_PIN_LOW" redefined
def.h:472:1: warning: this is the location of the previous definition
def.h:951:1: warning: "LEDPIN_PINMODE" redefined
def.h:376:1: warning: this is the location of the previous definition
def.h:952:1: warning: "LEDPIN_TOGGLE" redefined
def.h:377:1: warning: this is the location of the previous definition
def.h:953:1: warning: "LEDPIN_OFF" redefined
def.h:379:1: warning: this is the location of the previous definition
def.h:954:1: warning: "LEDPIN_ON" redefined
def.h:380:1: warning: this is the location of the previous definition
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-g++ -c -g -Os -Wall -fno-exceptions -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/GPS.cpp -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/GPS.cpp.o 
In file included from GPS.cpp:3:
def.h:935:1: warning: "SOFT_PWM_3_PIN_HIGH" redefined
def.h:444:1: warning: this is the location of the previous definition
def.h:936:1: warning: "SOFT_PWM_3_PIN_LOW" redefined
def.h:445:1: warning: this is the location of the previous definition
def.h:937:1: warning: "SOFT_PWM_4_PIN_HIGH" redefined
def.h:446:1: warning: this is the location of the previous definition
def.h:938:1: warning: "SOFT_PWM_4_PIN_LOW" redefined
def.h:447:1: warning: this is the location of the previous definition
def.h:939:1: warning: "SW_PWM_P3" redefined
def.h:448:1: warning: this is the location of the previous definition
def.h:940:1: warning: "SW_PWM_P4" redefined
def.h:449:1: warning: this is the location of the previous definition
def.h:943:1: warning: "SERVO_3_PINMODE" redefined
def.h:466:1: warning: this is the location of the previous definition
def.h:944:1: warning: "SERVO_3_PIN_HIGH" redefined
def.h:467:1: warning: this is the location of the previous definition
def.h:945:1: warning: "SERVO_3_PIN_LOW" redefined
def.h:468:1: warning: this is the location of the previous definition
def.h:946:1: warning: "SERVO_4_PINMODE" redefined
def.h:470:1: warning: this is the location of the previous definition
def.h:947:1: warning: "SERVO_4_PIN_HIGH" redefined
def.h:471:1: warning: this is the location of the previous definition
def.h:948:1: warning: "SERVO_4_PIN_LOW" redefined
def.h:472:1: warning: this is the location of the previous definition
def.h:951:1: warning: "LEDPIN_PINMODE" redefined
def.h:376:1: warning: this is the location of the previous definition
def.h:952:1: warning: "LEDPIN_TOGGLE" redefined
def.h:377:1: warning: this is the location of the previous definition
def.h:953:1: warning: "LEDPIN_OFF" redefined
def.h:379:1: warning: this is the location of the previous definition
def.h:954:1: warning: "LEDPIN_ON" redefined
def.h:380:1: warning: this is the location of the previous definition
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-g++ -c -g -Os -Wall -fno-exceptions -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/IMU.cpp -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/IMU.cpp.o 
In file included from IMU.cpp:3:
def.h:935:1: warning: "SOFT_PWM_3_PIN_HIGH" redefined
def.h:444:1: warning: this is the location of the previous definition
def.h:936:1: warning: "SOFT_PWM_3_PIN_LOW" redefined
def.h:445:1: warning: this is the location of the previous definition
def.h:937:1: warning: "SOFT_PWM_4_PIN_HIGH" redefined
def.h:446:1: warning: this is the location of the previous definition
def.h:938:1: warning: "SOFT_PWM_4_PIN_LOW" redefined
def.h:447:1: warning: this is the location of the previous definition
def.h:939:1: warning: "SW_PWM_P3" redefined
def.h:448:1: warning: this is the location of the previous definition
def.h:940:1: warning: "SW_PWM_P4" redefined
def.h:449:1: warning: this is the location of the previous definition
def.h:943:1: warning: "SERVO_3_PINMODE" redefined
def.h:466:1: warning: this is the location of the previous definition
def.h:944:1: warning: "SERVO_3_PIN_HIGH" redefined
def.h:467:1: warning: this is the location of the previous definition
def.h:945:1: warning: "SERVO_3_PIN_LOW" redefined
def.h:468:1: warning: this is the location of the previous definition
def.h:946:1: warning: "SERVO_4_PINMODE" redefined
def.h:470:1: warning: this is the location of the previous definition
def.h:947:1: warning: "SERVO_4_PIN_HIGH" redefined
def.h:471:1: warning: this is the location of the previous definition
def.h:948:1: warning: "SERVO_4_PIN_LOW" redefined
def.h:472:1: warning: this is the location of the previous definition
def.h:951:1: warning: "LEDPIN_PINMODE" redefined
def.h:376:1: warning: this is the location of the previous definition
def.h:952:1: warning: "LEDPIN_TOGGLE" redefined
def.h:377:1: warning: this is the location of the previous definition
def.h:953:1: warning: "LEDPIN_OFF" redefined
def.h:379:1: warning: this is the location of the previous definition
def.h:954:1: warning: "LEDPIN_ON" redefined
def.h:380:1: warning: this is the location of the previous definition
IMU.cpp: In function 'void getEstimatedAttitude()':
IMU.cpp:199: warning: missing braces around initializer for 'int32_t [3]'
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-g++ -c -g -Os -Wall -fno-exceptions -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/LCD.cpp -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/LCD.cpp.o 
In file included from LCD.cpp:3:
def.h:935:1: warning: "SOFT_PWM_3_PIN_HIGH" redefined
def.h:444:1: warning: this is the location of the previous definition
def.h:936:1: warning: "SOFT_PWM_3_PIN_LOW" redefined
def.h:445:1: warning: this is the location of the previous definition
def.h:937:1: warning: "SOFT_PWM_4_PIN_HIGH" redefined
def.h:446:1: warning: this is the location of the previous definition
def.h:938:1: warning: "SOFT_PWM_4_PIN_LOW" redefined
def.h:447:1: warning: this is the location of the previous definition
def.h:939:1: warning: "SW_PWM_P3" redefined
def.h:448:1: warning: this is the location of the previous definition
def.h:940:1: warning: "SW_PWM_P4" redefined
def.h:449:1: warning: this is the location of the previous definition
def.h:943:1: warning: "SERVO_3_PINMODE" redefined
def.h:466:1: warning: this is the location of the previous definition
def.h:944:1: warning: "SERVO_3_PIN_HIGH" redefined
def.h:467:1: warning: this is the location of the previous definition
def.h:945:1: warning: "SERVO_3_PIN_LOW" redefined
def.h:468:1: warning: this is the location of the previous definition
def.h:946:1: warning: "SERVO_4_PINMODE" redefined
def.h:470:1: warning: this is the location of the previous definition
def.h:947:1: warning: "SERVO_4_PIN_HIGH" redefined
def.h:471:1: warning: this is the location of the previous definition
def.h:948:1: warning: "SERVO_4_PIN_LOW" redefined
def.h:472:1: warning: this is the location of the previous definition
def.h:951:1: warning: "LEDPIN_PINMODE" redefined
def.h:376:1: warning: this is the location of the previous definition
def.h:952:1: warning: "LEDPIN_TOGGLE" redefined
def.h:377:1: warning: this is the location of the previous definition
def.h:953:1: warning: "LEDPIN_OFF" redefined
def.h:379:1: warning: this is the location of the previous definition
def.h:954:1: warning: "LEDPIN_ON" redefined
def.h:380:1: warning: this is the location of the previous definition
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-g++ -c -g -Os -Wall -fno-exceptions -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/MultiWii.cpp -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/MultiWii.cpp.o 
In file included from MultiWii.cpp:15:
def.h:935:1: warning: "SOFT_PWM_3_PIN_HIGH" redefined
def.h:444:1: warning: this is the location of the previous definition
def.h:936:1: warning: "SOFT_PWM_3_PIN_LOW" redefined
def.h:445:1: warning: this is the location of the previous definition
def.h:937:1: warning: "SOFT_PWM_4_PIN_HIGH" redefined
def.h:446:1: warning: this is the location of the previous definition
def.h:938:1: warning: "SOFT_PWM_4_PIN_LOW" redefined
def.h:447:1: warning: this is the location of the previous definition
def.h:939:1: warning: "SW_PWM_P3" redefined
def.h:448:1: warning: this is the location of the previous definition
def.h:940:1: warning: "SW_PWM_P4" redefined
def.h:449:1: warning: this is the location of the previous definition
def.h:943:1: warning: "SERVO_3_PINMODE" redefined
def.h:466:1: warning: this is the location of the previous definition
def.h:944:1: warning: "SERVO_3_PIN_HIGH" redefined
def.h:467:1: warning: this is the location of the previous definition
def.h:945:1: warning: "SERVO_3_PIN_LOW" redefined
def.h:468:1: warning: this is the location of the previous definition
def.h:946:1: warning: "SERVO_4_PINMODE" redefined
def.h:470:1: warning: this is the location of the previous definition
def.h:947:1: warning: "SERVO_4_PIN_HIGH" redefined
def.h:471:1: warning: this is the location of the previous definition
def.h:948:1: warning: "SERVO_4_PIN_LOW" redefined
def.h:472:1: warning: this is the location of the previous definition
def.h:951:1: warning: "LEDPIN_PINMODE" redefined
def.h:376:1: warning: this is the location of the previous definition
def.h:952:1: warning: "LEDPIN_TOGGLE" redefined
def.h:377:1: warning: this is the location of the previous definition
def.h:953:1: warning: "LEDPIN_OFF" redefined
def.h:379:1: warning: this is the location of the previous definition
def.h:954:1: warning: "LEDPIN_ON" redefined
def.h:380:1: warning: this is the location of the previous definition
MultiWii.cpp:33: warning: only initialized variables can be placed into program memory area
MultiWii.cpp:46: warning: only initialized variables can be placed into program memory area
MultiWii.cpp:97: warning: only initialized variables can be placed into program memory area
MultiWii.cpp: In function 'void loop()':
MultiWii.cpp:792: warning: unused variable 'initialThrottleHold'
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-g++ -c -g -Os -Wall -fno-exceptions -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/Output.cpp -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/Output.cpp.o 
In file included from Output.cpp:3:
def.h:935:1: warning: "SOFT_PWM_3_PIN_HIGH" redefined
def.h:444:1: warning: this is the location of the previous definition
def.h:936:1: warning: "SOFT_PWM_3_PIN_LOW" redefined
def.h:445:1: warning: this is the location of the previous definition
def.h:937:1: warning: "SOFT_PWM_4_PIN_HIGH" redefined
def.h:446:1: warning: this is the location of the previous definition
def.h:938:1: warning: "SOFT_PWM_4_PIN_LOW" redefined
def.h:447:1: warning: this is the location of the previous definition
def.h:939:1: warning: "SW_PWM_P3" redefined
def.h:448:1: warning: this is the location of the previous definition
def.h:940:1: warning: "SW_PWM_P4" redefined
def.h:449:1: warning: this is the location of the previous definition
def.h:943:1: warning: "SERVO_3_PINMODE" redefined
def.h:466:1: warning: this is the location of the previous definition
def.h:944:1: warning: "SERVO_3_PIN_HIGH" redefined
def.h:467:1: warning: this is the location of the previous definition
def.h:945:1: warning: "SERVO_3_PIN_LOW" redefined
def.h:468:1: warning: this is the location of the previous definition
def.h:946:1: warning: "SERVO_4_PINMODE" redefined
def.h:470:1: warning: this is the location of the previous definition
def.h:947:1: warning: "SERVO_4_PIN_HIGH" redefined
def.h:471:1: warning: this is the location of the previous definition
def.h:948:1: warning: "SERVO_4_PIN_LOW" redefined
def.h:472:1: warning: this is the location of the previous definition
def.h:951:1: warning: "LEDPIN_PINMODE" redefined
def.h:376:1: warning: this is the location of the previous definition
def.h:952:1: warning: "LEDPIN_TOGGLE" redefined
def.h:377:1: warning: this is the location of the previous definition
def.h:953:1: warning: "LEDPIN_OFF" redefined
def.h:379:1: warning: this is the location of the previous definition
def.h:954:1: warning: "LEDPIN_ON" redefined
def.h:380:1: warning: this is the location of the previous definition
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-g++ -c -g -Os -Wall -fno-exceptions -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/Protocol.cpp -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/Protocol.cpp.o 
In file included from Protocol.cpp:3:
def.h:935:1: warning: "SOFT_PWM_3_PIN_HIGH" redefined
def.h:444:1: warning: this is the location of the previous definition
def.h:936:1: warning: "SOFT_PWM_3_PIN_LOW" redefined
def.h:445:1: warning: this is the location of the previous definition
def.h:937:1: warning: "SOFT_PWM_4_PIN_HIGH" redefined
def.h:446:1: warning: this is the location of the previous definition
def.h:938:1: warning: "SOFT_PWM_4_PIN_LOW" redefined
def.h:447:1: warning: this is the location of the previous definition
def.h:939:1: warning: "SW_PWM_P3" redefined
def.h:448:1: warning: this is the location of the previous definition
def.h:940:1: warning: "SW_PWM_P4" redefined
def.h:449:1: warning: this is the location of the previous definition
def.h:943:1: warning: "SERVO_3_PINMODE" redefined
def.h:466:1: warning: this is the location of the previous definition
def.h:944:1: warning: "SERVO_3_PIN_HIGH" redefined
def.h:467:1: warning: this is the location of the previous definition
def.h:945:1: warning: "SERVO_3_PIN_LOW" redefined
def.h:468:1: warning: this is the location of the previous definition
def.h:946:1: warning: "SERVO_4_PINMODE" redefined
def.h:470:1: warning: this is the location of the previous definition
def.h:947:1: warning: "SERVO_4_PIN_HIGH" redefined
def.h:471:1: warning: this is the location of the previous definition
def.h:948:1: warning: "SERVO_4_PIN_LOW" redefined
def.h:472:1: warning: this is the location of the previous definition
def.h:951:1: warning: "LEDPIN_PINMODE" redefined
def.h:376:1: warning: this is the location of the previous definition
def.h:952:1: warning: "LEDPIN_TOGGLE" redefined
def.h:377:1: warning: this is the location of the previous definition
def.h:953:1: warning: "LEDPIN_OFF" redefined
def.h:379:1: warning: this is the location of the previous definition
def.h:954:1: warning: "LEDPIN_ON" redefined
def.h:380:1: warning: this is the location of the previous definition
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-g++ -c -g -Os -Wall -fno-exceptions -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/RX.cpp -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/RX.cpp.o 
In file included from RX.cpp:3:
def.h:935:1: warning: "SOFT_PWM_3_PIN_HIGH" redefined
def.h:444:1: warning: this is the location of the previous definition
def.h:936:1: warning: "SOFT_PWM_3_PIN_LOW" redefined
def.h:445:1: warning: this is the location of the previous definition
def.h:937:1: warning: "SOFT_PWM_4_PIN_HIGH" redefined
def.h:446:1: warning: this is the location of the previous definition
def.h:938:1: warning: "SOFT_PWM_4_PIN_LOW" redefined
def.h:447:1: warning: this is the location of the previous definition
def.h:939:1: warning: "SW_PWM_P3" redefined
def.h:448:1: warning: this is the location of the previous definition
def.h:940:1: warning: "SW_PWM_P4" redefined
def.h:449:1: warning: this is the location of the previous definition
def.h:943:1: warning: "SERVO_3_PINMODE" redefined
def.h:466:1: warning: this is the location of the previous definition
def.h:944:1: warning: "SERVO_3_PIN_HIGH" redefined
def.h:467:1: warning: this is the location of the previous definition
def.h:945:1: warning: "SERVO_3_PIN_LOW" redefined
def.h:468:1: warning: this is the location of the previous definition
def.h:946:1: warning: "SERVO_4_PINMODE" redefined
def.h:470:1: warning: this is the location of the previous definition
def.h:947:1: warning: "SERVO_4_PIN_HIGH" redefined
def.h:471:1: warning: this is the location of the previous definition
def.h:948:1: warning: "SERVO_4_PIN_LOW" redefined
def.h:472:1: warning: this is the location of the previous definition
def.h:951:1: warning: "LEDPIN_PINMODE" redefined
def.h:376:1: warning: this is the location of the previous definition
def.h:952:1: warning: "LEDPIN_TOGGLE" redefined
def.h:377:1: warning: this is the location of the previous definition
def.h:953:1: warning: "LEDPIN_OFF" redefined
def.h:379:1: warning: this is the location of the previous definition
def.h:954:1: warning: "LEDPIN_ON" redefined
def.h:380:1: warning: this is the location of the previous definition
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-g++ -c -g -Os -Wall -fno-exceptions -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/Sensors.cpp -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/Sensors.cpp.o 
In file included from Sensors.cpp:3:
def.h:935:1: warning: "SOFT_PWM_3_PIN_HIGH" redefined
def.h:444:1: warning: this is the location of the previous definition
def.h:936:1: warning: "SOFT_PWM_3_PIN_LOW" redefined
def.h:445:1: warning: this is the location of the previous definition
def.h:937:1: warning: "SOFT_PWM_4_PIN_HIGH" redefined
def.h:446:1: warning: this is the location of the previous definition
def.h:938:1: warning: "SOFT_PWM_4_PIN_LOW" redefined
def.h:447:1: warning: this is the location of the previous definition
def.h:939:1: warning: "SW_PWM_P3" redefined
def.h:448:1: warning: this is the location of the previous definition
def.h:940:1: warning: "SW_PWM_P4" redefined
def.h:449:1: warning: this is the location of the previous definition
def.h:943:1: warning: "SERVO_3_PINMODE" redefined
def.h:466:1: warning: this is the location of the previous definition
def.h:944:1: warning: "SERVO_3_PIN_HIGH" redefined
def.h:467:1: warning: this is the location of the previous definition
def.h:945:1: warning: "SERVO_3_PIN_LOW" redefined
def.h:468:1: warning: this is the location of the previous definition
def.h:946:1: warning: "SERVO_4_PINMODE" redefined
def.h:470:1: warning: this is the location of the previous definition
def.h:947:1: warning: "SERVO_4_PIN_HIGH" redefined
def.h:471:1: warning: this is the location of the previous definition
def.h:948:1: warning: "SERVO_4_PIN_LOW" redefined
def.h:472:1: warning: this is the location of the previous definition
def.h:951:1: warning: "LEDPIN_PINMODE" redefined
def.h:376:1: warning: this is the location of the previous definition
def.h:952:1: warning: "LEDPIN_TOGGLE" redefined
def.h:377:1: warning: this is the location of the previous definition
def.h:953:1: warning: "LEDPIN_OFF" redefined
def.h:379:1: warning: this is the location of the previous definition
def.h:954:1: warning: "LEDPIN_ON" redefined
def.h:380:1: warning: this is the location of the previous definition
Sensors.cpp: In function 'void GYRO_Common()':
Sensors.cpp:297: warning: unused variable 'tilt'
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-g++ -c -g -Os -Wall -fno-exceptions -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/Serial.cpp -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/Serial.cpp.o 
In file included from Serial.cpp:3:
def.h:935:1: warning: "SOFT_PWM_3_PIN_HIGH" redefined
def.h:444:1: warning: this is the location of the previous definition
def.h:936:1: warning: "SOFT_PWM_3_PIN_LOW" redefined
def.h:445:1: warning: this is the location of the previous definition
def.h:937:1: warning: "SOFT_PWM_4_PIN_HIGH" redefined
def.h:446:1: warning: this is the location of the previous definition
def.h:938:1: warning: "SOFT_PWM_4_PIN_LOW" redefined
def.h:447:1: warning: this is the location of the previous definition
def.h:939:1: warning: "SW_PWM_P3" redefined
def.h:448:1: warning: this is the location of the previous definition
def.h:940:1: warning: "SW_PWM_P4" redefined
def.h:449:1: warning: this is the location of the previous definition
def.h:943:1: warning: "SERVO_3_PINMODE" redefined
def.h:466:1: warning: this is the location of the previous definition
def.h:944:1: warning: "SERVO_3_PIN_HIGH" redefined
def.h:467:1: warning: this is the location of the previous definition
def.h:945:1: warning: "SERVO_3_PIN_LOW" redefined
def.h:468:1: warning: this is the location of the previous definition
def.h:946:1: warning: "SERVO_4_PINMODE" redefined
def.h:470:1: warning: this is the location of the previous definition
def.h:947:1: warning: "SERVO_4_PIN_HIGH" redefined
def.h:471:1: warning: this is the location of the previous definition
def.h:948:1: warning: "SERVO_4_PIN_LOW" redefined
def.h:472:1: warning: this is the location of the previous definition
def.h:951:1: warning: "LEDPIN_PINMODE" redefined
def.h:376:1: warning: this is the location of the previous definition
def.h:952:1: warning: "LEDPIN_TOGGLE" redefined
def.h:377:1: warning: this is the location of the previous definition
def.h:953:1: warning: "LEDPIN_OFF" redefined
def.h:379:1: warning: this is the location of the previous definition
def.h:954:1: warning: "LEDPIN_ON" redefined
def.h:380:1: warning: this is the location of the previous definition
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-gcc -c -g -Os -Wall -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo /Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/avr-libc/malloc.c -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/malloc.c.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-gcc -c -g -Os -Wall -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo /Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/avr-libc/realloc.c -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/realloc.c.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-gcc -c -g -Os -Wall -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo /Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/WInterrupts.c -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/WInterrupts.c.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-gcc -c -g -Os -Wall -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo /Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/wiring.c -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/wiring.c.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/wiring.c:264:3: warning: #warning Timer 2 not finished (may not be present on this CPU)
/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/wiring.c:273:3: warning: #warning Timer 2 not finished (may not be present on this CPU)
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-gcc -c -g -Os -Wall -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo /Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/wiring_analog.c -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/wiring_analog.c.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-gcc -c -g -Os -Wall -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo /Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/wiring_digital.c -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/wiring_digital.c.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-gcc -c -g -Os -Wall -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo /Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/wiring_pulse.c -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/wiring_pulse.c.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-gcc -c -g -Os -Wall -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo /Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/wiring_shift.c -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/wiring_shift.c.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-g++ -c -g -Os -Wall -fno-exceptions -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo /Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/CDC.cpp -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/CDC.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-g++ -c -g -Os -Wall -fno-exceptions -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo /Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/HardwareSerial.cpp -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/HardwareSerial.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/HardwareSerial.cpp: In function 'void store_char(unsigned char, ring_buffer*)':
/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/HardwareSerial.cpp:98: warning: comparison between signed and unsigned integer expressions
/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/HardwareSerial.cpp: In function 'void __vector_25()':
/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/HardwareSerial.cpp:153: warning: unused variable 'c'
/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/HardwareSerial.cpp: In member function 'void HardwareSerial::begin(long unsigned int, byte)':
/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/HardwareSerial.cpp:368: warning: unused variable 'current_config'
/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/HardwareSerial.cpp: In member function 'virtual size_t HardwareSerial::write(uint8_t)':
/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/HardwareSerial.cpp:467: warning: comparison between signed and unsigned integer expressions
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-g++ -c -g -Os -Wall -fno-exceptions -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo /Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/HID.cpp -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/HID.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/HID.cpp: In member function 'virtual size_t Keyboard_::write(uint8_t)':
/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/HID.cpp:514: warning: unused variable 'r'
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-g++ -c -g -Os -Wall -fno-exceptions -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo /Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/IPAddress.cpp -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/IPAddress.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-g++ -c -g -Os -Wall -fno-exceptions -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo /Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/main.cpp -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/main.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-g++ -c -g -Os -Wall -fno-exceptions -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo /Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/new.cpp -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/new.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-g++ -c -g -Os -Wall -fno-exceptions -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo /Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/Print.cpp -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/Print.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/Print.cpp: In member function 'size_t Print::print(const __FlashStringHelper*)':
/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/Print.cpp:44: warning: '__progmem__' attribute ignored
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-g++ -c -g -Os -Wall -fno-exceptions -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo /Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/Stream.cpp -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/Stream.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-g++ -c -g -Os -Wall -fno-exceptions -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo /Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/Tone.cpp -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/Tone.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/Tone.cpp:210:12: warning: #warning this may not be correct
/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/Tone.cpp:110: warning: only initialized variables can be placed into program memory area
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-g++ -c -g -Os -Wall -fno-exceptions -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo /Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/USBCore.cpp -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/USBCore.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/USBCore.cpp: In function 'int USB_Send(u8, const void*, int)':
/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/USBCore.cpp:278: warning: unused variable 'zero'
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-g++ -c -g -Os -Wall -fno-exceptions -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo /Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/WMath.cpp -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/WMath.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-g++ -c -g -Os -Wall -fno-exceptions -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo /Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino/WString.cpp -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/WString.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/malloc.c.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/realloc.c.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/WInterrupts.c.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/wiring.c.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/wiring_analog.c.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/wiring_digital.c.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/wiring_pulse.c.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/wiring_shift.c.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/CDC.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/HardwareSerial.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/HID.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/IPAddress.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/main.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/new.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/Print.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/Stream.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/Tone.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/USBCore.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/WMath.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/WString.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-gcc -Os -Wl,--gc-sections -mmcu=atmega32u4 -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/MultiWii.cpp.elf /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/Alarms.cpp.o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/EEPROM.cpp.o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/GPS.cpp.o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/IMU.cpp.o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/LCD.cpp.o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/MultiWii.cpp.o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/Output.cpp.o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/Protocol.cpp.o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/RX.cpp.o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/Sensors.cpp.o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/Serial.cpp.o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a -L/var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp -lm 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-objcopy -O ihex -j .eeprom --set-section-flags=.eeprom=alloc,load --no-change-warnings --change-section-lma .eeprom=0 /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/MultiWii.cpp.elf /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/MultiWii.cpp.eep 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-objcopy -O ihex -R .eeprom /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/MultiWii.cpp.elf /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/MultiWii.cpp.hex 
Binary sketch size: 17,836 bytes (of a 28,672 byte maximum)


Even more so with NanoWii MWC2.1 :
Post : http://www.rcgroups.com/forums/showthread.php?t=1999720
Link to zip : http://ultraesc.de/downloads/MWC21nanoSetupChromeAppGUI_0991.zip





/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-g++ -c -g -Os -Wall -fno-exceptions -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo -I/Applications/Arduino.app/Contents/Resources/Java/libraries/EEPROM /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/MWC21NanoV_0991.cpp -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/MWC21NanoV_0991.cpp.o 
In file included from MWC21NanoV_0991.ino:18:
def.h:132:1: warning: "SOFT_PWM_3_PIN_HIGH" redefined
def.h:68:1: warning: this is the location of the previous definition
def.h:133:1: warning: "SOFT_PWM_3_PIN_LOW" redefined
def.h:69:1: warning: this is the location of the previous definition
def.h:134:1: warning: "SOFT_PWM_4_PIN_HIGH" redefined
def.h:70:1: warning: this is the location of the previous definition
def.h:135:1: warning: "SOFT_PWM_4_PIN_LOW" redefined
def.h:71:1: warning: this is the location of the previous definition
def.h:136:1: warning: "SW_PWM_P3" redefined
def.h:72:1: warning: this is the location of the previous definition
def.h:137:1: warning: "SW_PWM_P4" redefined
def.h:73:1: warning: this is the location of the previous definition
MWC21NanoV_0991.ino:63: warning: only initialized variables can be placed into program memory area
MWC21NanoV_0991.ino:71: warning: only initialized variables can be placed into program memory area
MWC21NanoV_0991.ino:75: warning: only initialized variables can be placed into program memory area
MWC21NanoV_0991.ino: In function 'void loop()':
MWC21NanoV_0991.ino:361: warning: unused variable 'initialThrottleHold'
IMU.ino: In function 'void getEstimatedAttitude()':
IMU.ino:199: warning: operation on 'Zadd' may be undefined
IMU.ino:202: warning: operation on 'Zadd' may be undefined
Output.ino: In function 'void mixTable()':
Output.ino:120: warning: comparison between signed and unsigned integer expressions
Output.ino:121: warning: comparison between signed and unsigned integer expressions
Output.ino:123: warning: comparison between signed and unsigned integer expressions
Output.ino:129: warning: comparison between signed and unsigned integer expressions
Output.ino:223: warning: comparison between signed and unsigned integer expressions
Output.ino:224: warning: comparison between signed and unsigned integer expressions
Output.ino:226: warning: comparison between signed and unsigned integer expressions
Output.ino:237: warning: comparison between signed and unsigned integer expressions
Serial.ino: In function 'uint8_t SerialAvailable(uint8_t)':
Serial.ino:528: warning: suggest explicit braces to avoid ambiguous 'else'
Output.ino: In function 'void writeMotors()':
Output.ino:37: warning: array subscript is above array bounds
Output.ino:38: warning: array subscript is above array bounds
Output.ino:40: warning: array subscript is above array bounds
Output.ino:41: warning: array subscript is above array bounds
MWC21NanoV_0991.ino: In function 'void loop()':
MWC21NanoV_0991.ino:522: warning: 'prop' may be used uninitialized in this function
MWC21NanoV_0991.ino:353: warning: 'ITermGYRO' may be used uninitialized in this function
MWC21NanoV_0991.ino:353: warning: 'PTermGYRO' may be used uninitialized in this function
MWC21NanoV_0991.ino:353: warning: 'ITermACC' may be used uninitialized in this function
MWC21NanoV_0991.ino:353: warning: 'PTermACC' may be used uninitialized in this function
MWC21NanoV_0991.ino: At global scope:
MWC21NanoV_0991.ino:100: warning: 'magHold' defined but not used
MWC21NanoV_0991.ino:101: warning: 'vbat' defined but not used
MWC21NanoV_0991.ino:103: warning: 'BaroAlt' defined but not used
MWC21NanoV_0991.ino:105: warning: 'BaroPID' defined but not used
MWC21NanoV_0991.ino:106: warning: 'AltHold' defined but not used
MWC21NanoV_0991.ino:108: warning: 'errorAltitudeI' defined but not used
MWC21NanoV_0991.ino:117: warning: 'sonarAlt' defined but not used
MWC21NanoV_0991.ino:135: warning: 'failsafeEvents' defined but not used
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-g++ -c -g -Os -Wall -fno-exceptions -ffunction-sections -fdata-sections -mmcu=atmega32u4 -DF_CPU=16000000L -MMD -DUSB_VID=0x2341 -DUSB_PID=0x8036 -DARDUINO=105 -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/cores/arduino -I/Applications/Arduino.app/Contents/Resources/Java/hardware/arduino/variants/leonardo -I/Applications/Arduino.app/Contents/Resources/Java/libraries/EEPROM -I/Applications/Arduino.app/Contents/Resources/Java/libraries/EEPROM/utility /Applications/Arduino.app/Contents/Resources/Java/libraries/EEPROM/EEPROM.cpp -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/EEPROM/EEPROM.cpp.o 
  Using previously compiled: /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/malloc.c.o
  Using previously compiled: /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/realloc.c.o
  Using previously compiled: /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/WInterrupts.c.o
  Using previously compiled: /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/wiring.c.o
  Using previously compiled: /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/wiring_analog.c.o
  Using previously compiled: /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/wiring_digital.c.o
  Using previously compiled: /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/wiring_pulse.c.o
  Using previously compiled: /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/wiring_shift.c.o
  Using previously compiled: /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/CDC.cpp.o
  Using previously compiled: /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/HardwareSerial.cpp.o
  Using previously compiled: /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/HID.cpp.o
  Using previously compiled: /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/IPAddress.cpp.o
  Using previously compiled: /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/main.cpp.o
  Using previously compiled: /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/new.cpp.o
  Using previously compiled: /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/Print.cpp.o
  Using previously compiled: /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/Stream.cpp.o
  Using previously compiled: /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/Tone.cpp.o
  Using previously compiled: /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/USBCore.cpp.o
  Using previously compiled: /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/WMath.cpp.o
  Using previously compiled: /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/WString.cpp.o
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/malloc.c.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/realloc.c.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/WInterrupts.c.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/wiring.c.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/wiring_analog.c.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/wiring_digital.c.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/wiring_pulse.c.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/wiring_shift.c.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/CDC.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/HardwareSerial.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/HID.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/IPAddress.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/main.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/new.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/Print.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/Stream.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/Tone.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/USBCore.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/WMath.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-ar rcs /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/WString.cpp.o 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-gcc -Os -Wl,--gc-sections -mmcu=atmega32u4 -o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/MWC21NanoV_0991.cpp.elf /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/MWC21NanoV_0991.cpp.o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/EEPROM/EEPROM.cpp.o /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/core.a -L/var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp -lm 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-objcopy -O ihex -j .eeprom --set-section-flags=.eeprom=alloc,load --no-change-warnings --change-section-lma .eeprom=0 /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/MWC21NanoV_0991.cpp.elf /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/MWC21NanoV_0991.cpp.eep 
/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avr-objcopy -O ihex -R .eeprom /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/MWC21NanoV_0991.cpp.elf /var/folders/m3/rvx25kqd7hbdl1bwyzdx895m0000gn/T/build8635248106847774225.tmp/MWC21NanoV_0991.cpp.hex 
Binary sketch size: 26,308 bytes (of a 28,672 byte maximum)
