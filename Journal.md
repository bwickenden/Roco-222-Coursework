# Roco-222-Coursework

## DC Brushless Motor: Part 1

For the first Lab the main aim and objective was to create a brushless motor consisting of one coil of wire. For this task we were provided with the following materials:
- 10m of copper wire 
- 1 cork 
- Enamelled Copper tape
- 1 wooden base 
- 4 washers 
- 4 screws
- 2 Nails
- 4 neodymium magnets
- 2 large paper clip

The first step to building the motor was to make a commutator. The commutator allows us to continue to provide a force in one direction, this is achieved by switching the polarisation of the circuit. The commutator is comprised of two separate pieces of copper tape which are the same size and placed onto one side of the cork with a small gap inbetween. Once stuck in place we then inserted one nail into either side of the cork to act as an axle. We then proceeded to wrap the length of wire around the cork, making sure to keep count of the number of turns and to keep either end of the wire exposed.

![Comutator](https://github.com/bwickenden/Roco-222-Coursework/blob/master/Motor%201.jpg)

The total number of turns on the motor was 125 turns, and once fully wrapped we used a piece of sandpaper to scratch off the enamel so then the wire is able to conduct a current. Then we soldered each end of the wire onto one piece of the commutator each. After soldering we used a multi metre to test the connection and then took a reading of the resistance of the wire which we found to be 7.3ohms. Once this step was complete the initial build of the motor was finished. 

![Winding the coil](https://github.com/bwickenden/Roco-222-Coursework/blob/master/Winding%20the%20coil.jpg)

After the motor was finished we then had to build a base that the motor would be mounted onto. We used washers and screws to attach two large paper clips to either side of the wooden base which the motor would be able to rest on. We then attached two other paper clip to the other two sides of the base where our magnets would be attached to allowing our motor to be inbetween our magnets. Two large wires were then attached to the power supply which were then used as the brushes for the motor.

## DC Brushless Motor: Part 2
Now that our motor was working we were tasked with improving our design. The first way in which we did this was to add a second armature coil to our motor. To do this we used another 10 metre length of the same enamelled wire and wound the wire onto the cork so then it was perpendicular to the first coil. We also make and soldered a new commutator onto the motor which had four connections (One for each end of wire). With the new motor assembled we then went on to build a system that would keep the brushes for the motor in place. To achieve this we used a very simple design which was comprised of washers and paper clips, the wires that we used for the brushes were thick enough to hold their shape once held down with our set up. Out of all of our designs this motor worked the best however we did go on to create several different designs of motor. Listed bellow are the different variations of our designs: 

1. The basic motor which had just one additional armature coil with 125 turns of wire on each. The motor wasn't very pretty but it worked really well 12v and held a very high but stable rpm. The main reason for the second coil was to keep a continous rpm and a stable rotation. In addition we added some tape at either end for stability.

![Original Motor](https://github.com/bwickenden/Roco-222-Coursework/blob/master/The%20best.jpg)
![Improved Motor](https://github.com/bwickenden/Roco-222-Coursework/blob/master/Improved%20motor%20working.mp4)
(Apologies for the poor video, our original video became corrupted and this was the only other video that we had of it working.)

2. The 3D Printed motor which was designed to have four armature coils of 250 windings on each. The motor and built in commutator was design that we decided to have 3D printed, we wanted to created a motor that pushed its self to the limit. However unfortunately this design didn't turn out to be very good at all. We concluded that this was down to three design flaws: 

- Firstly we think that the magnetic field wasn't strong enough for the weight of the motor. This was down to the fact that the motor has a lot of wasted space at its core and we believe that the motor would have been more efficient if the armature coils were closer to the core of the motor. A way in which we could have solved this would have been to add a soft iron core to our motor. Soft iron has a high magnetic permability which causes the magnetic field lines to become more concentrated. 

- Secondly I think that the pieces of copper tape were too far apart on commutator which allowed for too much time to pass between the brushes leaving one connection and reconnecting with another. 

- Lastly we had to provide our own wire for this motor, which turned out to be quite a bit thinner than the original motor. I think that because the wire was so thin and much longer than the original length of wire that we used in our previous motor it caused the aramature coils to have too high of a resistance and thus the motor ran very inefficiently. In order for the motor to turn it had to be supplied with a much higher voltage and which then meant that the motor became hot much faster.

Due to this and the other two points previously stated we decided to continue with our original adaptation as it just simply ran a lot better. The 3D printed design did have some nice qualities such as dividers between armature coils which allowed each coil to be neatly arranged, which also made it much easier to wrap in the first place. The other feature that I also really liked was that we designed it so that the encoder could be fixed onto the core. We achieved this by printing the commutator with legs and then drilled holes into the top of the core which allowed the legs would slot into. By doing this enabled us to a strong connection between to two pieces which would help to keep the motor as stable as possible whilst rotating at high speeds. 

![3D Printed Motor 1](https://github.com/bwickenden/Roco-222-Coursework/blob/master/3D%20Printed%201.jpg)
![3D Printed Motor 2](https://github.com/bwickenden/Roco-222-Coursework/blob/master/3D%20Printed%202.jpg)
![3D Printed Motor 3](https://github.com/bwickenden/Roco-222-Coursework/blob/master/3D%20Printed%203.jpg)
![3D Printed Model](https://github.com/bwickenden/Roco-222-Coursework/blob/master/Motor(Ben%20and%20Dan).stl)

In addition to these two designs we also created several others which explored a variety of different options, however we decided to mainly focus on the other two designs. 

![Other Motors](https://github.com/bwickenden/Roco-222-Coursework/blob/master/Variations.jpg)

## Encoder
This task was all about trying to measure the rpm of our motor. The first part was to build the physical circuit of the encoder which was comprised of an Infrared transmitter and receiver. The way in which the device counted the rotations of the motor was by detecting when no signal was revceived. This was implemented with motor by placing a cardboard disk onto the axel which had a segment cut out of it which would be used to detect one rotation. 
![Encoder circuit](https://github.com/bwickenden/Roco-222-Coursework/blob/master/Encoder.jpg)
![Encoder on first Motor](https://github.com/bwickenden/Roco-222-Coursework/blob/master/Encoder%20on%20motor.jpg)
![Encoder on 3D printed Motor](https://github.com/bwickenden/Roco-222-Coursework/blob/master/Encoder%203D%20printed%20model.jpg)

We did have a few problems with this task and struggled to get the encoder working properly, we think that it was down to two point. 
1. The circuit had a loose connection somewhere which caused unreliable results. 
2. It was quite difficult to keep the encoder in place and so we think that this might have caused some of the issues that we had when trying to get some results. 

## Motor Control with Arduino
For this task added the Motor Shield and then we implemented the code give to control the small hobby motor. We found that by changing the delays in the code we could change how long the motor span for, with the implementation of the analogue values we could change the speed and that the direction was caused by setting the pins high and low.
```void setup() {
//Setup Channel A
pinMode(12, OUTPUT); //Initiates Motor Channel A pin
pinMode(9, OUTPUT); //Initiates Brake Channel A pin
}
void loop(){
Page 4 of 6
Practical 3: Controlling the motor
//forward @ full speed
digitalWrite(12, HIGH); //Establishes forward direction of Channel A
digitalWrite(9, LOW); //Disengage the Brake for Channel A
analogWrite(3, 255); //Spins the motor on Channel A at full speed
delay(6000);
digitalWrite(9, HIGH); //Engage the Brake for Channel A
delay(1000);
//backward @ half speed
digitalWrite(12, LOW); //Establishes backward direction of Channel A
digitalWrite(9, LOW); //Disengage the Brake for Channel A
analogWrite(3, 123); //Spins the motor on Channel A at half speed
delay(6000);
digitalWrite(9, HIGH); //Eengage the Brake for Channel A
delay(1000);
}
```
![Hshield](https://github.com/bwickenden/Roco-222-Coursework/blob/master/Hshield.jpg)
Due complications with the encoder as stated above we were unable to control the motor with the Arduino.

## Stepper Motors
For this lab we were tasked with we were tasked with wiring up a stepper motor. In order to do this we modified some example code which  I'll provide a snipping of the code bellow. 
```
#define DIR_A 12
#define PWM_A 3
#define DIR_B 13
#define PWM_B 11
const int delayMs = 100;
void setup() {
pinMode(DIR_A, OUTPUT);
pinMode(DIR_B, OUTPUT);
pinMode(9, OUTPUT); digitalWrite(8, LOW); //No braking ch. A
pinMode(8, OUTPUT); digitalWrite(8, LOW); //No braking ch. B
}
```


## Robotic Arm mini-project: Servo control

For this part of the project we had to design and build a robotic arm that had 2 degrees of freedom. The first part of this task was learning how to control the two servos. To do this at first we used very basic code which moved the servos in a set pattern but didn't provide any additional control once the code was loaded. Below I have provided a snippet of the code that we used for this task. 
```
digitalWrite(9, HIGH); 
delay(2);
digitalWrite(9, LOW); 
delay(78);
digitalWrite(9, HIGH); 
delay(2);
digitalWrite(9, LOW); 
delay(78); 
```
After we had achieved the basics of servo control we then moved on to create a 3D model of our Robotic arm. This was the first time that we had used AutoDesk Fusion 360 so this task at first was quite difficult. We went into the task with the aim to make a compact robotic arm that wouldn't take up too much space and that could be quite cheap to reproduce. In the end we settled with a design that is shown below. We were very happy with the outcome but there are a few improvements that could be made. Firstly we didn't give enough leeway for the servos to fit the way that we wanted. This then lead to hours of filing down the edges of the model. Secondly the model is too light and would benefit from being mounted onto a wooden base for extra support as if you were to move the arm of the robot too quickly you could throw it off balance. Lastly I would have liked to added a small motor on the end of the arm which could be used to create a crane like function. It would have been nice to add however it wasn't practical at the time to implement. 

![Servo](https://github.com/bwickenden/Roco-222-Coursework/blob/master/Robotic_Arm.stl)
![Crane Arm](https://github.com/bwickenden/Roco-222-Coursework/blob/master/Crane%20Arm.stl)
![Main Body](https://github.com/bwickenden/Roco-222-Coursework/blob/master/Arm.stl)
![Base](https://github.com/bwickenden/Roco-222-Coursework/blob/master/Main%20Body.stl)
![Finished Robot](https://github.com/bwickenden/Roco-222-Coursework/blob/master/Finished%20Robot.jpg)

Now that we have a finished and printed robotic arm we then went on to write some code which would enable us to control the robotic arm using potentiometers. Listed below is the code that we went on to use in order to have manual control over the servos. 
```
#include <Servo.h>
Servo servo1;
Servo servo2;
int potpin1 = 0;
int potpin2 = 5;
int val1;
int val2;
void setup()
{
servo1.attach(9);
servo2.attach(7);
}
void loop()
{
val1 = analogRead(potpin1); 
val2 = analogRead(potpin2); 
                 
val1 = map(val1, 0, 1023, 0, 179); 
val2 = map(val2, 0, 1023, 0, 179); 
                  
servo1.write(val1); 
servo2.write(val2);   
         
delay(1);      
}
```
This part of the work was a lot of fun and we both really enjoyed it as it was at this moment that you could really see your robotic arm working exactly how you envisioned it when designing it. We made a few changes in relation to the potentiometers, at first we soldered them onto a piece of veroboard but we then later decided that it would be easier to have the potentiometers plugged into a breadboard incase we wanted to make any changes. 

![Potentiometer control](https://github.com/bwickenden/Roco-222-Coursework/blob/master/Potentiometer%20control.mp4)

## Robotic Arm mini-project: ROS

The next part of our project was to learn how use ROS to control our robotic arm. The first step was to configure the Arduino so then it was connected with ROS. After we had connected the Arduino we wrote some code which would allow us to control the robotic arm using the terminal. 

```
#include <ros.h>
#include <std_msgs/UInt16.h>
#include <Servo.h>

using namespace ros;

NodeHandle nh;
Servo servo1;
Servo servo2;

void cb1( const std_msgs::UInt16& msg){
  servo1.write(msg.data);
}


void cb2( const std_msgs::UInt16& msg){
  servo2.write(msg.data);
}

Subscriber<std_msgs::UInt16> sub1("servo1", cb1);
Subscriber<std_msgs::UInt16> sub2("servo2", cb2);

void setup(){
    nh.initNode();
    nh.subscribe(sub1);
    nh.subscribe(sub2);

   servo1.attach(9);
   servo2.attach(7);
}

void loop(){
  nh.spinOnce();
  delay(1);
}

```
The next step was to create a 3D model using Rviz, to do this we had to load and modify a urdf file. This task was quite difficult as we had to design the entire model only using code which was a challenge but over all it went quite well and we managed to create a model which resembled our model.

![Original Model](https://github.com/bwickenden/Roco-222-Coursework/blob/master/Rviz%20Original.png)
![Modified Model](https://github.com/bwickenden/Roco-222-Coursework/blob/master/Rviz%20Mod.mp4)
![Modified URDF File](https://github.com/bwickenden/Roco-222-Coursework/blob/master/URDF%20file.PNG)


Control the servo motors from the robot's joint state: Unfortunately we ran out of time and wasn't able to get this part working. 

