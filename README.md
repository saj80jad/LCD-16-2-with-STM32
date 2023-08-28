## Interfacing 16×2 LCD with STM32
this is Interfacing 16×2 LCD with bluePill board but you can use in all stm32 microcontroller.
just add lcd.h and lcd.c to your project.

## Wiering
| STM32 GPIO        | LCD pin       |
| ----------------- | ------------- |
| GPIOA0            | RS            |
| GPIOA1            | EN            |
| GPIOA2 : GPIOA5   | D4 : D7       |

![wiering](wiering.png)

## Describe code
``` c
LCD_Init(); //: is for Initialization'
LCD_SendCommand(uint8_t command); //: is for sending command'
LCD_WriteString(char* str); //: is for printing data on LCD'
LCD_Clear(); //: is for clearing LCD screen'
```

## list of command
![command of lcd](lcdCommand.png)![wiering](https://github.com/saj80jad/LCD-16-2-with-STM32/assets/143374386/37dc8b6b-8210-4471-96e2-a76672513ad6)
![lcdCommand](https://github.com/saj80jad/LCD-16-2-with-STM32/assets/143374386/654c3d94-0f74-4f86-a8d4-5ca31cc82eb0)
