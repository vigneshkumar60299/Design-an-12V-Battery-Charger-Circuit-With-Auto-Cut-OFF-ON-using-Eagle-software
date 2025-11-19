# Exp 3: Design an 12V Battery Charger Circuit With Auto Cut OFF & ON circuit using Eagle software
# AIM:
To design an schematic,layout diagram and generate gerber file for a 12V Battery Charger Circuit With Auto Cut OFF & ON circuit using Eagle software.
# EQUIPMENT REQUIRED:
● Hardware: Personal Computer (PC)<br>
● Software: Eagle <br>
# PROCEDURE:
Create a New Project:<br>
o Launch EAGLE and start a new project for your PCB design.<br>
o Within the project, create a new schematic file.<br>
Add Components:<br>
o Utilize the built-in libraries in EAGLE or create custom libraries if needed.<br>
o Use the 'Add' tool to place the required components onto the schematic sheet.<br>
Make Connections:<br>
o Connect the components using the 'Net' tool.<br>
o Label the nets clearly to maintain clarity and organization in your design.<br>
Check for Errors:<br>
o Once the schematic design is complete, perform an Electrical Rule Check (ERC) to identify and correct any errors.<br>
o Save the schematic after confirming that no errors are present.<br>
Switch to Board Layout:<br>
o Click on the 'Generate/Switch to Board' button to create the PCB layout from the schematic.<br>
Arrange Components and Route Traces:<br>
o In the board layout editor, arrange the components to optimize space and reduce signal interference.<br>
o Use the 'Route' tool to connect the components based on the schematic design.<br>
o Ensure proper routing by utilizing the available editing tools in EAGLE to avoid design rule violations.<br>
Design Rule Check (DRC):<br>
o Perform a Design Rule Check (DRC) to ensure that the routing and layout comply with design standards and that there are no issues.
o Save the board layout after resolving any errors.<br>
Generate Gerber Files:<br>
o Go to File > CAM Processor and configure the CAM jobs to generate Gerber files for all PCB layers, such as copper layers, silkscreen, solder mask, and drill files.<br>
o Verify the generated files to ensure they contain all necessary information for manufacturing.<br>
Save Manufacturing Files:<br>
o Save the Gerber files and any other required manufacturing files to send to your PCB manufacturer for fabrication.<br>
# THEORY:

A 12V Battery Charger Circuit with Auto Cut-Off and On is a smart charging system designed to automatically stop charging once the battery reaches its full voltage level and restart when the voltage drops below a set threshold. This type of circuit ensures safe, efficient, and long battery life by preventing overcharging and deep discharging.
Such circuits are commonly used for lead-acid batteries, UPS batteries, emergency lights, and automotive batteries. The charger is compact, reliable, and can be implemented easily on a single-side or double-side PCB.

<img width="743" height="305" alt="image" src="https://github.com/user-attachments/assets/2dbc8aa2-e368-4eb0-9a6a-dddb66a54963" />

## Working:

The **12V battery charger circuit with auto cut-off and on** works by continuously monitoring the battery voltage and controlling the charging process using a voltage comparator and a relay switch. When the circuit is powered, the relay initially connects the charger output to the battery, allowing current to flow and begin charging. As the battery voltage gradually increases, the voltage sensing section—typically built using an operational amplifier (like LM324 or LM358)—compares the battery voltage with a preset reference voltage. Once the battery voltage reaches the full-charge level, usually around **14.4V**, the comparator changes its output state, de-energizing the relay coil. This action disconnects the charger from the battery, effectively stopping the charging process and preventing overcharging. When the battery is used and its voltage drops below a preset lower threshold (around **11.8V–12V**), the comparator again switches its state, re-energizing the relay and reconnecting the charger to the battery. Thus, the circuit automatically restarts charging without any manual intervention. The system may include **LED indicators** to show charging and full-charge status, making it user-friendly. This automatic operation ensures safe charging, longer battery life, and reliable performance for various 12V battery applications.

<img width="382" height="318" alt="image" src="https://github.com/user-attachments/assets/0abf47c4-6ae1-4247-8c1a-09f1546ef0ef" />

# CIRCUIT DIAGRAM:
## Schematic diagram
<img width="1920" height="1080" alt="3-sc" src="https://github.com/user-attachments/assets/35e9744b-dea7-42e7-ac04-a37b315d720f" />

## Layout diagram
<img width="1920" height="1080" alt="3-ly" src="https://github.com/user-attachments/assets/2b83a4ee-6584-417f-a317-44d4f4fd8654" />

# RESULT:
Thus, the schematic,layout diagram and generate gerber file for a 12V Battery Charger Circuit With Auto Cut OFF & ON circuit has been successfully designed using Eagle software.

