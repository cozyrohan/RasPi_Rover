## Description:
My Raspberry Pi Zero W Rover Control project came into existence when I saw a chassis from a trashed AWS DeepRacer Kit [including an esc, steering servo, and a 7.4v lipo] laying around in a parts bin.

The moment I saw it, I knew I had to bring it to life. The transmitter/controller and the reciever/pwm generators were missing. I set out to do this project with MINIMAL hardware overhead. Instead of buying a transmitter and reciever, I wanted to use only parts around the workshop. Thus, I scrounged a PS4 controller from a friend, an RPi Zero W (with bluetooth) and a usb power bank. Thus the project was started and completed a few weeks later. 

## Key Features:

Raspberry Pi Zero W: Use Raspberry Pi Zero W, a compact single-board computer, to control rover's movements and take input from the PS4 controller.

PS4 Controller Integration: Connect a PS4 controller to the Raspberry Pi Zero W via Bluetooth for rover control.

Can a gaming experience be simulated? --> Answer: Yes, but the shallow range of motion on the joysticks is makes it a little difficult to control the cars steering and throttle as well as one might wish. No wonder there is dedicated hardware optimized for RC after all...



## Dependencies / Instructions for Use

1. Create a VENV on your Pi in a directory of your choice.
2. Install the dependencies:
   
a) Follow this video to get the ps4 bluetooth driver up and running -->
more info on ds4drv: https://www.youtube.com/watch?v=CeyGP3_kKZI&ab_channel=ArturSpirin

b) sudo pip install pyPS4Controller -->
more info on pyPS4Controller:   https://www.youtube.com/watch?v=CeyGP3_kKZI&ab_channel=ArturSpirin
 
c) gpiozero (not a pip install, but watch this to understand whats going on) -->
https://www.youtube.com/watch?v=_fdwE4EznYo&ab_channel=GaryExplains

4. Connect ps4 controller to Raspberry Pi Zero and ensure that you can register/print joystick commands to the console!

5. Wire the control and power for the ESC and Steering servos 

6. Clone this repo, then run the entry script.
