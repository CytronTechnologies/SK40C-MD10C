# SK40C-MD10C
This is sample program to test the functionality of the MD10C by using SK40C.  
<img src="https://github.com/CytronTechnologies/SK40C-MD10C/blob/master/MD10C-image.jpg" width="350">  

For full tutorial you can refer to [Driving DC Brush Motor with MD10C](https://my.cytron.io/tutorial/project-10-driving-dc-brush-motor-with-md10c).  

## Requirements  
**Hardware:**  
* [10Amp 5V-30V DC Motor Driver](https://my.cytron.io/p-10amp-5v-30v-dc-motor-driver)  
* [SK40C](https://www.cytron.io/p-sk40c)  
* [PIC16F877A](https://www.cytron.io/p-ic-pic-16f877a)  
* [DC Motor](https://my.cytron.io/c-dc-motor)  

If your project required higher current rating you might want consider [13Amp 6V-30V DC Motor Driver](https://my.cytron.io/p-13amp-6v-30v-dc-motor-driver).

**Software:**  
* [Arduino IDE](https://www.arduino.cc/en/software)  

## Installation  
For the wiring SK40C(PIC16F877) to MD10C and DC Motor using **Sign-Magnitude PWM mode** you can refer the table below:  
| MD10C  | SK40C(PIC16F877)  |
| ------ | ----------------- |
| Power +| VDD(+5V)          |
| Power -| GND               |
| Motor A| Motor +           |
| Motor B| Motor -           |
| VIN    | VDD(+12V)         |
| DIR    | RA0               |
| PWM    | RC1               |
| GND    | GND               |

For **Locked-Antiphase PWM**:  
| MD10C  | SK40C(PIC16F877)  |
| ------ | ----------------- |
| Power +| VDD(+5V)          |
| Power -| GND               |
| Motor A| Motor +           |
| Motor B| Motor -           |
| VIN    | VDD(+12V)         |
| DIR    | RC1               |
| PWM    | RA0               |
| GND    | GND               |

## Related Tutorials  
* [MD10C Fast Testing](https://my.cytron.io/tutorial/md10c-fast-testing)  
* [Controlling 10A DC Motor Driver using Arduino Nano](https://my.cytron.io/tutorial/controlling-10a-dc-motor-driver-using-arduino-nano)   

YouTube videos:  
* [MD10C with Arduino](https://youtu.be/kA38GhkUOso)  
* [MD13S with Arduino](https://youtu.be/IXaNO6wflRk)  

## Documentation  
Datasheet for this product can be found here: 
* [MD10C Rev3.0 User's Manual](https://docs.google.com/document/d/1rgQzn-nWn-qcWNnHjDZvIYqUrdCeBQQxXA-TU3BF0AQ/view)  
* [MD13S User's Manual](https://docs.google.com/document/d/1icu1GVDxZhUn3ADSUc3JknNcmUMdPcsnJ4MhxOPRo-I/view)  

## Support  
Welcome to our [technical forum](http://forum.cytron.io) if you have further inquiry.  

