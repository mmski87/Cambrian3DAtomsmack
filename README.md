# Cambrian3DAtomsmack
Atomstack Cambrian 3D Printer revised firmware "Atomsmack" by Mateusz Modzelewski (facebook.com/aniolo55)

Since atomstack is refusing to provide suport i have created new firmware for printers for default mainboards:

- Atomstack Cambrian PRO (READY)
- Atomstack Cambrian MAX (IN DEVELOPMENT)

Warning, TESTING IN PROGRESS
Please follow steps to upgrade your firmware to "Atomsmack 1.0"

- Place the printer firmly on the desk/solid surface
- Ensure everything is allright with your 3D printer before starting next upgrade steps ( I'm not responsible for skipping steps or uploading firmware in wrong order, or damaging your 3D Printer ) - if you hasitate, call out post with questions on Atomstack Cambrian 3D Printer Official User Group (Facebook)
From now on, do not skip any steps:
- Perform "Factory reset" (Settings -> System info -> restore factory settings)
- Perform bed leveling procedure
- Optionally run test.gcode (PLA FILAMENT 1.75 head), write down result how much time it takes
- Next, grab micro usb card reader or use laptop/pc built in one
- Upload firmware to your printer from folder "1st firmware"  (POWER OFF, INSERT SD CARD, POWER ON, GREEN LIGHT, WAIT FOR UPDATE)
- !!IMPORTANT!! Perform "Factory reset"
- Home your printer
- Perform PID autotuning
- Upload firmware to your printer from folder "2nd firmware"  (POWER OFF, INSERT SD CARD, POWER ON, GREEN LIGHT, WAIT FOR UPDATE)
  
- From now on, you will be using fixed development firmware that may or may not cause problems (post feedback)
- DO NOT FACTORY RESET AFTER THIS STEP
- Home your printer
- Print test.gcode, check if everything is OK, optionally post your result to my email
- Optionally repeat all steps if you want to test other firmware version
- Optionally you can rollback at anytime to stock firmware from "2nd firmware" folder
- Enjoy your upgraded Atomsmack!

TEST GCODE SETTINGS:
230*C/60*C
100mm/s speed // 2000 mm/s² acceleration

I will be happy any feedback on this firmware and testing above steps.
Say thank you by sending at least 1$ for a coffee!
Paypal [aniolo5@gmail.com]

Yours, MM

