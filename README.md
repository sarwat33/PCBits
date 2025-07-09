# PCBits

Welcome to **PCBits**, a repository where I share my PCB designs, schematics, and Gerber files. Whether you're looking for inspiration or a starting point for your own electronics projects, this repository has something for everyone!

---

## 📂 Repository Contents

1. **PCB Designs**
   - 3D renderings of the designed PCBs.
   - Layout previews of the PCBs with traces and pads.
   
2. **Schematic Diagrams**
   - Easy-to-follow circuit schematics for each design.

3. **Gerber Files**
   - Ready-to-fabricate files for your PCB projects.

---

## 🔧 Featured Designs (All the designs are in order)
### **4) Project: DC-DC Boost Converter -- Converts low voltage DC (3.3V-5V) to upto 33V**

This project is built around the **XL6009 IC** and includes the following features:
- **Voltage Tuning**: A potentiometer has been used to tune the output voltage
- **Max Voltage**: 33Volts

### Key Images

1. **3D PCB View**  
   ![3D PCB View](./assests/3D_Boost_Converter.png)

2. **PCB Layout**  
   ![PCB Layout](./assests/PCB_Boost_Converter.png)

3. **Schematic Diagram**  
   ![Schematic Diagram](./assests/Schematic_Boost_Converter.png)

### **2) Project: Transformerless Power Supply**

This project is built around the *LM7805 voltage regulator,Diodes,Zener Diodes,Capacitors and Resistors and THT components** and includes the following features:
- **LM7805**: Regulates the voltage

### Key Images

1. **3D PCB View**  
   ![3D PCB View](./assests/3D_view_Transformerless_Power_Supply.png)

2. **PCB Layout**  
   ![PCB Layout](./assests/PCB_View_Transformerless_Power_Supply.png)

3. **Schematic Diagram**  
   ![Schematic Diagram](./assests/Schematic_View_Transformerless_Power_Supply.png)



### **3) Project: Digitalite -- Reactive to Light and Sound**

This project is built around the **ATTiny85 microcontroller** and includes the following features:
- **Light Sensing Unit**: Uses an LDR to detect changes in ambient light.
- **Sound Sensing Unit**: Equipped with a microphone for sound detection.
- **Battery Unit**: Powered by a compact coin cell.
- **LED Output**: Displays outputs based on sensor input.

### Key Images

1. **3D PCB View**  
   ![3D PCB View](./assests/3D.png)

2. **PCB Layout**  
   ![PCB Layout](./assests/pcb_layout.png)

3. **Schematic Diagram**  
   ![Schematic Diagram](./assests/schematic_diagram.png)


### **1) Project: Full wave bridge rectifier -- Converts AC to DC output**

This project is built using a Transfomer having two coils,one secondary and one primary coil and includes the following features:
- Capacitor has been added to clear out the ripples and smoothen the pulsating DC waveform in the output.
- Resistor has been used as a load.

### Key Images

1. **3D PCB View**  
   ![3D PCB View](./assests/PCB_3D_view.png)

2. **PCB Layout**  
   ![PCB Layout](./assests/PCB_footprint_view.png)



---

## 🛠️ Tools Used

- **KiCAD** for PCB design and schematic creation.
- **ATTiny85 Microcontroller** for circuit implementation.

---

## 🚀 How to Use

1. **View PCB Designs**:
   - Open the 3D PCB render images to see a visual representation.
   
2. **Modify the Design**:
   - Clone the repository and open the `.kicad_pcb` or `.sch` files in KiCAD.

3. **Fabricate the PCB**:
   - Use the Gerber files in the `/Gerber` directory to order PCBs from your preferred manufacturer.

---

## 📜 License

This project is licensed under the MIT License - feel free to use, modify, and distribute the files.

---

## 🤝 Contributing

Have ideas or improvements for the designs? Feel free to fork the repository and submit a pull request!

---

### 💬 Feedback

If you have any feedback or questions about the designs, please open an issue or reach out directly.

---

Happy PCB designing! 😊
