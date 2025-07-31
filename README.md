
# 🛰️ Satellite Orbit Simulation in 3D Space

**Author:** Farzaneh Naderi  
**Student ID:** 810301115  
**Course:** GPS — Practice 1  
**Instructor:** Dr. Saeed Farzaneh  

---

## 📘 Overview

This project simulates the **3D orbital motion of a satellite** around Earth using Newtonian gravitational dynamics.  
The numerical integration of motion equations is performed with the **RK45 method** (`solve_ivp` from SciPy), and visualizations are generated using `matplotlib`.

📌 The simulation provides:
- Full 3D orbit visualization
- Altitude analysis over time
- Calculation of **apogee** and **perigee** altitudes
- Earth surface as a 3D sphere

---

## 🌐 Physical Constants

| Constant      | Value                | Unit            |
|---------------|----------------------|------------------|
| `μ` (mu)       | 398600               | km³/s² (Earth's gravitational parameter) |
| `R_earth`      | 6371                 | km (Earth's radius) |

---

## 📐 Initial Conditions

- **Initial Position:** `[8000, 0, 6000]` km  
- **Initial Velocity:** `[0, 7, 0]` km/s  
- **Simulation Duration:** `4 hours (14400 seconds)`  
- **Solver:** Runge-Kutta (RK45), 1000 evaluation points

---

## 🖼 Visualizations

✅ 3D orbit path of the satellite  
✅ Earth as a sphere (semi-transparent)  
✅ Altitude variation over time  
✅ Apogee & perigee clearly labeled  

---

## 📈 Sample Output

```

Apogee Altitude: 2562.87 km
Perigee Altitude: 1771.35 km

````

---

## ▶️ How to Run

```bash
python satellite_orbit_sim.py
````

---

## 📦 requirements.txt

```txt
numpy>=1.26.4
scipy>=1.13.0
matplotlib>=3.8.2
```

Install with:

```bash
pip install -r requirements.txt
```

---

## 📂 Project Structure

```plaintext
📁 gps_orbit_sim/
├── satellite_orbit_sim.py    # Main Python script
├── README.md                 # Project documentation
└── requirements.txt          # Dependencies
```

---

## 📚 Academic Context

This simulation is a foundational step in understanding orbital mechanics and satellite trajectory analysis — a key aspect of GPS satellite positioning and space-based navigation systems.

---

## 👩‍💻 Author

Created with scientific care by **Farzaneh Naderi**
📍 GitHub: [@Farzanehnaderi](https://github.com/Farzanehnaderi)
📧 Email: [farzanehnaderi@ut.ac.ir]



آیا دوست داری فایل‌های `README.md` و `requirements.txt` رو به‌صورت آماده برای دانلود یا بارگذاری در GitHub برات بسازم؟
```

