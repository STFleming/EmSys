![](imgs/EmSysLogo.svg)
## Welcome to EmSys Autumn 2021 CSC368/M68
Welcome to the Swansea University EmSys (Embedded Systems) module. 
This repository contains various useful bits and pieces for the course, such as a schedule, datasheets, and various other things.
For this course, I will primarily use GitHub to host lecture and lab content. Below is a table detailing the lecture and labs' timing, along with links to the relevant GitHub page. Most of the repositories are currently private but will be made public before the appropriate lab/lecture. 

### Lab and Coursework Breakdown
|            | Lab description                                                                | Assessment type   | Overall weighting | Pairs/Individual |
|------------|--------------------------------------------------------------------------------|-------------------|-------------------|------------------|
| Lab 1      | TinyPico Introduction; DotDevice                                               | Signoff           | 5%                | Lab pairs        |
| Lab 2      | GPIO deep dive; Describing basic circuits with Verilog                         | Signoff           | 5%                | Lab pairs        |
| Lab 3      | Designing a communication protocol                                             | Individual report | 15%               | Lab pairs        |
| Lab 4      | Describing Sequential Logic                                                    | Signoff           | 5%                | Lab pairs        |
| Lab 5      | Configuring a PWM peripheral; Designing a PWM hardware peripheral from scratch | Signoff           | 5%                | Lab pairs        |
| Lab 6      | IoT sensor node design focussing on power consumption                          | Individual report | 15%               | Lab pairs        |
| Coursework | Developing dotDevice hardware                                                  | Individual report | 50%               | Individual       |

* All the lab work is completed in pairs. Pairing will be determined at the start of term.
* A "Signoff" assessment type means that at the end of the lab a demonstrator will check your lab pairs work, provide feedback, and sign it off to get the marks for that lab. 
* An "Individual report" assessment type means that each student will need to submit an individual report for marking, where feedback is returned within 2 weeks. 

### Useful links
* Setting up your EmSys lab environment [[here](https://github.com/STFleming/EmSys_labSetup)]
* Latest virtual lab url [[here](http://ec2-52-15-138-171.us-east-2.compute.amazonaws.com:4000/)]

-----------------------------------------------------------------------------------
### Lecture Schedule and Course Content
| Week  | dates       | Lecture 			                                                          | 				                                                                                     | 
|-------|-------------|-------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|
| 1     |   |  -                               |                                                 |
| 2     |   | [Introduction & Course Overview]()                              |                                                 |
| 3     |   | [Memory Mapped I/O, C Pointers, Bit Manipulation, Verilog Intro]()                              |                                                 |
| 4     |   | [Communications]()                              |                                                 |
| 5     |   | [Verilog: Sequential Logic & State]()                              |                                                 |
| 6     |   | [Digitial-to-Analog conversion, HW Timers, and PWM modules]()                              |                                                 |
| 7     |   | [Interrupts and Power Consumption]()                              |                                                 |
| 8     |   | [Coursework Overview]()                              |                                                 |
| 9     |   | [Worst Case Execution Time]()                              |                                                 |
| 10    |   | [Real Time Operating Systems]()                              |                                                 |
| 11    |   | [FPGA Devices]()                              |                                                 |


### Lecture Recordings
| Week  | dates       |  Recording                                                                                |
|-------|-------------|-------------------------------------------------------------------------------------------|
| 1     |             |                                                                                           |          


-----------------------------------------------------------------------------------
### Datasheets & Technical Reference Manuals
| Device                       | Datasheet/Technical Reference Manual                                                                                                               |
|------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------|
| ![](imgs/tp_small.jpg)       | [TinyPico-01](https://www.tinypico.com/ )                                                                                                                                   |
| ![](imgs/esp32_small.jpg)    | [ESP32 Technical Reference Manual](https://www.espressif.com/sites/default/files/documentation/esp32_technical_reference_manual_en.pdf)            |
| ![](imgs/logic_analyser_small.jpg) | [Logic Analyser](https://cdn.shopify.com/s/files/1/1509/1638/files/Logic_Analyzer_Datasheet_e6569a64-4910-4661-9ef3-f431019ab753.pdf?v=1610445451) |
| ![](imgs/currentRanger_small.jpg) | [Low Power Current Amplifier](https://lowpowerlab.com/guide/currentranger/specs-architecture/) |

### TinyPico Pinout
![](imgs/tinypico-specs-v2.jpg)

-----------------------------------------------------------------------------------

### Software & Libraries
|  Software   |   Information / Resources  |
|-------------|----------------------------|
| ![](imgs/arduino_small.png) | [Basic Info](https://www.arduino.cc/en/Tutorial/BuiltInExamples) |
| ![](imgs/sigrok_small.png) | [PulseView Logic Analyser gui](https://sigrok.org/wiki/PulseView) |
| ![](imgs/circuitjs_small.gif)    | [CircuitJs Web simulator](https://www.falstad.com/circuit/circuitjs.html) |
| ![](imgs/github_small.png)    |  [ArduinoWebsockets](https://github.com/gilmaimon/ArduinoWebsockets) |
