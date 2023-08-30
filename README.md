# Cambrian3DAtomsmack
Atomstack Cambrian 3D Printer revised firmware "Atomsmack" by Mateusz Modzelewski (facebook.com/aniolo55)

Since atomstack is refusing to provide suport i have created new firmware for printers for default mainboards:

- Atomstack Cambrian
- Atomstack Cambrian MAX

Warning, minor issue Filament sensor will be disabled! (TBD)
Please follow steps to upgrade your firmware to "Atomsmack 1.0"

- Place the printer firmly on the desk/solid surface
- Ensure everything is allright with your 3D printer before starting next upgrade steps ( I'm not responsible for skipping steps or uploading firmware in wrong order, or damaging your 3D Printer ) - if you hasitate, call out post with questions on Atomstack Cambrian 3D Printer Official User Group (Facebook)
From now on, do not skip any steps:
- Perform "Factory reset" 
- Perform bed leveling procedure
- Optionally run test.gcode (PLA FILAMENT 1.75 head), write down result
- Next, grab micro usb card reader or use laptop/pc built in one
- Upload firmware to your printer from folder "START" 
- Perform "Factory reset"
- Home your printer
- Select "Move" option, go XYZ + 10 at least
- Upload your selected firmware (NORMAL,MEDIUM,FAST)
- Perform "Factory reset"
- Home your printer
- Select "Move" option, go XYZ + 10 at least
- From now on, you will be using fixed development firmware that may or may not cause problems (post feedback)
- Upload firmware "BASE"
- Perform PID autotuning
- Home your printer
- Print test.gcode, check if everything is OK, optionally post your result including selected firmware
- DO NOT CLICK FACTORY RESET EVER AGAIN (or it will go for original firmware settings, making it super slow) You will have to repeat all steps again.
- Optionally repeat all steps if you want to test other firmware version
- Optionally you can rollback at anytime to stock firmware from website
- Enjoy your upgraded Atomsmack!

I will be happy any feedback on this firmware and testing above steps.
Say thank you by sending at least 1$ for a coffee!
Paypal [aniolo5@gmail.com](https://paypal.me/aniolo5?country.x=PL&locale.x=pl_PL)https://paypal.me/aniolo5?country.x=PL&locale.x=pl_PL

Yours, MM

