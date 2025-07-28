# 🔊 VU Meter Project — Sound Level Display using LM3915 (No Microcontroller)

This project presents an analog **VU (Volume Unit) Meter** circuit that visually represents sound levels using an LED bar display. Designed without any microcontroller, it operates entirely with analog components — primarily the **LM3915 integrated circuit** — making it ideal for foundational learning in electronics and signal processing.

---

## 📘 Project Summary

The circuit uses a **microphone** to detect ambient sound and convert it into an electrical signal. This signal is filtered and amplified, then passed into the **LM3915**, which drives a set of **10 LEDs** to indicate the loudness of the sound. The louder the sound, the more LEDs light up, providing a simple and intuitive volume visualization.

---

## 🧩 Components Used

| Component              | Specification / Quantity       |
|------------------------|-------------------------------|
| Microphone             | Electret-type                  |
| LM3915 IC              | 1                              |
| Capacitors             | 10µF, 0.1µF                    |
| Resistors              | 33kΩ, 470kΩ, 1MΩ, 10kΩ         |
| LED Bar                | 10 LEDs (LED1 to LED10)        |

---

## ⚙️ How It Works

1. **Microphone** captures sound waves and converts them into weak analog signals.
2. **Capacitors** remove high-frequency noise from the signal.
3. **Resistors** set the gain and reference voltages for proper signal scaling.
4. **LM3915** acts as the heart of the system:
   - Amplifies the microphone input
   - Compares signal strength against preset thresholds
   - Activates output pins connected to LEDs accordingly
5. **LED Display**: LEDs light up progressively to reflect the intensity of the detected sound.

---

## 🖼️ Circuit Diagram

Please refer to the attached PDF file `Sound_Sensor_Project.pdf` for:
- Detailed circuit schematic
- Component arrangement
- Functional explanation

---

## 🎓 Project Team

This project was completed as part of the Digital Electronics Lab coursework at **Helwan National University, Faculty of Engineering**, under the supervision of **Dr. Mostafa Mahmoud**.

**Team Members:**
- أحمد محمد أحمد فؤاد المنيلاوي  
- احمد رضا كامل عبد الغني  
- إسراء حمدي سيد عبد المسلا  
- ايه حمادة فرج
- احمد سعيد محمد إمام زايد  

---

## 📬 Contact

For academic collaboration or technical discussion, please reach out to:

**Ahmed El-Manylawi**  
📧 ahmed.elmanylawi@gmail.com  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/ahmed-el-manylawi-67b6162aa)

---

> 📎 *This project is shared strictly for academic and educational reference.*
