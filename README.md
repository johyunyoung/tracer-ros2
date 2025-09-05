sudo modprobe gs_usb


- first time
cd ~/your_ws/src/ugv_sdk/scripts/
bash setup_can2usb.bash

- not first time
cd ~/ros2_ws/src/ugv_sdk/scripts/
bash bringup_can2usb_500k.bash

- test
candump can0


- launch
ros2 launch tracer_base tracer_base.launch.py

이후 cmd_vel 주고 움직이는지 확인.
