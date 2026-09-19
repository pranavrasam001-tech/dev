# date:17/9
# time spent:1hr
## description:
I have researched the PCB design process and the components needed for the project. I checked datasheets, pin connections, voltage requirements, and suitable footprints for the RP2040, USB-C connector, flash memory, MCP1700 3.3V regulator, capacitors, resistors, switches, and pin headers. This research will help me select the correct components and avoid mistakes during the design.
In the future, I will create the complete schematic in KiCad and connect all components using proper wires and net labels. After checking the schematic, I will assign footprints, move the design to the PCB editor, arrange the components, and route all the connections carefully.

------

# date:18/9
# time spent:1hr
## description:
I have created the initial schematic in KiCad and added the main components, including the RP2040, USB-C receptacle, capacitors, resistors, switches, flash memory, and voltage regulator. I have started wiring the components and using net labels to keep the connections clear and organized. I am also checking the component values and pin connections carefully so that the schematic is correct before moving to the PCB design stage.
<img width="940" height="624" alt="image" src="https://github.com/user-attachments/assets/e66591bf-a5b2-47a4-a092-ab4c1a122fcd" />
<img width="940" height="150" alt="image" src="https://github.com/user-attachments/assets/4f6c5c46-bf4d-4fc7-8e62-f73d2a0d2c7c" />
<img width="251" height="421" alt="image" src="https://github.com/user-attachments/assets/ed9fd2f7-d6cd-460f-90bc-0a3d34b31c48" />
<img width="274" height="502" alt="image" src="https://github.com/user-attachments/assets/6768d877-1e1d-4117-be97-872049b6883d" />

------

# date:18/9
# time spent:1.2hr
## description:
So here I have added the some capacitors and I have connected to the 4 pin with come capacitors and one  flash memory IC (chip), switches , resistors and many more while doing this it was quite difficult as the adding of the net labels was a vey big process to do it as we need to select net label and place where we need and we need change the label. And there were several label to add.!
<img width="706" height="779" alt="image" src="https://github.com/user-attachments/assets/5e047fa3-14c8-4510-a756-6126ae70a498" />
<img width="940" height="554" alt="image" src="https://github.com/user-attachments/assets/823a9d43-ac09-4503-ab76-0e61044c3ee5" />
<img width="940" height="559" alt="image" src="https://github.com/user-attachments/assets/5a0e2e43-fb94-45d5-a4c5-df2b2f15283d" />

------

# date:18/9
# time spent:1hr
## description:
I added the 1×20 and 1×3 pin headers in the circuit design, but connecting all pins was little difficult. Every pin needed correct connection name, and already many connections were there near RP2040. Because of this, sometimes I missed some pins or added wrong connection name. I checked the pin numbers with component details and fixed the errors. Some net labels were same, so I arranged them properly to avoid confusion. After completing this, I checked the schematic again before moving to the PCB layout.
<img width="590" height="646" alt="image" src="https://github.com/user-attachments/assets/3e25e2ea-573c-435d-b508-00e08c298fdd" />
<img width="940" height="625" alt="image" src="https://github.com/user-attachments/assets/4ba614b6-f037-4d5c-840b-2a3caa5bd026" />

------

# date:18/9
# time spent:1hr
## description:
Now it’s the footprints time , as there were many capacitors and the resistor I was need to be done very carefully as there were more number of foot prints , sometimes by mistakenly the other footprint may get added into the other one. And the main is the selection of the footprint was a tougher tasks as we need to do based on the component and value of that. 
<img width="940" height="456" alt="image" src="https://github.com/user-attachments/assets/b8b64357-8a69-43ac-b6ee-f45634fa0a97" />
other components need to usually be found on LCSC and then I have gone into the datasheet to find the footprint, and then added. 
<img width="940" height="483" alt="image" src="https://github.com/user-attachments/assets/fa9736ca-bcd8-471a-96b8-573b074fb966" />

------

# date:18/9
# time spent:2hrs
## description:
so basically I have now converted to the schematics to pcb editor where I have updated the schematics in the pcb editor and started arranging all the components where ever required
<img width="940" height="642" alt="image" src="https://github.com/user-attachments/assets/929f7748-6ae7-40d6-8f04-f8095055e6b3" />
I'm going to switch to the MCP1700 LDO, which is smaller, but does handle less current (250ma). So just replacing the NCP1700 with the MCP1700x-330xxTT, which is the 3.3V MCP1700:
<img width="816" height="571" alt="image" src="https://github.com/user-attachments/assets/93240fc8-698f-4b1d-a264-b80c25cc3854" />
So this is my complete pcb of arranging the components as it was quite difficult to arrange as there were many capacitors in it so I have done it slowly and in more zoom In.
<img width="585" height="831" alt="image" src="https://github.com/user-attachments/assets/e39dce5f-9a3f-44f0-a01c-27dcd95fa360" />
so finally i have doing my pcb where we need to Connected to each and every component this was my toughest task as the routing was not getting possible at all but how much i could, i have done in the routing.
<img width="940" height="485" alt="image" src="https://github.com/user-attachments/assets/0e1b1f20-f81a-45eb-ba96-bd3a7010f8ac" />

