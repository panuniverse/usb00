# usb00
Exercises on 圈圈教你玩USB with SDCC

## history
* 2016/04/12 out of CRD, start working for SAV under Eric. Target of that time was to learn USB UVC/UAC, and MIDI by the way, as well as Windows/Linux/iOS kernel, and application programming.
* 2016/10/26 suspend due to working on 8148
* 2017/03/01 p000 
  To prove sdcc can replace KEIL. The program lightens up all LEDs connected to port 2.
* 2017/03/01 p001
  Learn how to write timer0 interrupt in sdcc. This program blinks LEDs connected to port 2 every 1 second. 
* 2017/03/09 p002
  Learn how to implement printf.
* 2017/05/06 move to a new branch and restart again
* 2017/05/10 p003 modulize codes. note: "If you have multiple source files in your project, interrupt service routines can be present in any of them, but a prototype of the isr MUST be present or included in the file that contains the function main.
* 2017/05/14 p004 add key

installation
$ sudo apt-get install -y sdcc
