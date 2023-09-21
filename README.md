## Description:
My Raspberry Pi Zero W Rover Control project came into existance when I saw a cool chassis from a trashed AWS DeepRacer Kit [including an esc, steering servo, and a 7.4v lipo] laying around in a parts bin.

The moment I saw it, I knew I had to bring it to life. The missing pieces were the transmitter/controller and the reciever/pwm generators. I set out to do this project with MINIMAL hardware overhead. Instead of buying a transmitter and reciever, I wanted to use only parts around the workshop. Thus, I scrounged a PS4 controller from a friend, an RPi Zero W (with bluetooth) and a usb power bank. Thus the project was started and completed a few weeks later. 

## Key Features:

Raspberry Pi Zero W: Use Raspberry Pi Zero W, a compact single-board computer, to control rover's movements and take input from the PS4 controller.

PS4 Controller Integration: Connect a PS4 controller to the Raspberry Pi Zero W via Bluetooth for rover control.

Can a gaming experience be simulated? --> Answer: Yes, but the shallow range of motion on the joysticks is makes it a little difficult to control the cars steering and throttle as well as one might wish. No wonder ther is dedicated hardware for this after all...



## Dependencies / Instructions for Use

1. Create a VENV on your Pi in a directory of your choice.
2. Install the dependencies:
         a) Follow this video to get the ps4 bluetooth driver up and running -->
   more info on ds4drv: https://www.youtube.com/watch?v=CeyGP3_kKZI&ab_channel=ArturSpirin
         b) sudo pip install pyPS4Controller -->
   more info on pyPS4Controller:   https://www.youtube.com/watch?v=CeyGP3_kKZI&ab_channel=ArturSpirin

1. Connect ps4  controller to Raspberry Pi Zero
