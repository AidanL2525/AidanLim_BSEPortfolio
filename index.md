# Aidan's Three Joint Robotic Arm
Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails!

You should comment out all portions of your portfolio that you have not completed yet, as well as any instructions:
```HTML 
<!--- This is an HTML comment in Markdown -->
<!--- Anything between these symbols will not render on the published site -->
``` 

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Aidan L | Leigh High School | Mechanical Engineering | Incoming Sophomore

<!--- **Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg) -->
  
# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE 

# Second Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/62v-hwCqD9Y?si=V5SEFIW0lsW38_ax" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


My second Milestone shows the compatibility of the servo to my Arduino. The micro servo has many gears and a small circuit board that can control how much the gears turn through inputs. These inputs can be read through my Arudino IDE on my computer that outputs the information to my Arduino. The data then flows through the three female to female wires into the servo's circuit board. The numbers I input are numerical and each represents an angle. For example, if I input the number 3, the servo will rotate 60 degrees. These servos will be used to move the base, joints, and pincers of the robotic arm. So far, the instructions have been fairly easy to follow, only consisting of testing the robotic components. 

The problem I had faced during my second Milestone was trying to get the servos working. My instructor Ben and I tried many things to make it function, even gathering data using the oscilloscope to see if the Arduino was actually making an output. We then decided to search up the servo online and realized it needed 4.8 volts to activate. We figured that my computer was outputting some amount of voltage into my Arduino because it was working when testing my joystick, but not enough energy to power the servos. We fixed this problem by easily attatching batteries into the Arduino. 

To reach my final Milestone, I would need to build my robotic arm and finally test it.

# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/zen-y9g0eFM?si=V7BoQDgwfVFaTILo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

My first Milestone demonstrates the functions of the joystick to my Arduino. The displacement of the joystick is measured using a potentiometer. Potentiometers create a graph that contain x and y axes to display the location numarically of the joystick. These inputs are first fed through three female to female wires into the Arduino to finally transfer into the Arduino IDE on my computer. The output is shown using a serial motor that constantly sends lines of x, y, and z points depending on the joystick position. But the z axis will stay as 0 beacause the potentiometer does not calculate the displacment in height even when the joystick is pressed down. I have currently not built anything of the physical robot, but have only tested my systems and code.

The only minor problems I had faced during my first Milestone was trying to place the female to female wires onto the Arduino pins. The pins are tightly grouped and leave very little space for each wire to slot in. The heads of the wire were also very loose, making it very easy to unplug if tugged slightly. The only solution to my challenges are to be careful with the wires and to have patience when connecting them to my Arduino.

My plan to complete my project is to follow each and every step of my main project guide properly and precisely. 

<!--- # Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
``` -->

# Bill of Materials

| Cokoino Robotic Arm | Cokonio's building kit of 3 Joint Robotic Arm | $49.99 | <a href="https://www.amazon.com/LK-COKOINO-Compliment-Engineering-Technology/dp/B081FG1JQ1"> Link </a> |
| YIKESHU 2WD Smart Robot Car Chassis Kit | Mobility for the 3 Joint Robotic Arm | $18.99 | <a href="https://www.amazon.com/YIKESHU-Smart-Chassis-Encoder-Battery/dp/B073VHQT6P/ref=sr_1_2?crid=PJ0L8E9W0VVU&dib=eyJ2IjoiMSJ9.rAtzeTMewjqQtbfHoPTpllczQ2na8OWPtlJRUuewEoY.Hsresp6GxwOBatjmspXvGbFKHDawa3rjwxLRsZ6dDOA&dib_tag=se&keywords=yikeshu+2wk+smart+robotic+car&qid=1718731589&s=toys-and-games&sprefix=yikeshu+2wk+smart+robotic+c%2Ctoys-and-games%2C154&sr=1-2"> Link </a> |
| HiLetgo HC-05 Wireless Bluetooth RF Transceiver | Bluetooth transmitter to Android phone | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |

<!--- # Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/) -->
- 

# Starter Project: Retro Arcade Console 

<iframe width="560" height="315" src="https://www.youtube.com/embed/UlN1hSnhQcY?si=dF2FZOEe-0TgTIOz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

This is the Retro Arcade Console Starter Project. The console uses the pre-soldered CPU on the board to read the input of the seven buttons to determine its next action based of its pre-coded information. It sends binary code, series of 1's and 0's, to the LED's to tell each LED to either turn on or off. There are two options to power the arade: USB and batteries. The Arcade is powered by three AAA batteries, connected through a red and black wire to the USB port to describute energy to all components. 

I fought against two main problems: making the buzzer work and going back to fix my work. The instructors and I could not fix it because we did not understand why it is shorting. The two solders were very far apart yet the multimeter was still reading a short. We tried using a wick to pick up any metal particles inbetween the two solders and Another problem I faced was having the fix my mistakes along the way. I strugged on having to go back on my work to make all of the components work properly. I had many errors such as the solder not fully touching the board and some shorts on the LED panel that caused two columns of LED's to not function. 

The lesson I learned with my starter project is to be cautious and accurate with my work. This will help me progess through my final project smoothly without any difficulties. After finishing my starter project, I will be working on my main project which is the three joint robotic arm. 

<!--- # Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs.-->

```c++

#include <Servo.h>
#include <Joystick.h>

Servo Servo_1;
Servo Servo_2;
Servo Servo_3;
Servo Servo_4;

struct ServoTarget {
  int ServoLocation;
  int ServoDestination;
};

ServoTarget ServoTarget_1;
ServoTarget ServoTarget_2;
ServoTarget ServoTarget_3;
ServoTarget ServoTarget_4;

void setup() {
  // put your setup code here, to run once:

  Servo_1.attach(4);
  Servo_2.attach(5);
  Servo_3.attach(6);
  Servo_4.attach(7);

  ServoTarget_1.ServoDestination = 110;
  ServoTarget_2.ServoDestination = 90;
  ServoTarget_3.ServoDestination = 90;
  ServoTarget_4.ServoDestination = 90;
}

void UpdateServo(ServoTarget & Motion) {
  // holds positioning of servo through increments of disposition

  int diff = (Motion.ServoDestination - Motion.ServoLocation) / 2;
  Motion.ServoLocation += diff;

  if (0 > Motion.ServoDestination) {
    Motion.ServoDestination = 0;
  }

  if (180 < Motion.ServoDestination) {
    Motion.ServoDestination = 180;
  }

}

void loop() {
  // put your main code here, to run repeatedly:

  int LX = analogRead(A0)/100 - 5;
  int LY = analogRead(A1)/100 - 5;

  int RX = analogRead(A2)/100 - 5;
  int RY = analogRead(A3)/100 - 5;

  ServoTarget_1.ServoDestination += LY;
  ServoTarget_2.ServoDestination += LX;
  ServoTarget_3.ServoDestination += RX;
  ServoTarget_4.ServoDestination += RY;
  delay(25);

  UpdateServo(ServoTarget_1);
  UpdateServo(ServoTarget_2);
  UpdateServo(ServoTarget_3);
  UpdateServo(ServoTarget_4);

  Servo_1.write(ServoTarget_1.ServoLocation);
  Servo_2.write(ServoTarget_2.ServoLocation);
  Servo_3.write(ServoTarget_3.ServoLocation);
  Servo_4.write(ServoTarget_4.ServoLocation);
  
}

# Bill of Materials

| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)
-
