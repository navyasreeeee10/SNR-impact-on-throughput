# SNR-impact-on-throughput
This project studies how the Signal-to-Noise Ratio (SNR) affects network throughput. Higher SNR gives better data transfer rates. Using the Shannon formula, it shows that improving signal quality boosts communication speed and supports SDG 9 – Industry, Innovation, and Infrastructure.

# 📶 Signal-to-Noise Ratio Impact on Network Throughput

### 🌍 Relevant SDG: **SDG 9 – Industry, Innovation, and Infrastructure**

---

## 🧠 Overview
This project demonstrates how the **Signal-to-Noise Ratio (SNR)** affects **network throughput** using Python.  
Higher SNR values result in improved data transmission rates.  
It uses the **Shannon-Hartley theorem** to calculate theoretical and practical throughput, supporting the goal of **enhancing communication technologies** under **SDG 9**.

---

## ⚙️ Features
- Simulates SNR from **-10 dB to 40 dB**
- Calculates **theoretical capacity** using Shannon’s formula  
- Includes **realistic throughput** (with efficiency factor)  
- Generates a **clear graph** comparing capacity vs actual throughput  
- Highlights how signal quality impacts network performance  

---

## 🧩 Formula Used
\[
C = B \times \log_2(1 + SNR)
\]

Where:  
- **C** = Channel capacity (bits/sec)  
- **B** = Bandwidth (Hz)  
- **SNR** = Signal-to-Noise Ratio (linear scale)

---

## 🖥️ Technologies Used
- **Python 3**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook**

---

## 🚀 How to Run
1. Clone this repository  
   ```bash
   git clone https://github.com/yourusername/snr-network-throughput.git
