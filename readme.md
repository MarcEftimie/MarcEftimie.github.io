# Projects

This page includes only a fraction of projects that I've completed throughout my time at Olin College of Engineering. Hope you enjoy!

## Pipelined RISC-V CPU

I designed a pipelined RISC-V CPU in System Verilog for my computer architecture class final project. This processor supports almost all I, S, R, B, and J instructions for the RV32I instruction set. Down below, you can explore the repository that includes all of the code for this project!
<br>
[Pipelined RISC-V CPU Repository](https://github.com/MarcEftimie/Pipelined_RISC-V_CPU)
<br><br>
Before getting into any System Verilog, I always draw sketches to validate my understanding of digital systems. Usually, I'll start with general block diagrams and then add details (mostly muxs in this case) as I go. Here are one of those sketches.
![Pipelined RISC-V CPU Sketch](pipelined-cpu-sketch.png)
<br><br>

## Analog Circuitry

If I have any spare time from classes, I usually use it by tinkering with personal projects relating to analog circuitry. Of the projects that I've documented, I've compiled a few here to share.
<br>

### Independent Study Spring 2022 (WIP)

Currently, I'm working with a colleague of mine to explore the advantages of computing particular computations using analog devices. Our early stages consisted of deciding which computations we wanted to tackle first before moving on to more complex ones. With the growing need of neural networks, we decided to design an analog circuit specifically for matrix multiplication which is a common computation done in AI training. As of now, we are exploring different means of analog signals together; some include log anti-log op amp configurations and a four quadrant multiplier, the gilbert cell.

### Blood / Heart Related Sensing

Since my school had extra stock of blood / heart sensors, I decided to design circuits to filter out the desired signals. These more practical projects helped me better understand many analog topics including RC filters, op amps, bode plots, reactance, etc.
<br>
<br>

### Electrocardiogram (EKG):

EKG's essentially measure the voltage across certain parts of your body which makes them a great way to measure a pulse.
<br>
![EKG](ekg.png)
<br><br>

### Pulse Oximeter:

Pulse Oximeter sensors output a voltage depending on the light that shines through your finger; they're used for measuring blood oxidation.
<br>
![Pulse Oximeter](pulse-oximeter.png)
<br>
![Pulse Oximeter Circuit](pulse-oximeter-circuit.png)
<br><br>

### Ballistocardiogram:

By using a scale as my sensor, I made a circuit that can measure someone's pulse just by having them stand on it. This is because your heart applies a small (but detectable) downwards pressure when it pumps.
<br>
![Ballistocardiogram](ballistocardiogram.png)
<br>
![Ballistocardiogram Circuit](ballistocardiogram-circuit.png)
<br><br>

## FlyGloveFly

During fall 2022, I teamed up with four other students to build a drone that can be controlled with a glove in a 5 weeks time. The idea is that the wearer of the glove can control the drone using different hand gestures. For this project, I was responsible for the electrical and firmware for the glove and drone. We have a website fully dedicated to the development and testing of this drone which I'll link here.
<br>
https://olincollege.github.io/pie-2022-03/fly-glove-fly/

### Drone Electrical System

![Drone Circuit](drone-circuit.png)
<br>
![Drone](drone.png)

## Solid Rocket Engine

This year I had the opportunity to lead the Olin Rocketry Engine sub-team. My team is responsible for developing Olin Rocketry's proprietary propulsion system; this includes designing each part that goes into a solid rocket engine, making our own fuel, and settings up testing rigs to gather data from test launches. In a few weeks, my team has designed a completely new engine casing along with integrating new pressure and force transducers compared to last year's design. Currently, we are in the process of machining parts to get ready for a test launch happening in January.
<br><br>

### The Phobos V3 Engine:

![Phobos V3 Engine](engine-cad.png)
<br><br>

### Test Launch Stand:

![Test Stand](test-stand.png)
<br><br>
