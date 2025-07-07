# Firewalker Sneakers
The Firewalker Sneakers project is a creative wearable tech build that turns ordinary shoes into interactive, light-up sneakers. By using pressure-sensitive sensors made from Velostat and conductive thread, the shoes detect each step and trigger colorful LED lights (NeoPixels) controlled by a FLORA microcontroller. When the user walks, the LEDs light up in real-time, creating a "fire-like" glow effect beneath the feet. This project combines electronics, coding, and design, making it a fun and educational way to explore how technology can be embedded into clothing and accessories.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Yuan X | Carlmont high school | Math/Physics | Incoming Senior

![Headstone Image](YuanX.png)
  
# Final Milestone
For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE

# Second Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/BxdtzbBLt2k?si=we1ZCD_3qRk3ke78" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

The second milestone focuses on integrating and testing the lighting system using the NeoPixel strip. To begin, the NeoPixel strip is connected to the Arduino-compatible FLORA board according to the circuit diagram. Once the hardware is wired correctly, the next step is to install the Adafruit NeoPixel library in the Arduino IDE. With the library installed, you can either write or load a basic program that activates the lights when pressure is applied to the sensor embedded in the shoe. This code maps pressure input to visual feedback from the LED strip. Once uploaded to the board, the system is tested by stepping on the sensor to verify that the lights respond appropriately to pressure. This milestone ensures the electrical and software components are communicating correctly and are ready for final integration into the shoe.

# Challenges Faced(Second Milestone)

Library Installation Issues
Installing the Adafruit NeoPixel library in the Arduino IDE can sometimes fail due to version conflicts or missing dependencies.

Incorrect Wiring
Misconnecting the NeoPixel strip to the wrong pins on the FLORA board can prevent the lights from functioning or even damage components.

Power Limitations
NeoPixel strips require sufficient power. Drawing too much current from the USB port may cause flickering, dim lights, or no lights at all.

# First Milestone
For the first milestone of my Firewalker Sneakers project, I focused on building and calibrating the pressure sensors that will detect when I step down. I began by cutting two heel-shaped pieces of Velostat, one for each shoe. Then, I taped loops of conductive thread onto one side of each piece, making sure to leave long thread tails (about 18 inches) for later connection. After flipping the Velostat over, I added a second loop of conductive thread on each, keeping the tails on the same side but spaced at least two inches apart. This creates a sensor that changes resistance when pressure is applied.

Next, I tested the sensors by hooking them up to the FLORA board using alligator clips and uploading sample code to the Arduino IDE. I opened the serial monitor and pressed on the sensor with a blunt object, like a roll of tape, to observe the changing values. This step helped me confirm that the sensor was working and responding to pressure as expected. Completing this milestone was essential because it laid the foundation for detecting foot movement, which will later trigger the LED light effects in the shoes.

# Challenges Faced(First Milestone)

Handling Conductive Thread: The conductive thread was difficult to work with because it frays easily and can tangle while sewing or threading through the Velostat. Making clean, secure connections took time and precision.

Proper Sensor Alignment: Ensuring the two loops of thread were properly aligned on opposite sides of the Velostat without touching each other was tricky. Any overlap could cause a short circuit or incorrect sensor readings.

Securing Components: Taping the thread firmly to the Velostat while maintaining good electrical contact was a challenge. If the thread wasn’t tight or placed correctly, the sensor wouldn’t respond consistently to pressure.

<iframe width="560" height="315" src="https://www.youtube.com/embed/fwhkf0YV6iE?si=URTqbM3EcvMTZX-P" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

# Starter Project - Jitterbug
The first project that I finished at BlueStamp is called Jitterbug. The reason why choose this starter project is because it likes very fun when I was selecting the item. There is only one start botton on the project, and there is string that can make the bug moving once you press the start botton. I successfully finished my start project. however, I still need to be careful which line is positive and which line is negative.

<iframe width="560" height="315" src="https://www.youtube.com/embed/WTMthDaV5aw?si=hRhfK89XkzoWDurS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

# Schematics 
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
```

# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|

# Other Resources/Examples

