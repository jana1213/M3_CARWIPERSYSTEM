
# INTRODUCTION
Wiper is a fundamental part that is utilized to clear raindrops or any water off of the windscreen. Wipers are planned and made to clean the water off of a windscreen. Most vehicles have two wipers on the windscreen, one on the back window and the other on every fog light. The wiper parts apparent from outside the vehicle are the elastic cutting edge, the wiper arm holding the edge, a spring linkage, and portions of the wiper turns. The actual wiper has around six sections called pressure focuses or hooks that are little arms under the wiper



The current framework utilizes a control tail to initiate the wiper and the most common way of pulling up the wiper is difficult.r needs to turn on and off the control tail and it will diminish the driver's fixation during the driving. Consequently, this framework is proposed to tackle this large number of issues. The idea of this wiper framework is like other regular wipers, yet this framework will be moved up to a programmed control framework by utilizing a controller.When water hits a devoted sensor situated on the windscreen, it sets off the wiper engine to move. isn't distinguished by sensor, the wiper will consequently stop. This will assist the driver with giving more focus and lessen the auto crash likelihood.


In this project, there were two developments audited as the writing survey. The two were planned with various ideas and working component anyway with same target of working standard of the vehicle wiper. The downpour sensor was an exceptionally adaptable gadget for programmed cleaning of vehicle windscreen when it is wet because of dampness, raindrops or even mud. It worked by mirroring amicable light bars inside the windscreen. Whenever raindrops fall onto the windscreen, this agreement light is upset and making a drop in the light shaft force. The framework then initiated the wipers to be worked in full programmed mode. It makes some reaction memories of 0.1 seconds. It took into account a speedy response when an abrupt sprinkles of water will make the driver absolutely 'blinds' when the circumstance occurred. With the programmed wiper, the driver can turn away the gamble of a mishap. The programmed wiper is significant during weighty traffic, for example around, city, school zone and other public spots. A driver might be exposed to numerous interruptions with awful climate, risky street conditions and weakness. The Rain Sensor diminished the driver's weight by making driving more agreeable. Following a wet vehicle is as of now not a disturbance as identification of even 0.005 milliliters of water is conceivable.





# COMPONENTS AND SUPPLIES:
* STM32F407 Discovery Board
* Push Button
* LEDs
* Resistors
* Power Supply
# DIAGRAMS
# BLOCK DIAGRAM
![BLOCK DIAGRAM (1)](https://user-images.githubusercontent.com/101693748/168218197-b54a3395-2235-4baf-9c88-88014a2f8e84.png)

# FLOW CHART
![FLOWCHART 1](https://user-images.githubusercontent.com/101693748/168218223-8fabd5df-2dd2-45e2-b538-14d39aa0b479.png)

# SCHEMATIC DIAGRAM
![o1](https://user-images.githubusercontent.com/101693748/168218142-2fe98ed9-a209-4431-a7f9-d068d950e92a.png)


# ADVANTAGES:
* To save money during wet seasons, turn off the irrigation system. Electricity bills are lowered as a consequence.
* Rain sensors store water during rain events, allowing it to be available throughout the summer and winter.
* As a consequence, rain sensor-based equipment like vehicle wipers and irrigation systems last longer since they only work when needed.
* It is quite simple to use.
* As a consequence, less energy is consumed.
* Rain sensor-based systems are extremely simple to install.
* Individual rain sensors are fairly inexpensive.
# Disadvantages:
* When water falls squarely on the rain sensor, the mechanism activates.
* The entire system cost rises when more components, including a rain sensor, are required.
* Rain sensors must make a decision within a few minutes to avoid erroneous detection of rain.
# 4W & H (WHO,WHAT,WHEN,WHERE,HOW)
# WHAT
* The operational speed of a vehicle wiper is controlled by a wiper speed control mechanism based on rain conditions. To generate, the control system incorporates a rain sensor (30) that detects rain conditions. The amplitude of an analogue signal depends on the detected rain conditions.

# WHY
* To keep the windscreen clean enough to give adequate view at all times. #WHEN
* The windshield wipers remove rain and snow from the windshield, while the headlights improve visibility at night.
# WHO
* A wiper speed control system for an automobile manages the wiper's functioning speed in response to weather conditions.
# HOW
* You can adjust the speed of the car wiper system according to the rainfall
# WHERE
* In general, car wipers are controlled by the stalk on the right side of the steering wheel.
# REQUIREMENTS
# HIGH LEVEL REQUIREMENTS
![hl](https://user-images.githubusercontent.com/101693748/168130086-6532f411-0c49-4834-8c8b-a0df39bc2d75.png)

# LOW LEVEL REQUIREMENTS
![ll](https://user-images.githubusercontent.com/101693748/168130124-dbe5007f-5c86-42ae-85de-574e544d8598.png)


# TESTCASES
# HIGH LLEVEL
![tchl](https://user-images.githubusercontent.com/101693748/168130149-18c817a7-7e72-4d11-8ea7-9737cb642682.png)

# LOW LEVEL
![tcll](https://user-images.githubusercontent.com/101693748/168130172-4243a291-c3ad-4106-b8c5-f6711cdf19d8.png)

# SWOT ANALYSIS
# STRENGTH
* Low Budget
* Good Reputation
* High Bargaining Power Supliers
* Big Influence on the Market
# WEAKNESS
* Structural Inertia
* High Transaction Cost
* No Focus on Private Sector
* Week Focus on Process Innovations
# OPPRONUTIES
* Emerging New Markets
* Technological Development
* Demand for Saver Equipments
* Technological Lock in of Product
# THREATS
* Low Bargaining Power Buyers
* Highly REgulated Industry
* Ethical Pressure
* Econimical Crisis
# Exploring STM32F407 Discovery Board
![o1](https://user-images.githubusercontent.com/101693748/168216680-be54d6cb-dd55-4f3e-8556-9cb9b45c041d.png)
* Hardware Used : STM32F4 DISCOVERY kit, for more information visit: STM32F4 DISCOVERY
* Software Tool : STM32cubeIDE, for more information visit: STM32CubeIDE
* For installation of STM32CubeIDE refer Youtube
* Note : As this microcontroller has many advanced features and the main aim of this project is to get all basic insights, during the driver development only the required functionalities are added and other advanced functionality is not added. I may update the driver and other functionality in the future.
# Overview of STM32F407VGT6 Microcontroller
![o2](https://user-images.githubusercontent.com/101693748/168216817-b997a145-94bf-4212-884d-fee39f7eebae.png)
* The STM32F407 Discovery board utilizes STM32F407VGT6 Microcontroller which has ARM Cortex-M4F Processor, which is equipped for running upto 168Mhz. This MCU has numerous peripherals, for example, GPIO ports, TIMERS, ADCs, DACs, Flash Memory, SRAM, SPI, UART ect. The processor and peripherals talk through BUS-Interface. There are three transports accessible
* I-BUS (Instruction Bus) D-BUS (Data Bus) S-BUS (System Bus) I-BUS This transport interfaces the Instruction transport of the Cortex®-M4 with FPU(Floating point unit) center to the BusMatrix. This transport is utilized by the center to bring guidelines. The objective of this transport is a memory containing code (interior Flash memory/SRAM or outside recollections through the FSMC/FMC).
* D-BUS This transport associates the databus of the Cortex®-M4 with FPU to the 64-Kbyte CCM information RAM to the BusMatrix. This transport is utilized by the center for strict burden and troubleshoot access. The objective of this transport is a memory containing code or information (inner Flash memory or outside recollections through the FSMC/FMC).
* S-BUS This transport associates the framework transport of the Cortex®-M4 with FPU center to a BusMatrix. This transport is utilized to get to information situated in a fringe or in SRAM. Guidelines may likewise be gotten on this transport (less proficient than ICode). The objectives of this transport are the inward SRAM1, SRAM2 and SRAM3, the AHB1 peripherals including the APB peripherals, the AHB2 peripherals and the outside recollections through the FSMC/FMC.
* So guidelines and information use I-transport and D-transport separately, All the other fringe utilizes System transport. The Cortex-M4 processor contains three outside Advanced High-execution Bus (AHB)- Lite transport connection point and one Advanced Peripheral Bus (APB) interface. The GPIOs are associated with AHB1 transport which has a greatest speed of 150Mhz and is isolated into two transports as APB1 and APB2. APB1 runs at 42Mhz(max) and APB2 runs at 82Mhz(max). The various peripherals like SPI, UART, TIMERs, ADCs, DACs, and so forth are associated with either APB1/APB2 transports. What's more, the AHB2(168Mhz max) is associated with Camera and USB OTG interfaces, AHB3 is associated with External memory regulator.


# outputs
1.user button and hold it for two seconds
![o3](https://user-images.githubusercontent.com/101693748/168217417-1b284083-4926-4428-83ec-35616e8d45ec.png)
2.wiper speed low
![o4](https://user-images.githubusercontent.com/101693748/168217589-8b77bc5a-997d-4c3d-aa89-dcd0a2f80ef6.png)
3.wiper speed medium
![o5](https://user-images.githubusercontent.com/101693748/168217740-451f1216-3e25-4335-938b-f9a6a455ff1d.png)
4.wiper speed is high
![o6](https://user-images.githubusercontent.com/101693748/168217822-8ac362b4-4ec6-4ca6-b2d4-7860e1c78dfc.png)
5. user button is pressed and hold for 2 seconds, the red LED is off
![o7](https://user-images.githubusercontent.com/101693748/168217926-4030e98c-423c-4c11-982a-e6d0d3b361ed.png)





