# Pinguino-UNO-Rev2-SMD
Development Board based on the PIC18F2550, programmable in Arduino language. Use the Pinguino IDE, open source and open hardware project.

# Main Features
- Open Source
- Programing by Pinguino IDE
- Works with the same Arduino Language
- 17 digital pins / 5 analog pins / 2 PWM pins
- Same dimensiones than the Arduino UNO
- Same pin distribution (digital and analog) than the Arduino UNO
- Led SMD test inboard
- We can supply the board with USB or External power supply from 9-12V

# Basic Pinguino Schematic Circuit
In the bellow picture We can see the minimal connections necesary to made our board work, according to it, We can made changes and build your own board for specific projects.

# Pinguino UNO Pic 18F2550 Schematic
Schematic Diagrama Pinguino based on Pic18f2550
For the External Supply from 9-12V, the board use the chip 1117 -5V and 1117-3.3V, with the DC Jack conector we can power on easily our projects.
The gerber files are atteched in this post, and you can made and build your own Pinguino UNO, in this case We manufactured the board with JLCPCB which offers very quality pcbs. You can access by this link https://jlcpcb.com/IAT

# PCB LAYOUT
Before We continue with the PCB layout, it is important to indicate that You can use any software for PCB Desing, believe me there are many options, even if you use the best software it will not mean that you are the best pcb desinger, so in this case We are going to use The Altium Designer highly recommended if you want to enter in the pcb design world like a professional.
So after We finished and check our schematic circuit We need to switch from schematic to PCB layout. We can see the PCB with the Ground Plane, this helps for noise filter on the pcb. Also is important to remember that in the case of the microcontroller is necesary to place the crystal and the capacitor the closest possible.

Here after we finish the pcb layout We can get the Gerber files, there are two kind of gerber files we have to pay attention to it, the first GerberX2 and the other Gerber RS274X, most of the manufacturer use the second one Gerber RS274X, in some software we will just GerberX2 and Gerber (In the case of Altium Designer).
There are two kind of gerber files we have to pay attention to it, the first isGerberX2 and the other Gerber RS274X, most of the manufacturer use the second one Gerber RS274X

# 3D MODEL
One of the features of Altium Designer is the 3D visualization, the 3d visualization is important and it give us the posibility to see and check our PCB and how it would be in real, also it can show us the components distribution and dimensions. Before I did not consider this feature so important, but the 3d visualization can show us if our footprint dimensions are ok, if all the components will be places without touching each other by mistake.

► Also very important to remember, if you are going to add 3d models, be carefull that you add in the Step AP214 format, the others extensions and formats can not work correctly.
The 3d visualization can show us if our footprint dimensions are ok, if all the components will be places without touching each other by mistake.

# PDF 3D
According to the software that you are using, You can also get the 3d Models, as I commented you before, this board was desinged On the Altium Designer Software who has this nice option to get the 3d pdf, so later you can share with your coworkers or clients to show the advances of the pcb, without the software installed.

# PCB MANUFACTURE
Once we finished our development board; it is time to bring it to life. In order to manufacture our board, We are going to use JLCPB Services.In case that you do not have an account yet, check out the bellow link►JLCPCB: https://jlcpcb.com/IAT
Let's bring our Pcb to life with JLCPCB manufacturer

How to Order our PCB in JLCPCB ?
Once We are register, and We logged in our account, We are ready to submit an order and receive our board in a very short time. In this case We need to update first the gerber files, which contains all the necesary information to build the pcb, You can get the gerber files in the link bellow.
►Gerber Files:
Upload your gerber files

Indicate the features
After the upload of our gerber files, We need to indicate the features of the board, in the next picture you can see the options available.

Add your shipping address
This part is very important, here you should write your currently address, where you would like to receive your pcb prototypes. It is not common but sometimes very rarely, you will need to pay extra feeds, but as I told you, it is very rarely.

Make the payment and finish the order
After you indicates this information, We continue with the payment section, These is the section where you can apply your coupons or discount codes. Basically We can complete the paymente by two general ways, Paypal or Credit card.

Receive your PCB
Days later, 7 days or few more, according to your location and custom broker process, You will receive your pcb prototypes.

# Why JCLPCB?
JLCPCB has been at the fore front of the PCB industry. With over 14-year continuous innovation and improvement based on customers' need, we have been growing fast, and becoming a leading global PCB manufacturer, who provides the rapid production of high-reliability and cost-effective PCBs and creates the best customer experience in the industry.In case that you do not have an account yet, check out the bellow link►JLCPCB: https://jlcpcb.com/IAT

- Most Efficient, Economic, Innovative PCB Solutions
- Higher Quality
- Lower Cost
- Faster Delivery
JLCPCB provides a rapid production of high-reliability and cost-effective PCBs and create the best customer experience in the indrustry.

# Building the Pinguino UNO
In this post you will find the components necesary to build the pinguino Board and also the components are very easy to get. Common components that we regulary use for electronics projects.

#  Programing the board
In order to program the board We need to donwload the Pinguino IDE, open source platform which uses the same language than the Arduino. You can download here: https://pinguino.cc/

The Pinguino IDE works with textual programing and also Block programing.IMPORTANT. When you conect the board you have some seconds to upload your program after that You need to press reset boton to load the program again. Once your program is uploaded it will automatically reset and ejecute the program.

# THANKS
Thank to:

►JLCPCB: https://jlcpcb.com/IAT


