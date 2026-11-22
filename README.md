# 📡 AM Demodulator Design using Analog Circuits

## 📌 Overview
This project focuses on the design and implementation of an **Amplitude Modulation (AM) demodulator** for a **10 kHz carrier signal** with an input amplitude range of **50 mV to 1 V**.

The system successfully recovers the original message signal using analog signal processing techniques.

---

## 🎯 Objectives
- Generate AM signal using transistor-based modulation
- Design a complete AM demodulator circuit
- Extract message signal using envelope detection
- Amplify recovered signal for analysis

---

## ⚙️ System Design

### 🔊 1. Modulation Stage
- Carrier: 10 kHz sine wave  
- Message: 1 kHz sine wave  
- Transistor (BC547) used for modulation  

---

### 🔌 2. Buffer Stage
- Op-amp (TL064) used as voltage follower  
- Prevents loading and distortion  

---

### ⚡ 3. Precision Rectifier
- Eliminates diode threshold loss  
- Enables accurate detection of low amplitude signals  

---

### 📉 4. Envelope Detector
- Extracts message signal from AM waveform  
- Uses diode + RC circuit  

---

### 🔧 5. High Pass Filter
- Removes DC component  
- Retains AC message signal  

---

### 🔊 6. Amplifier Stage
- Non-inverting amplifier  
- Gain = 1.5  

---

## 🧠 Concepts Used
- Amplitude Modulation (AM)
- Envelope Detection
- Analog Signal Processing
- Filters (RC)
- Op-Amp Circuits

---

## 📊 Results
- Successfully recovered 1 kHz signal from 10 kHz carrier  
- Minor distortion due to practical limitations  
- Output closely matches original message signal  

---

## ⚠️ Observations
- Slight amplitude variation observed  
- Distortion due to:
  - Component tolerances  
  - Non-ideal diode behavior  
  - Op-amp limitations  

---

## 🔮 Future Improvements
- Use precision IC-based demodulators  
- Improve filter design  
- Reduce distortion using better components  

---

## 📷 Output
(All waveform images attached)

---

## 📄 Documentation
Full report available in `/docs`

---

## 👨‍💻 Author
**Guruvisvesh S A**
