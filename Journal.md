# Roco-222-Coursework

## DC Brushless Motor: Part 1

For the first Lab the main aim and objective was to create a brushless motor consisting of one coil of wire. For this task we were provided with the following materials:
- 10m of copper wire 
- 1 cork 
- Enameled Copper tape
- 1 wodden base 
- 4 washers 
- 4 screws
- 2 Nails
- 4 neodymium magnets
- 2 large paper clip

The first step to building the motor was to make a comutator. The comutator allows us to continue to provide a force in one dirrection, this is achieved by switching the polarisation of the circuit. The comutator is comprised of two seperate pieces of copper tape which are the same size and placed onto one side of the cork with a small gap inbetween. Once stuck in place we then inserted one nail into either side of the cork to act as an axle. We then proceeded to wrap the length of wire around the cork, making sure to keep count of the number of turns and to keep either end of the wire expossed.

![Comutator](https://github.com/bwickenden/Roco-222-Coursework/blob/master/Motor%201.jpg)

The total numnber of turns on the motor was 125 turns, and once fully wraped we used a piece of sandpaper to scratch off the enamel so then the wire is able to conduct a current. Then we soldered each end of the wire onto one piece of the comutator each. After soldering we used a multi metre to test the connection and then took a reading of the resitance of the wire which we found to be 7.3ohms. Once this step was complete the intial build of the motor was finished. 

![Winding the coil](https://github.com/bwickenden/Roco-222-Coursework/blob/master/Winding%20the%20coil.jpg)

After the motor was finshed we then had to build a base that the motor would be mounted onto. We used washers and screws to attach two large paper clips to either side of the wooden base which the motor would be able to rest on. We then attached two other paper clip to the other two sied of the base where our magnets would be attached to allowing our motor to be inbetween our mangnets. Two large wires were then attached to the power supply which were then used as the brushes for the motor.

## DC Brushless Motor: Part 3
Now that our motor was working we were tasked with improving our design. The first way in which we did this was to add a second armature coil to our motor. To do this we used another 10 metre length of the same enameled wire and wound the wire onto the cork so then it was perpendicular to the first coil. We also make and soldered a new comutator onto the motor which had four connections (One for each end of wire). With the new motor assembled we then went on to build a system that would keep the brushes for the motor in place. To achieve this we used a very simple design which was comprised of washers and paper clips, the wires that we used for the brushes were thick enough to hold their shape once held down with our set up. Out of all of our designs this motor worked the best however we did go on to create serveral different designs of motor. Listed bellow are the different variations of our designs: 

1. The basic motor which had just one addational aramature coil with 125 turns of wire on each. The motor wasn't very pretty but it worked really well 12v and held a very high but stable rpm. The main reason for the second coild was to keep a continous rpm and a stable rotation. In addtion we added some tape at either end for stablility.

![Original Motor](https://github.com/bwickenden/Roco-222-Coursework/blob/master/The%20best.jpg)
![Improved Motor](https://github.com/bwickenden/Roco-222-Coursework/blob/master/Improved%20motor%20working.mp4)
(Apologies for the poor video, our original video became corrupted and this was the only other video that we had of it working.)

2. The 3D Printed motor which was designed to have four aramature coils of 250 windings on each. The motor and built in comutator was design that we decided to have 3D printed, we wanted to created a motor that pushed its self to the limit. However unfortunately this design didn't turn out to be very good at all. We concluded that this was down to three design flaws: 

- Firstly we think that the magnetic field wasn't strong enough for the weight of the motor. This was down to the fact that the motor has a lot of wasted space at its core and we believe that the motor would have been more effiecnt if the armature coils were closer to the core of the motor. A way in which we could have solved this would have been to add a soft iron core to our motor. Soft iron has a high magnetic permability which causes the magnetic field lines to become more concentrated. 

- Secondly I think that the pieces of copper tape were too far appart on comutator which allowed for too much time to pass between the brushes leaving one connection and reconecting with another. 

- Lastly we had to provide our own wire for this motor, which turned out to be quite a bit thinner than the original motor. I think that because the wire was so thin and much longer than the original length of wire that we used in our previous motor it caused the aramature coils to have too high of a resistance and thus the motor ran very inefficiently. In order for the motor to turn it had to be supplied with a much higher voltage and which then ment that the motor became hot much faster.

Due to this and the other two points previously stated we decided to continue with our original adaptation as it just simply ran a lot better. The 3D printed design did have some nice qualities such as dividers between armature coils which allowed each coil to be neatly arranged, which also made it much easier to wrap in the first place. The other feature that I also really liked was that we designed it so that the encoder could be fixed onto the core. We achieved this by printing the comutator with legs and then drilled holes into the top of the core which allowed the legs would slot into. By doing this enabled us to a strong connection between to two pieces which would help to keep the motor as stable as possible whilst rotating at high speeds. 

![3D Printed Motor 1](https://github.com/bwickenden/Roco-222-Coursework/blob/master/3D%20Printed%201.jpg)
![3D Printed Motor 2](https://github.com/bwickenden/Roco-222-Coursework/blob/master/3D%20Printed%202.jpg)
![3D Printed Motor 3](https://github.com/bwickenden/Roco-222-Coursework/blob/master/3D%20Printed%203.jpg)
![3D Printed Model](https://github.com/bwickenden/Roco-222-Coursework/blob/master/Motor(Ben%20and%20Dan).stl)

In addition to these two designs we also created serveral others which explored a variety of different options, however we decided to mainlty focus on the other two designs. 

![Other Motors](https://github.com/bwickenden/Roco-222-Coursework/blob/master/Variations.jpg)

## Encoder

## Motor Control with Arduino

## Stepper Motors

## Robotic Arm mini-project: Servo control

For this part of the project we had to design and build a robotic arm that had 2 degrees of freadom. The first part of this task was learning how to control the two servos. To do this at first we used very basic code which moved the servos in a set pattern but didn't provide any additional control once the code was loaded. Below I have provided a snippit of the code that we used for this task. 
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
After we had achieved the basics of servo control we then moved on to create a 3D model of our Robotic arm. This was the first time that we had used AutoDesk Fusion 360 so this task at first was quite difficult. We went into the task with the aim to make a compact robotic arm that wouldn't take up too much space and that could be quite cheap to reproduce. In the end we settled with a design that is shown bellow. We were very happy with the outcome but there are a few improvements that could be made. Firstly we didn't give enough leeway for the servos to fit the way that we wanted. This then lead to hours of filing down the edeges of the model. Secondly the model is too light and would benefit from being mounted onto a wooden base for extra support as if you were to move the arm of the robot too quicly you could throw it off balance. Lastly I would have liked to added a small motor on the end of the arm which could be used to create a crane like function. It would have been nice to add however it wasn't practical at the time to implement. 

![Servo](https://github.com/bwickenden/Roco-222-Coursework/blob/master/Robotic_Arm.stl)
![Crane Arm](https://github.com/bwickenden/Roco-222-Coursework/blob/master/Crane%20Arm.stl)
![Main Body](https://github.com/bwickenden/Roco-222-Coursework/blob/master/Arm.stl)
![Base](https://github.com/bwickenden/Roco-222-Coursework/blob/master/Main%20Body.stl)
![Finished Robot](https://github.com/bwickenden/Roco-222-Coursework/blob/master/Finished%20Robot.jpg)

Now that we have a finished and printed robotic arm we then went on to write some code which would enable us to control the robotic arm using potentiometers. Listed bellow is the code that we went on to use in order to have manual control over the servos. 
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
This part of the work was a lot of fun and we both really enjoyed it as it was at this moment that you could really see your robotic arm working exactly how you invisioned it when designing it. We made a few changes in relation to the potentiometers, at first we soldered them onto a piece of veroboard but we then later decided that it would be eaiser to have the potentiometers plugged into a breadboard incase we wanted to make any changes. 

![Potentiometer control](https://github.com/bwickenden/Roco-222-Coursework/blob/master/Potentiometer%20control.mp4)

## Robotic Arm mini-project: Servo control





