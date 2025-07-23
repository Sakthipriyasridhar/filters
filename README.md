# Mitigation of Harmonics Using Tuned Filters

### 🎓 Final Year Electrical Engineering Skill Project  
**Department of Electrical and Electronics Engineering**  
University College of Engineering, Anna University - BIT Campus, Trichy

---

## 📘 Overview

This project focuses on mitigating power system harmonics using **single tuned** and **double tuned passive filters**. Harmonics, caused by nonlinear loads like thyristor drives and arc furnaces, degrade power quality and damage electrical components. This project designs, simulates, and analyzes tuned filters to suppress such distortions using **MATLAB/Simulink**.

---

## 🎯 Objective

To mitigate current and voltage harmonics in the power system by designing and simulating:

- **Single Tuned Filter**
- **Double Tuned Filter**

---

## 🛠️ Software Used

- MATLAB / Simulink R2017a  
- PowerGUI block (for FFT and impedance analysis)

---

## ⚙️ Key Concepts

- **Harmonics**: Integer multiples of fundamental frequency caused by nonlinear loads.
- **Single Tuned Filter**: Offers low impedance path to a specific harmonic.
- **Double Tuned Filter**: Targets two harmonic frequencies using a single configuration.

---

## 📐 Technical Details

- Fundamental frequency: 50 Hz  
- Filters designed for 11th and 13th harmonic mitigation  
- Parameters derived from:  
  - Capacitive Reactance (Xc)  
  - Inductive Reactance (Xl)  
  - Quality Factor (Q)  
  - Short Circuit Capacity (Scc)  
- Effective impedance and filter MVAR rating calculated  
- Filters modeled using mathematical equations and validated in simulation

---

## 📊 Simulations

### 1️⃣ Without Filter
- Simulink model of a nonlinear load connected to the grid.
- FFT shows presence of dominant harmonic frequencies.
### 🔌 1. Grid Without Filter
![Grid Without Filter](images/grid_without_filter.jpg)

### 2️⃣ With Single Tuned Filter
- Reduced specific harmonic (e.g. 11th).
- Impedance and FFT plots confirm harmonic suppression.
### 🔁 2. With Single Tuned Filter
![Single Tuned Filter](images/single_tuned_filter.jpg)

### 3️⃣ With Double Tuned Filter
- Suppresses both 11th and 13th harmonics efficiently.
- FFT shows significant harmonic reduction and improved waveform.
### 🎯 3. With Double Tuned Filter
![Double Tuned Filter](images/double_tuned_filter.jpg)

---

## 📈 Results

- Simulation and theoretical values closely matched.
- Double tuned filters provided better performance than single tuned ones.
- Harmonic content was significantly reduced in both current and voltage waveforms.

---

**Project Guide**: Dr. P. Anbalagan

---

## 📄 License

This project is for academic purposes and is open for reference and learning.  
Feel free to use with proper credit to the authors.

---



## 🧪 How to Run

1. Open MATLAB R2017a
2. Load the Simulink models:
   - `grid_without_filter.slx`
   - `single_tuned_filter.slx`
   - `double_tuned_filter.slx`
3. Run simulation and open PowerGUI block.
4. Use FFT Analysis to observe harmonic mitigation.

---

## 💬 Feedback

For queries or suggestions, open an issue or contact any of the contributors.

