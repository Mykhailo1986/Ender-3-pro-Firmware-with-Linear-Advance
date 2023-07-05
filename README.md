# Ender-3-pro-Firmware-with-Linear-Advance<br>
## Українська (Ukrainian)
Це прошивка для Ender 3 Pro Українська, увімкнутий Linear Advance, Marlin 2.1.2  (board 4.2.2, STM32F103RET6 controller,  stepper motor driver MC2225)<br>
Прошивка просто кидаеш [bінарник](https://github.com/Mykhailo1986/Ender-3-pro-Firmware-with-Linear-Advance/realice) на cd_card тa вмикаеш Ender 3 pro<br>
Як дізнатись борд: дивись в меню <br>
Як дізнатись контроллер:  якщо на чипі написано остання строка ARM  та друга RET6 (У мене перша GD32F303)<br>
[Як дізнатись який у вас драйвер крокового двигуна:](https://www.reddit.com/r/ender3/comments/uh02go/cant_identify_stepper_drivers_on_creality_422/)
Дивись на кардрідері борда, у мене наклейка [8Н](https://i.redd.it/need-help-identifying-stepper-driver-on-ender-3-pro-v4-2-2-v0-77bqmpqype891.jpg)<br>
  -  C = HR4988
  -  E = A4988
  -  A = TMC2208
  -  B = TMC2209
  -  H = [TMC2225](https://www.youmaketech.com/wp-content/uploads/2022/01/TMC2225-Specifications.pdf)<br>
Marlin configuration.h: Use TMC2208/TMC2208_STANDALONE for TMC2225 drivers
><br>

## English
This is [firmware](https://github.com/Mykhailo1986/Ender-3-pro-Firmware-with-Linear-Advance/realice) for Ender 3 Pro in Ukrainian, with Linear Advance enabled, Marlin 2.1.2 (board 4.2.2, STM32F103RET6 controller, stepper motor driver MC2225).<br>
How to determine the board: check in the menu.<br>
How to determine the controller: if the last line on the chip says ARM and the second line says RET6 (I have GD32F303 as the first line).<br>
[How to determine your stepper driver:](https://www.reddit.com/r/ender3/comments/uh02go/cant_identify_stepper_drivers_on_creality_422/)
Look at the card reader on the board, mine has the label [8Н](https://i.redd.it/need-help-identifying-stepper-driver-on-ender-3-pro-v4-2-2-v0-77bqmpqype891.jpg):<br>
- C = HR4988
- E = A4988
- A = TMC2208
- B = TMC2209
- H = [TMC2225](https://www.youmaketech.com/wp-content/uploads/2022/01/TMC2225-Specifications.pdf)<br>
Marlin configuration.h: Use TMC2208/TMC2208_STANDALONE for TMC2225 drivers.<br>

To update the firmware on your Ender 3 Pro with Linear Advance and Ukrainian language support, follow these instructions:<br>
Note: Make sure you have a stable power supply and take appropriate precautions while updating the firmware.<br>

Download the firmware:<br>
Click on the firmware file and then click the "Download" button to save it to your computer. The file should have a name like ["Ender3Pro_LiniarAdvance_UKR_multilingual.bin"](https://github.com/Mykhailo1986/Ender-3-pro-Firmware-with-Linear-Advance/blob/main/Ender3Pro_LiniarAdvance_UKR_multilingual.bin).<br>
Prepare an SD card:<br>

- Take an empty SD card (preferably 8GB or smaller) and format it to FAT32 file system.
- Copy the downloaded firmware file "Ender3Pro_LiniarAdvance_UKR_multilingual.bin" to the root directory of the SD card.
- Safely eject the SD card from your computer.
- Turn off your Ender 3 Pro and insert the prepared SD card into the SD card slot on the printer.
- Power on the printer and wait for the firmware update to start.<br>
The update process may take a few minutes. Do not interrupt power during this time.<br>
Once the update is complete, the printer will start automatically.
- Remove the SD card from the printer.

That's it! You have successfully updated the firmware on your Ender 3 Pro with Linear Advance and Ukrainian language support.


