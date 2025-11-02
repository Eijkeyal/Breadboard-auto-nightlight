# Automatic Night Light Circuit

## Project Overview
This is a hands-on breadboard implementation of an automatic light sensor circuit that activates an LED when darkness is detected.

## Components Used
- **LDR** (Light Dependent Resistor) - Light sensor
- **NPN Transistor** (BC547/2N2222) - Electronic switch
- **Resistors** - 10kΩ (for LDR) & 330Ω (for LED)
- **LED** - Light output
- **9V Battery** - Power source
- **Breadboard** - Prototyping platform
- **Jumper Wires** - Connections

## 🔌 Breadboard Implementation
Since this is a practical breadboard project without a formal schematic, here's the connection guide:

### Connection Layout:
1. **LDR Circuit**: Connect LDR in series with 10kΩ resistor across 9V
2. **Transistor Base**: Connect between LDR and 10kΩ resistor
3. **LED Circuit**: Connect LED with 330Ω resistor to transistor collector
4. **Power**: 9V battery connected to breadboard power rails


## 📸 Visual Documentation
*(Include your video and photos here)*


## Applications
- Automatic street lights
- Night lamps
- Security systems
- Energy-saving systems

## 🎯 How It Works
- **Bright Light**: LDR resistance low → transistor stays OFF → LED OFF
- **Darkness**: LDR resistance high → transistor turns ON → LED lights up

