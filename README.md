# 双轴按键摇杆模块

双轴按键摇杆模块用于控制机器人，舵机，马达的运动方向.

![8](https://user-images.githubusercontent.com/18615354/47488634-54c98180-d877-11e8-861f-667e8b720334.jpg)

## Usage

### How to connect a Grove - ThumbJoystick to Microbit

#### Prepare

Connecting a Grove - ThumbJoystick to Microbit is a bit tricky, but it is worth doing. So let's go!!

Firstly, we need to prepare a [Micro:bit](https://microbit.org/), a [Grove shield](https://www.seeedstudio.com/Grove-Inventor-Kit-for-micro-bit-p-2891.html), a tweezers(or needle), a scissors, a [Grove - Thumb Joystick](https://www.seeedstudio.com/Grove-Thumb-Joystick-p-935.html), and a [Grove - Branch Cable](https://www.seeedstudio.com/Grove-Branch-Cable-5PCs-pac-p-847.html).

**It is very very important to pay attention when using scissors and tweezers!**

![1](https://user-images.githubusercontent.com/18615354/47488623-52ffbe00-d877-11e8-824d-6f2254cb648c.jpg)

#### Step1

As the pictures shown, the Grove - Branch Cable has 3 connectors. We name them `Conector#1`, `Conector#2` and `Conector#3`. Note that `Conector#2` and `Conector#3` have no differences at first. 

Then carefully pick the **white cable** out of `Conector#2` with a tweezers(or needle). 

![2](https://user-images.githubusercontent.com/18615354/47488624-53985480-d877-11e8-8cf9-d99b62482caa.jpg)

#### Step2

Carefully pick the **yellow cable** and **white cable** out of `Conector#3` with a tweezers(or needle). 

![3](https://user-images.githubusercontent.com/18615354/47488628-53985480-d877-11e8-988c-32ed3ffe098f.jpg)

#### Step3

**Be careful not to cut the wrong cable!!!**

Cut the **white cable** of `Conector#2` and the **yellow cable** of `Conector#3`. 

![4](https://user-images.githubusercontent.com/18615354/47488629-5430eb00-d877-11e8-9bb2-22f211ee23d5.jpg)

#### Step4

Insert the **white cable** to the **first slot** of `Conector#3` as the picture shown.

![5](https://user-images.githubusercontent.com/18615354/47488630-5430eb00-d877-11e8-92a5-93d5df4be469.jpg)

#### Step5

Almost done!

Now we connect `Conector#2` to `P0/P14` port  and `Conector#3` to `P1/P15` port of Grove shield.

![6](https://user-images.githubusercontent.com/18615354/47488631-5430eb00-d877-11e8-9782-2f8a0c326a6b.jpg)


#### Step6

The last step! We connect `Conector#1` to Grove - Thumb Joystick and finish!

![7](https://user-images.githubusercontent.com/18615354/47488634-54c98180-d877-11e8-861f-667e8b720334.jpg)


### Demo 1: Display Arrow

Now let me show you how to program in Makecode.

After adding this package to Makecode, we can find a block named "on Key Up/Down/..". This block is similar to the base block "on button A/B pressed", it means if the key is at "Up" status, an [event handler](https://makecode.microbit.org/beta---docs#doc:reference/event-handler) is started. 

![8](https://user-images.githubusercontent.com/18615354/47495337-741bdb00-d886-11e8-9307-fc711b05a8a2.png)


![9](https://user-images.githubusercontent.com/18615354/47491944-7ed27200-d87e-11e8-91b6-a6d78e519981.jpg)

This is an example of showing some arrows when Grove - Thumb Joystick is manipulated.

![10](https://user-images.githubusercontent.com/18615354/47378018-6f8de000-d729-11e8-9de5-de7cd246f747.png)

## License
MIT
