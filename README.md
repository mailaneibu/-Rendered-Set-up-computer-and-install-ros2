# -Rendered-Set-up-computer-and-install-ros2

# Set up computer and install ros2



## Download ubuntu

- Download ubuntu 22.04 desktop on personal computer
[https://docs.google.com/document/d/1n_PtpIUUcK-SeW0rHteTiTLYI3NpxOOHtgTdMi5x5fA/edit?usp=sharing](https://docs.google.com/document/d/1n_PtpIUUcK-SeW0rHteTiTLYI3NpxOOHtgTdMi5x5fA/edit?usp=sharing)
- Download Rufus software in order to put ubuntu on a usb device
[https://rufus.ie/en/#google_vignette](https://rufus.ie/en/#google_vignette)

## For reset the computer that we want to set up
- Put the usb in the port
- Turn on the computer or restart it and click quickly on 'F12' or 'delete'
- Chose ubuntu (enter)

Normally you will be in bios : 

IMAGE

-Go in 'Boot Sequence' and choose your device (for us it is the usb) then click on 'apply'

If there is a security error : 

IMAGE

Go in 'security' in the boot
- click exit, then click yes to erase the computer and set up a new one with ubuntu

## Install ROS2 Humble : 
- Follow this tutorial :  [https://github.com/Jaeyoung-Lim/px4-offboard/pull/8/files]( https://github.com/Jaeyoung-Lim/px4-offboard/pull/8/files)


```python
'unlocated package' error due to a comment '#QGroundControl' in a code 

```

Then, in '###run the demo' --> 'micro-ros-agent : 
you have to source it 
```
$source install/local-setup.sh
```


