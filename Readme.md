# BLUETOOTH-CONTROLLED-GLOVE-WITH-FLEX-SENSOR-

## **Project Overview**

## **Abstract**
This project addresses the communication gap for individuals with hearing or speech impairments by developing a wearable device that translates hand gestures into speech. Using a Bluetooth-controlled glove equipped with a flex sensor, accelerometer, and mobile app, gestures are captured and converted into audible language. This solution provides an assistive technology that promotes inclusivity in social and professional settings, enabling easier communication in various environments, including noisy or quiet spaces.

---

## **Introduction**

### **Background**
Communication barriers for the deaf-mute community are significant due to limited access to sign language interpreters. This project leverages sensor technology and AI to translate gestures into speech, bridging this gap. Existing systems, while accurate, lack real-time translation capabilities, necessitating a cost-effective and practical solution for broader use.

### **Statement of Problem**
The lack of accessible sign language recognition systems forces individuals with hearing or speech impairments to rely on interpreters. This project aims to provide an affordable, independent communication system for the deaf-mute community.

### **Objectives**
- Develop a cost-effective, real-time gesture recognition system.
- Utilize smartphones for easy and portable translation.

---

## **Methodology**

The system is built as a prototype comprising:  
1. **Flex Sensor Integration**: Captures hand gestures.  
2. **Arduino Uno System**: Processes data.  
3. **HC-05 Bluetooth Module**: Sends data to a smartphone.  
4. **Mobile App**: Converts text to speech.

The glove translates analog signals from flex sensors into digital data, processed by Arduino Uno, and transmitted via Bluetooth for translation.

---

## **System Components and Connections**

### **Components Used**
- **Flex Sensor**: Detects bending angles.
- **20kΩ Resistor**: Forms a voltage divider with the flex sensor.  
- **HC-05 Bluetooth Module**: Communicates with the smartphone.  
- **Arduino Uno**: Microcontroller for processing signals.

### **Connections**
- **HC-05 Bluetooth Module**  
  - VCC → Arduino 5V  
  - GND → Arduino GND  
  - RX → Arduino Pin 3  
  - TX → Arduino Pin 2  
- **Flex Sensor**  
  - One end → Arduino 5V  
  - Other end → Analog input via a voltage divider circuit.

### **Apps for Data Transmission**
1. **Serial Bluetooth Terminal**: Receives text data from HC-05.  
2. **Arduino Bluetooth Text-to-Speech Converter**: Converts text to speech.  
3. Alternative Apps:  
   - **Macrodroid**: Text-to-speech translation.  
   - **Bluetooth Serial Monitor**: Receives text data.


---

## **Applications**

1. **Assistive Technology**: Enhances communication for individuals with speech impairments.  
2. **VR/AR Interaction**: Gesture-based control in virtual environments.  
3. **Home Automation**: Operates smart devices through hand gestures.  

---

## **Conclusion**
The Bluetooth-controlled glove with flex sensors offers a cost-effective and innovative solution to bridge communication barriers for the deaf-mute community. Future improvements include enhancing glove sensitivity, adding automatic sign training, and expanding the vocabulary for gesture recognition.

---

